# dl-assets
Repo for Dragalia Lost assets. Currently just holds character story portraits/expressions, but may include more later.

# FAQS
## Why are some of the different expressions for the story sprites identical?
Unfortunately this is just how they are in the game data. I've tried to programmatically dedupe them as much as possible but since they do all actually have very slight pixel differences, some may have slipped through the differ threshold. Feel free to report those through the Issues tab if you see them.

## Why are some of the labels for the characters missing/incorrect?
Some labels require manual entry and are thus subject to human error. Please feel free to contribute a correction to [this mapping](https://github.com/yvsdrop/dl-assets/blob/master/storysprites/index.json).

## Why am I allowed to select invalid expression combinations?
Mouth/face combinations are not actually deterministically available in the data, so I'm using a basic heuristic to divide them, and it might capture some false negatives. If you come across any bad cases, please feel free to report in the issues tab.

# Credits
* [sh0wer1ee's multi-language localization](https://github.com/sh0wer1ee/DLPortraits): Localized labels were taken from a snapshot of sh0wer1ee's multi-locale labelled characters and manually merged in where applicable.