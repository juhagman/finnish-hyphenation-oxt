# finnish-hyphenation-oxt
Libre Office Extension for hyphenating Finnish with static Hunspell patterns.

(C) 2016 Jussi Hagman

## License

For my code BSD-style. Unlimited copying, redistribution and modification of this file
is permitted with this copyright and license information.

Parts of the repository have their own Licenses.

Hyphenation patterns originate from CTAN.
The extension structure is stolen from hyph-en.oxt. Original changelog retained. 

## Introduction

For hyphenating Finnish language, the go-to tool is usually Voikko. I hear works great for Libre Office and more. 
Unfortunately I did not get it working with Calibre, with which I tried to convert and hyphenate Finnish
language eBooks.

I could not find a Libre Office Extension with static hyphenation patterns, so I decided to create one. The 
hyphenation patterns are converted from TeX patterns for Finnish found on CTAN. The Extension is based on an English 
dictionary extension downloaded from Libre Office site. 

## Building

    $ rake

Creates `dict-fi.oxt` file in the project root.

## Installation

Add the resulted file where ever it is needed, e.g. Calibre.
