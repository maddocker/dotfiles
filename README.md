# Purpose
To keep all of my system-agnostic user configs in one place. This way, my UI and tooling configs are transferrable for a (hopefully) consistent experience across Linux machines, no matter the host hardware or specific distro
(although some assumptions are made, such as Wayland being supported on the system for Sway and Waybar).

Commercial systems keep causing me grief with their proprietary, uncontrollable, and ever-changing UIs. Having my tweaks centralized like this in an easily deployable manner means that I will be more encouraged to use free software as time goes on,
as I can both change things at will and leave them be indefinitely without breakage.

# Deployment
1. Install desired applications and GNU Stow depending on host system.
2. Clone this as a new folder into your `home`.
3. `cd` into this folder.
4. Deploy each application's user config into their spots: `stow [subfolder]` for each desired subfolder in this repo

# Neovim/NVChad
This subfolder specifically requires both installation of Neovim and the [NVChad distro](https://nvchad.com/docs/quickstart/install), after which you can `stow` this custom init file. There is likely a better way to do this, but this is what I got.
