```
Warning!
The README.md information in the "development" branch may not be correct.
It is constantly supplemented, changed and corrected for the final release.
With proper reference in this branch, you can find out information about new updates.
```

# 16Theme
![Banner](/1.6-css.png "1.6-CSS")

![](https://img.shields.io/badge/latest-1.5-informational)
![](https://img.shields.io/badge/stable-1.4-informational)
<br>
| Branch      | Name         | Status                                                          | Game |
|-------------|:------------:|-----------------------------------------------------------------|------|
| stable      | 16Theme      | ![](https://img.shields.io/badge/-default_branch-informational) | CS:S |
| bug-fixes   | 16Theme      | ![](https://img.shields.io/badge/-merge_branch-informational)   | CS:S |
| development | 16Theme      | ![](https://img.shields.io/badge/development-finished-informational) | CS:S |

## Installation
1. Download latest release
2. Move the file to "game folder"/cstrike/custom/
3. Run game

## Installation (repository)
1. Clone this repository
2. Move the "16Theme" folder to "game folder"/cstrike/custom/
3. Run game

## Screenshots
![Screenshot 1](/scr1.png "Main menu")
![Screenshot 2](/scr2.png "Windows")

# For developers
## Release badges
| Badge                                                              | Meaning      |
|:------------------------------------------------------------------:|:------------:|
| ![](https://img.shields.io/badge/Supported-01.01.23-informational) | Supported version with end of support date. |
| ![](https://img.shields.io/badge/Unsupported-gray)                 | No longer supported version. Still might be stable. |
| ![](https://img.shields.io/badge/Stable-success)                   | The version has been tested and does not have critical bugs. |
| ![](https://img.shields.io/badge/Legacy-yellow)                    | An outdated version that is not recommended for use. |
| ![](https://img.shields.io/badge/Pre--Release-22f)                 | A version with minor changes from the previous one, released without updating the repository. |

### Pre-release versions (intermediate releases)
Well, if one day you find a release with the "Pre-Release" badge, you may also notice that the stable branch will still not have any new features since
the released version. Let's explain. Pre-Release versions are versions that have already been tested and have new or changed features, but these changes 
are so minor that they cannot be inserted into a completely new version.
So, instead of "1.5" you will see "1.4.1" or "1.4.2".
But still, in fact, it will not be version 1.4, but 1.5.

### Legacy version (really old releases)
Looking through the releases page, you will come across the "Legacy" badge. How to understand such releases?

If a release has such a badge, then it received it for one of the following reasons:
- Project renaming
- Incompatibility with previous versions
- Incompatibility with new versions of the game
- Changed in the future the distribution format of the addon

The 1.0 release fits the first reason, and the 1.1 release is labeled for the fourth reason.
These releases are no longer useful and are not recommended.

### Version check plan.
- Checking the GUI elements in the main menu in the aspect ratio of the screen 4:3; 16:9; 16:10
  - Find servers
  - Create a server
  - Achievements
  - Settings
  - Console
- Checking the correct position of HUD objects in the game.
- Checking the pause menu during the game.
