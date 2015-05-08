# Notes

- Allow entries in the toc that do not lead to an own file but to the anchor on the parent level. or should those entries automatically be retrieved from the content of the file and added to the TOC as published?
- allow entries where the chapter name does not match the title in the TOC (or use the the first title in `.md` file for generating the html TOC?

## TOC

- Introduction
  - Scribus has slowly improved year after year and there are good chances that a few of the changes we propose will be the standard in the future (or some settings will be automatically detected for you)
- Setting up some basic preferences
- Cleaning up the user interface
  - Scribus offers you lot of control on the way your text and images are layouted. This comes at a cost: there are many buttons, input boxes, dialogs filling your screen to get the work done. The following hints try to point you to some of the widgets that you can turn out without missing any (or very little... i mean the time to get used to the alternative or switching it on only when you used it) "lost".
  - show the Properties Palette and put it on the right side of your Scribus window (on top of the Scribus window, not on right of it; except if you have a very wide monitor; in 1.5 it can be docked) and learn the F2 key to show and hide it. Refrain from moving it from keeping moving it around.
    - probably the most important place in Scribus: you will keep on using it
    - always at the same place for the brain muscles
  - hide all the toolbars but the tools.
    - from other applications, you might be used to open files, copy and paste or print through the toolbars: those are "slow" shortcuts. if you're happy with being slow, go for the the menues, if you want to be fast, learn the keyboard shortcuts: most of them are the same accross all applications and computers: it's a good investment to learn them.
    - if you notice that you really need them, you can always re-enable them later.
    - try to use the keyboard shortcuts instead of the toolbar buttons.
    - the only toolbar that you need is the Pdf one, and you only need to create interactive PDF forms (and this is a thing that most Scribus never or very rarely do: show it when you need it).
  - Move the tools tolbar to the left of the Scribus window and dock it there.
- Settings part two
  - disable showing the startup dialog (mostly you're faster by typing ctr-o and ctr-n to open or create a new document)
  - enable snapping (should already be on in 1.5 and not possible to enable on 1.4; move it to the first steps after creating a document?)
  - set ctrl-shift-p for producing a pdf and ctrl-alt-p for switching the preview mode
  - Set the default page margins to something you will mostly be using (for europe probably 1cm on each side)
  - In the tools
    - text: choose a meaningful default font (by default it's the first one, in alphabetical order, mostly a bold one).
      - On Linux and most free systems "DejaVu Sans Book"?
      - On OS X
      - On Windows
    - image: Scale image to frame size and keep ratio
    - other tools: for duplicate set the horizontal and vertical displacement to zero (you want the duplicate to be at the same place as the original, and the move it with the keyboard)
    - setup the hyphenation language
      - if your language is not available, please refer to...
  - set the Preflight verifier to check for the most common PDF version for you. if in doubt choose 1.4 (really?).
- Colors, fonts, ...
  - You should not bother about them in your first steps with Scribus please refer to...
- Your first document
  - If you have not done so yet, it's time to create your first document
  - some clue on what to take care
  - `file > new`
  - text goes into text frames, images in image frames
  - scribus does not dynamically create the pages for you. you can define the number of pages -- if you already now it: this is common for small brochures -- when creating the document or add pages as you need thorugh `page > insert`.
  - you fill find answers to your most likely questions in the "second steps" document.
- what is scribus / what scribus is not / what scribus might be (if you are creative)
- ghostscript:
  - Ghostscript for Windows can be downloaded from here: <http://ghostscript.com/download/> There are downloads for both 32 and 64-bit systems.
