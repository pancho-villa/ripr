ripr
====

A tiny app to record any internet stream

Requirements
===
Python 3

It was written solely in Py3k so if you want Python 2, you'll have to run 3to2.py or port it over. Pull requests gladly accepted, so long as you create  compatibility shims in the code base so there aren't duplicates of everything.

Usage
===

from command line
---
    >>>python __init__.py URL HH:MM:SS -p PATHTOLOCALFILE

It writes to the local file after the elapsed time the file you ripped. For example this records wemu for 1 minute to the same directory as the __init__ file but you can give it any fully qualified full path with any extension:

    python __init__.py http://pubint.ic.llnwd.net/stream/pubint_wemu  00:01:00 -p output.mp3
