## README for hunspell-de-med-workaround


###Overview

    Description:        de_DE German hunspell dictionary modified to include hunspell-de-med
    Terms:              172101
    Author:             Glutanimate (https://github.com/Glutanimate)
    Original Authors:   Bjoern Jacke <bjoern@j3e.de>, Franz Michael Baumann <frami.baumann@web.de>,
                        Tobias Quathamer (https://launchpad.net/~toddy)
    Sources:            - hunspell-de-de-frami (20100305)
                        - hunspell-de-med (20110608-1)
    License:            GNU GPL v3 (see LICENSE.txt for more information)


###Description

This project hosts hunspell dictionary files based on hunspell-de-de-frami and hunspell-de-med. It is a temporary workaround to the various issues surrounding the use of add-on hunspell dictionaries with LibreOffice and OpenOffice (1).


###Installation

    git clone https://github.com/Glutanimate/hunspell-de-med-workaround.git
    cd hunspell-de-med-workaround
    sudo cp de_DE.dic '/usr/share/hunspell/de_DE.dic'
    sudo cp de_DE.aff '/usr/share/hunspell/de_DE.aff'

###Restoring the original dictionaries

**Ubuntu/Debian**

    sudo apt-get install --reinstall hunspell-de-de-frami

###Warranty

This software comes with no warranty of any kind. Some misspelled words might be included.

###Sources

(1): https://bugs.launchpad.net/ubuntu/+source/language-support-extra-de/+bug/363619, https://bugs.launchpad.net/ubuntu/+source/openoffice.org/+bug/329968 and https://bugs.launchpad.net/medicalterms/+bug/401423
