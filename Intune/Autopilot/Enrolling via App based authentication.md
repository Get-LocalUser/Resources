## Overview

I was tired of manually entering and authenticating with a username and password when using the `Get-WindowsAutopilotInfo` script, so I created an app registration in Entra ID to streamline the process. I struggled a bit with the API permissions, but with the help of [Andrew Taylor's blog](https://andrewstaylor.com/2023/06/13/authenticating-to-new-get-windowsautopilotinfo/) and a few other resources, I managed to get it set up... I think! Now it’s time to test once I get this next VM up.

### Update

It worked! 🎉 Now, if this script is run on a brand-new, out-of-the-box machine, it might not save much time over entering a username and password manually (unless you load a `.ps1` file onto a USB stick and run it from there) so I suppose it didn't so much as streamline it as much as provide an quicker way to enroll on an existing device. However, if it's executed on a machine already in use, this setup could be quite helpful, especially if you're not using `Convert all targeted devices to Autopilot` in Intune.