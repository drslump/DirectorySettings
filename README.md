DirectorySettings for SublimeText 2
===================================

Place `.sublime-settings` files in a directory and, if you open a file in that directory, the settings will get applied to the file's view. Settings can nest in directories; in the event of conflict, the deepest settings files win.

Much `TODO` here, including:

- performance
- watching for settings changes

Example: To get a different color scheme for files in a given directory, add a `.sublime-settings` file to `~/code/project/` that reads:

    {
        "color_scheme": "Packages/Color Scheme - Default/SpecialTheme.tmTheme"
    }

That is all for now!