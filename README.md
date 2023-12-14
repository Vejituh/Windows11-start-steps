# First Boot

**If explorer crashed on first boot, use task manager to end and restart explorer.exe.**

**Install any network drivers if needed before hand.**
1. Run windows updates and restart untill all are installed.
2. Run any driver updates.
    1. Chipset Drivers.
    2. GPU Drivers.
    3. Mouse & Keyboard Drivers.
    4. Printer Drivers (if needed).
    5. Check if bios version needs updated.

# Winutil

[Winutil Github Repo](https://github.com/ChrisTitusTech/winutil)
1. Run Terminal as Admin
2. Run `iwr -useb https://christitus.com/win | iex`

**First re-install winget in the config tab because of Windows 11 bug**

3. Go to Tweaks tab and select `Desktop` in the Recommended Selections and then also tick remove onedrive and hit `Run Tweaks`.
4. Then go to config tab and select `All .Net Framework (2,3,4)` and hit `Install Features`.

## Install Apps

1. Open a terminal
2. Start a command with `winget install ` and then add the following of your choice -
    **Browser**
    1. Mercury (Firefox based browser): `Alex313031.Mercury`
    2. Thorium (Chrome based browser): `Alex313031.Thorium.AVX2`
    3. Firefox: `Mozilla.Firefox`
    4. Chrome: `Google.Chrome`
    5. Vivaldi: `VivaldiTechnologies.Vivaldi`
    6. Brave: `Brave.Brave`