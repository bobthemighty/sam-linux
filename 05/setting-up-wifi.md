To set up wifi, we're going to use wifi-menu. This is a handy little tool that will help you configure your wifi-card to talk to your router.

Because wifi-menu can change your computer's settings, it needs root privileges. You already know how to act as root, right?

wifi-menu is already installed on your machine, run it now. You will need to select the plusnet router, and then enter the right password.

When that's finished, you should be able to type `ping google.com` and see that you are connected to the internet.

To make your wifi start automatically, you'll need to set up a *service*. At this point call Dad for help with setting up the systemd unit.

Congrats Sam, you're on your way to Linux-mastery!
