## Supported Software

The software below can be installed, updated and removed using `deb-get`'s main repository:

<!-- [[[cog
import subprocess
import cog

pretty_list = subprocess.check_output(["../deb-get", "prettylist", "01-main"], encoding="utf-8")
cog.out(pretty_list)
]]] -->
| Source   | Package Name   | Description   |
| :------: | :------------- | :------------ |
| [<img src="../.github/github.png" align="top" width="20" />](https://github.com/OrangeDrangon/android-messages-desktop/) | `android-messages-desktop` | <i>Run Android Messages as a desktop app.</i> |
<!-- [[[end]]] -->


**Legend**

The icons above denote how `deb-get` installs/updates the packages.

- <img src="../.github/debian.png" align="top" width="20" /> apt repository
- <img src="../.github/github.png" align="top" width="20" /> GitHub releases
- <img src="../.github/launchpad.png" align="top" width="20" /> Launchpad PPA
- <img src="../.github/direct.png" align="top" width="20" /> Website/Direct

