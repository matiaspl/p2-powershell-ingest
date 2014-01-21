p2-powershell-ingest
====================

Automated ingest solution for P2 cards under Windows

This script was hacked up to get around mediocre transfer speeds in Panasonic's own P2 Viewer software. It's running on an old Intel Core Duo Toshiba laptop with internal GBit network interface

What it does is:
  1. Detect if a P2 card has been put into a PCMCIA slot
  2. Present a simple GUI that allows to select the destination (main NAS or one of the workstations)
  3. Show a copy progress bar
  4. Erase the card if needed

The files always land in "p2-ingest" folder in a subfolder named after the current date, preserving the file structure so it's readable in both P2 Viewer and Adobe Premiere.

Matt
