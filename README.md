# Fork of [react-native-render-html](https://github.com/archriss/react-native-render-html)

This fork is specifically for use with Atlas volumes body. Forked at v4.1.1. I don't think they specific things can be done without forking. The original repo is in active dev right now, so upstream changes might have to be merged so it can also include fixes from the original repo.

Versions of this package will be versioned like: 4.1.1-alpha.x

This hacked version includes:

    * An activity indicator for images.
    * Wrapper for images so images can be centered.
    * If bold styling is present inline, switches font to 'Lato_bold'.
    * Fix for image blur issue.
    * Smaller margin for uls