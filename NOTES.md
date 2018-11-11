# Getting Scribus

## Getting the `.dmg`

https://www.scribus.net/downloads/stable-branch/

will send you to

https://sourceforge.net/projects/scribus/files/scribus/1.4.6/

where you can download

https://sourceforge.net/projects/scribus/files/scribus/1.4.6/scribus-1.4.6.dmg/download

(just don't click too much around, since sourceforge tends to show
"deceiving ads")

you then have a dmg that you can install as every other dmg...

## Homebrew

If you have Homebrew installed, you can use it instead of downloading the DMG.

## First launch of Scribus

Like most indipendent Software, Scribus is not signed with an Apple Developer Certificate. The first time you open Scribus, you cannot double click the Scribus icon or a Scribus document. For the first start, you need to use the open command in the context menu: right click (or ctrl-clik) on the application Icon and choose "Open", carefully read the message and if you agree with it, click the "Open" button to start Scribus.

From now on, you will be able to start this copy of Scribus by double clicking the Scribus icon or a Scribus document.

A few remarks:

- This processess has to be repeated each time you download a new version of Scribus.
- You need to find the Scribus in the finder, in the "Applications" directory. Spotlight does not give you access to the context menu.
- Scribus is signed with a standard GPG process. You can download the GPG key from the Scribus download page and verify your copy with `gpg --verify ...`.

It is to be noted, that the official Scribus 

 Failing to do will give you a signature error.
 - On some os x versions, the first you run an application you did not get from the appstore, you have to right click on the application icon, choose open and confirm that you want to open the application you downloaded from the internets.

## Where are the preference files?

On MacOS, the preferences are in

`~/Library/Preferences/Scribus/`

`~` is your Home directory, typically: `/Users/Your-name`

In the Finder, you can open _your_ Library directory by holding down the "option" while the "Go" menu: among other "places", it will show your “Library” directory.

## Where is Ghostscript?

### You don't really need it. Mostly.

Suring your first steps with Scribus, you can probably safely ignore the message asking for
ghostscript.

The day you will need it, you will notice!

### Installing Ghostscript

You can download a DMG for Ghostscript from

http://pages.uoregon.edu/koch/

Scribus should recognize it on the next start (I've tested it and it was recognized!).

## Adding fonts
