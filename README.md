# PKGBUILD-AppImage
This repo contains a template and two examples of Arch Linux PKGBUILDs for packaging 
AppImages in a standard Arch Linux .zst package used in the DeLinuxCo project.

DeLinuxCo delivers AppImages using a custom repo. The AppImages are installed in the system like any other package,
to the user, it is completely transparent.

This repo contains three directories, template-appimage, darktable-appimage and
zen-browser-appimage.

The **template-appimage** is self explanatory, anyone can use it as a starting point generate Arch Linux package to
deliver AppImages via a repo.

The **darktable-appimage** shows an example of extracting the icon and .desktop file for integrating directly
from the appimage.

The **zen-browser-appimage** shows how to supply your own icon and .desktop file. In Zen-browser's case,
the AppImage comes with a .png icon.

Best practices so far, subject to change.

* Avoid using .png icons, use SVG instead. Installing an .svg icon in 
/usr/share/icons/hicolor/scalable/apps/ has been most reliable.

* Use the same naming convention for the .desktop file as in the AppImage.





