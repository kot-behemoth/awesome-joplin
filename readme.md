# Awesome Joplin [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of all things Joplin


## Contents

- [Themes (`userstyle.css` and `userchrome.css`)](#themes-userstylecss-and-userchromecss)
- [Tools](#tools)
- [Plugins](#plugins)
- [Tutorials](#tutorials)
- [Contribute](#contribute)
- [License](#license)


## Themes (`userstyle.css` and `userchrome.css`)

- [amandamcg's custom styles](https://github.com/amandamcg/joplin-theme) - [UI], [Editor], [Dark].
  
  ![](https://raw.githubusercontent.com/amandamcg/joplin-theme/master/screenshots/v0.7.1-updates.png)

- [devonzuegel's custom styles](https://github.com/devonzuegel/joplin-custom-css) - [Editor], [Light].

  ![](https://raw.githubusercontent.com/devonzuegel/joplin-custom-css/master/v1.png)
  
- [tessus's custom styles](https://github.com/tessus/joplin-custom-css) - [UI], [Editor], [Dark].

  ![](https://raw.githubusercontent.com/tessus/joplin-custom-css/master/images/Dark.png)
  
- [gloden-2020](https://github.com/lightzhan/joplin-theme-gloden-2020) - [Editor], [Light].

  ![](https://raw.githubusercontent.com/lightzhan/joplin-theme-gloden-2020/master/pic/example.png)

- [Charles' custom styles](https://git.sr.ht/~charles/dotfiles/tree/0363ef08173f4af4c89f2e4081d165903aa27e93/overlay/.config/joplin-desktop/userstyle.css) - [Editor], [Light].
   
-  [joplin-Nord2](https://github.com/mattsbennett/joplin-Nord2) - [UI], [Editor], [Dark], [Fonts]. A sub-theme of Joplin's built-in Nord theme.
   
  ![](https://raw.githubusercontent.com/mattsbennett/joplin-Nord2/master/img/Nord2.png)

- [Joplin Dark Gruvbox](https://github.com/robotcorner/joplin-theme-dark-gruvbox/blob/master) -[UI], [Editor], [Dark]

  ![](https://raw.githubusercontent.com/robotcorner/joplin-theme-dark-gruvbox/master/screenshots/sample-img1.png)
  
- [hrqmonteiro's NeptuneJoplin](https://github.com/hrqmonteiro/joplin-theme) - [UI], [Editor], [Dark], [Icons]. Advanced custom theme with heavy inspiration from _Things 3_.

  ![](https://raw.githubusercontent.com/hrqmonteiro/joplin-theme/master/assets/screenshot1.png)

- [joseajohnson's custom theme](https://github.com/joseajohnson/joplin-style-dark-colors) - [UI], [Editor], [Dark]. Alternating rows on lists with muted colors, larger, bolder editing styles, KaTeX hues.

  ![](https://raw.githubusercontent.com/joseajohnson/joplin-style-dark-colors/main/img/joplin-style-dark-colors_00.png)
  ![](https://raw.githubusercontent.com/joseajohnson/joplin-style-dark-colors/main/img/joplin-style-dark-colors_10.png)

- [Wanaka UI](https://github.com/benji300/joplin-wanaka-ui) - [UI], [Editor], [Dark], [Light]. Requires Joplin v1.4.12 or newer.

  ![](https://raw.githubusercontent.com/benji300/joplin-wanaka-ui/master/assets/main-light.png)
  ![](https://raw.githubusercontent.com/benji300/joplin-wanaka-ui/master/assets/main-dark.png)

- [VSCode Community Material Theme](https://github.com/mahor1221/joplin-vsc-material-theme) - [UI], [Dark].

  ![](https://raw.githubusercontent.com/mahor1221/joplin-vsc-material-theme/master/screenshots.gif)

## Tools

All of these are mostly sourced from the [#apps topic](https://discourse.joplinapp.org/c/apps/11) on the [official Joplin forum](https://discourse.joplinapp.org).

- [Web Clipper](https://joplinapp.org/clipper/). A browser extension that allows you to save web pages and screenshots from your browser. To start using it, open the Joplin desktop application, go to the Web Clipper Options and follow the instructions.joplin-dashboard
- [File Uploader and OCR (a.k.a. REST Uploader)](https://github.com/kellerjustin/rest-uploader), [[discussion](https://discourse.joplinapp.org/t/file-uploader-and-ocr/719)]. Command line companion application to supplement Joplin. The app monitors a directory you specify; when new files are created in the directory, it automatically uploads the file as text or an attachment (depending on file type) to a new note in Joplin. The app performs OCR on images and PDFs, and the text is dropped into the note as a comment. An image preview is also created for PDFs.
- [Python Joplin API](https://github.com/foxmask/joplin-api). The API of Joplin Editor in Python 3.6+.
- [Replace Evernote links in Joplin](https://github.com/pentop/replaceEvernoteLinksWithJoplin). A script which uses the Joplin API to globally search-and-replace Evernote links within notes with native Joplin links.
- [Send email from Outlook to Joplin](https://gist.github.com/ramisedhom/0f34c5d6a8d73f0b98ac4bea2ec30be0). A VBA script (Visual Basic for Application) to send the subject of selected emails from Outook to Joplin Desktop.
- [Ghoplin](https://github.com/zblesk/Ghoplin). A tool for downloading posts from Ghost blogs into Joplin.
- [notestation-to-joplin](https://github.com/KraxelHuber/notestation-to-joplin), [[discussion](https://discourse.joplinapp.org/t/python-script-for-importing-notes-from-synologys-note-station-into-joplin/6605)]. A Python script that extracts notes (including attachments) from Synology’s Note Station and imports them into the Joplin app.
- [joplin-mail-gateway](https://github.com/manolitto/joplin-mail-gateway). This tool provides a solution for emailing content directly into your Joplin notes.

  You may send or forward an email to a dedicated email address. This email is than automatically delivered to your personal Joplin notes. Attachments (PDFs, Images, ...) will automatically be included in the note. In addition text is automatically scanned from images via OCR. This extracted text is added at the bottom of the note so that it is easily searchable in Joplin.
- [joplin-bulker](https://github.com/andgineer/joplin-bulker), [[discussion](https://discourse.joplinapp.org/t/bulk-tag-delete-python-script/5497)]. Python script to bulk remove tags from Joplin files.
- [Dashboard home page from Joplin](https://gist.github.com/ramisedhom/47eee0a3e4eb887f02c3730ed5b3c211).

  ![](https://aws1.discourse-cdn.com/standard14/uploads/cozic/original/2X/d/d02532a55a0c529b6cb24f94f02f708d606c7a19.png)

- [Yeoboseyo](https://github.com/foxmask/yeoboseyo), [[discussion](https://discourse.joplinapp.org/t/yeoboseyo-the-bus-for-your-internet-services/2771)]. "The bus for your internet services." A companion for Joplin which allows creating notes from RSS Feeds, plus others possibilities, like publishing the same RSS Feeds on another service, like Mastodon.
- [Web Clipper for Safari](https://github.com/cweirup/JoplinSafariWebClipper), [[discussion](https://discourse.joplinapp.org/t/safari-app-extension-for-joplin-now-available/9660)]. [Beta] Safari Web Clipper. It does the basics: Clipping pages (complete and simplified); clipping URLs and selections; tagging; selecting folders; changing the title; checking on server status and disabling the controls if Joplin isn’t running. It’s based on the Web Clipper for Chrome and Firefox provided with Joplin, with Javascript modifications to support Safari App Extensions and, of course, a native-based UI. Some things are not implemented (complete HTML clipping and screenshot capture), but the basics are there.

  One item to note: It does operate differently than the Chrome/Firefox Extension, in that the “Clip” buttons operate immediately. There is no “Confirm” step after selecting your Clip option.


## Plugins

### Official Joplin Plugin Repository

Since roughly January 2021 there exists an [official Joplin Plugin Repository](https://github.com/joplin/plugins), and Joplin app has a simple way of discovering and installing available plugins. To install any of these plugins, open the desktop application, then go to the "Plugins" section in the Configuration screen. You can then search for any plugin and install it from there.

### Old-style plugins

This is a list of plugins that were created before the official plugin repository existed. Here are a few interesting ones:

- [Make all possible links](https://github.com/S73ph4n/joplin_make_all_links) [Experimental] Goes through the current note looking for words (or groups of words) matching another note's title. When found, makes them into links to the corresponding notes.
- [Link to note](https://github.com/S73ph4n/joplin_autolinker) [Experimental] Checks if the selected text matches an existing note's title. If such a note exists, makes a link to it. If it doesn't, creates it.
- [Automate notes with JS](https://github.com/S73ph4n/joplin_automate_notes) [Experimental] Execute blocks of Javascript in the note, writing the results below.
- [Note tabs](https://github.com/benji300/joplin-note-tabs) [Experimental] Display the selected note in a tab panel and allows to pin/unpin notes as tabs.
- [Create note from highlighted text](https://github.com/ambrt/joplin-plugin-create-note-from-text), [explanation](https://discourse.joplinapp.org/t/create-note-from-highlighted-text/12511) [Experimental] Turns text or block of text into new note under active folder.
- [Statusbar](https://github.com/tbergeron/joplin-statusbar) [Experimental] Very simple plugin that adds a view to use as a statusbar. For now it only displays the last sync time.


## Tutorials

- [Send screenshot to Joplin](https://discourse.joplinapp.org/t/send-screenshot-to-joplin-windows/4918). A way to take desktop screenshot and save it automatically to Joplin [Windows].


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Greg Goltsov has waived all copyright and related or neighboring rights to this work.
