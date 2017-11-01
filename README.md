# python-fontforge-script

Python Script for Font Manipulation using FontForge Module

[![Build Status](https://travis-ci.org/Kennyl/python-fontforge-script.svg?branch=master)](https://travis-ci.org/Kennyl/python-fontforge-script)

**Please install python-fontforge module first as well as PyQt5**

# [minimizeFont.py](../../blob/master/minimizeFont.py)

Python script that minimize ttf font by input word list

Use [minifyGlyphs](../../blob/master/minifyGlyphs) as input word list

Word list format
```
## start with "##" line will be ignore to read
A
B
C
```

# [copyReferenceAtoB.py](../../blob/master/copyReferenceAtoB.py)

Python script that copy glyph 'A' to glyph 'B' by Reference

Use [copyReferenceAtoB](../../blob/master/copyReferenceAtoB) as input word list

Word list format (Copy glyph 'A' to glyph 'B', copy glyph 'C' to glyph 'D')
```
## start with "##" line will be ignore to read
A B
C D
```

# [checkMissingGlyph.py](../../blob/master/checkMissingGlyph.py)

Check Missing Glyph in word list [missingGlyphs](../../blob/master/missingGlyphs) 

Word list format
```
## start with "##" line will be ignore to read
A
B
C
```