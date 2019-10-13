# browserphotos

Single-page HTML/JavaScript app that works from a `file` URL and shows an arrow-key-navigable slide show of photos and videos.

## License

MPL 2.0

## Use Case

Your desktop Linux distro doesn't come with a viewer that shows both JPEGs and video files in a single slide show like the Windows 8 Photos app or GraphicConverter on Mac.

## Usage

* Copy the file `00_slideshow.html` into a folder that contains photos and videos.
* Insert a list of the file names for the photos and videos (must have `.mp4` or `.webm` file name extension in lower case) in the order you want to see them in in the source code into the JavaScript array initializer for `var files`.
* Open `00_slideshow.html` in a Web browser.
* Put the Web browser in its full-screen mode (F11).
* Navigate with arrow keys, pg up/down, space/backspace.

## Missing features

* Touch support.
* Going backwards my mouse.
