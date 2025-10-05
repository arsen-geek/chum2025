# A_HDE
Advanced Humor Detection Examples. A dataset for humor detection in Russian language.

Supplementary of the BA thesis of Arseny Anisimov and for the application for the Workshop on Computational Humor.

## Column Names in the Dataset
* `num`  number of the near duplicate group
* `setup`  set-up, the first part of the text
* `punch`  punchline, the last part of the text
* `text`  full text
* `humor`  `0` if the text is non-humorous, `1` if it's humorous
* `type`  type of the humor mechanism: `GP` (garden path), `RL` (red light), `C` (crossroad)
* `connector`  position of the connector
* `typeall`  the same as `type`, but for all texts of invariant
* `connectorall`  the same as `connector`, but for all texts of invariant
* `nopair`  comment `nopair` if there is no duplicate
