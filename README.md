Sanzang Tables
==============

About
-----
Sanzang is a system for translating from CJK languages -- Chinese, Japanese,
and Korean. You can define your own translation rules as you need them, and
these are stored in simple delimited text files. These rules define how to
translate specific words and phrases.

The files contained here are "translation tables" -- sets of translation rules
for Sanzang. By running the Sanzang Utils translator with one of these table
files, you can generate rough translations. For example:

    $ cat mytext.txt | szu-r | szu-t zh_en_tripitaka

For the programs that use these tables, see Sanzang Utils:

<https://github.com/yaoguai/sanzang-utils>

Following Development
---------------------
The translation rules here are regularly revised, added to, and improved. If
you are interested in using these translation tables, then you should track
their development so you can use the latest versions.

Redistribution
--------------
If this project is subject to copyright or database rights, then these rights
are waived universally to the maximum extent of the law. This data should be
regarded as knowledge in the public domain.

To help facilitate this worldwide, the Creative Commons Zero (CC0) license is
used, which is a tool for releasing works into the public domain. See the file
COPYING.md for more details.

Table: zh_en_tripitaka
----------------------
* Source: Traditional Chinese from the Taisho Tripitaka (e.g. CBETA)
* Targets: (1) Hanyu Pinyin, (2) English
* Encoding: UTF-8
* Description: Translation from the Chinese Buddhist canon
* Entries: 7000+
