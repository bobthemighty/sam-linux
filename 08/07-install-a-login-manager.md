Last step!

Until now, whenever we rebooted the machine, it loaded the same boring black screen. To fix that we'll install a Display Manager. The Display Manager is responsible for choosing which desktop you want to use, and for logging you in.

To install it type `pacman -S sddm`.

sddm installs a *service* (remember those from the wifi bit?) so we need to enable the service so that it will start when the machine boots.

type `sudo systemctl enable sddm`.

Now reboot!
