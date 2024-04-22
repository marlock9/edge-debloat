# edge-debloat
Registry key to disable (most of) the bloat in Microsoft Edge. I did it just for me, but decided to share. **I don't need any browser functionality other than just being a browser**, so I disabled many "features" one may find missing. In this case look how to customize registry key for yourself. Page with description of all policies: https://learn.microsoft.com/en-us/deployedge/microsoft-edge-policies

# Before installation
Starting Edge after adding this registry key *may* delete your profile because of explicitly setting one profile, so do a backup of profile directory first. To find your profile's directory, look at the page `edge://version/`, value of `Profile path:`.
I'd appreciate feedback on this.

# Installation
Download edge-debloat.reg from `main` branch and install it with admin privilegies.
Run Edge, go to `edge://policy/` page and press `Reload Policies` button.
You have to `Reload Policies` after every update.

# Updates
I'm trying to keep this policy up-to-date with newly releasing changes described on this page: https://learn.microsoft.com/en-us/deployedge/microsoft-edge-relnote-stable-channel

# Contributing
If you think I missed something important, or I disabled something important (mainly I'd care about security functions), feel free to create issues/pull requests
