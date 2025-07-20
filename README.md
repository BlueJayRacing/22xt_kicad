# 22xt_kicad, JHU Blue Jay Racing Repository
This is the KiCad Repository for the JHU 22XT DAQ Sub-team.


## Installation and User Guide
GitHub & KiCad Guide: https://docs.google.com/document/d/1nFm-e38JEY4i58-0UFxqdLA5TKqWCrV3EDKR8jGpRfA/edit?usp=sharing 

As a summary, you should be using **KiCad Version 9**. All project will be modular, and you should be storing all your step files, symbols, & footprints within the created folders.

Schematic settings & layout settings are described in the guide, as well as component derating.

## Branch Guide
You should be working on a new branch for each revision of your board. It is only when your board gets ordered on JLC that it should be merged with the main branch.

Branch naming structure: [boardname]_rev[0X]

Example:
> main_board_rev01

<ins>How-To Create a Branch:</ins>

```
git checkout -b [your_branch] main
git push -u origin [your_branch]
```
