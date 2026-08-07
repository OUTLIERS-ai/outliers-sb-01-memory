# Outliers Second Brain - Layer 1 - Memory

You explain your business to an AI, it understands, you close the window, and all of it is gone.
Next time you start from nothing and explain it again.

This layer gives it somewhere to write things down that is still there tomorrow.

## Install it

From this folder:

    python install.py

It asks you three questions, makes the folder, writes the rulebook your AI reads before it does
anything, and points your AI at the folder so it can be found from anywhere.

## What it needs beneath it

Nothing. This is the bottom of the ladder.

You need Python 3.8 or newer, and git if you want a copy of every change kept - the installer
will tell you plainly if either is missing rather than failing quietly.

## What you end up with

    Second Brain/
      People/  Projects/  Areas/  Meetings/
      Resources/  Ideas/  Decisions/  Archive/
      CLAUDE.md        the rulebook your AI reads first. Yours to edit.
      .gitignore       refuses to keep passwords and keys in your history
      _layers/         which layers are installed

Plus a line written into your AI's own settings saying where the folder is, so you can ask about
your business from anywhere rather than only from inside it.

## Using it

Talk to it. Tell it what happened; it decides where that goes. Then ask it something you would
otherwise have to remember.

The test that this layer worked: it answers a question about your own business that a fresh chat
window could not have answered.

## What this layer leaves unsolved

A folder accepts anything, and it has no idea what a good note looks like. Two notes can end up
with the same name and different contents, and a link to that name then resolves to whichever was
found first - with nothing telling you that happened.

That is Layer 2.
