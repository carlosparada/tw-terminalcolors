# tw-terminalcolors

Terminal.app (macOS) profile colors based on Tailwind CSS colors

# Installation

## Terminal Profile

Clone this repository or download the Tailwind*.terminal files. After that, open Terminal.app on macOS and go to Terminal > Preferences... (Cmd + ,) and then click on the Profiles tab. There is a button with ellipsis inside a circle, next to the plus (+) and minus (-) buttons. Click the button and select Import... then select the profile file you want to import (e.g. Tailwind.terminal). You can import only one profile at once.

![Image of Terminal.app Profile Preferences](/img/pref-profiles.png)

If desired, you can click one of the Tailwind profiles imported and then click on the "Default" button if you want all new Terminal windows to use the specified profile.

## Color Picker

You can also add the whole set of Tailwind colors to the standard macOS Color Picker. Type the following at the Terminal command prompt:

```sh
cp TailwindCSS.clr ~/Library/Colors
```

![Image of Color Picker](/img/color-picker.png)
