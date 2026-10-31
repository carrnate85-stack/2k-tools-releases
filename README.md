# 2K Hub releases

**Download 2K Hub:** open the [Latest release](https://github.com/carrnate85-stack/2k-tools-releases/releases/latest),
download `launcher-<version>-win-x64.zip`, extract it, and run
`2k-launcher-hub.exe`. Choose **Install 2K Hub** on its Play page. It installs
to `%LOCALAPPDATA%\2K Tools`, adds Start menu and desktop shortcuts, and keeps
itself up to date.

2K Hub is the NBA 2K27 launcher: play with your mods, manage profiles,
cameras, Jukebox and more. From its Play page it also installs, updates and
opens the NBA 2K27 Exporter and the 2K Roster Editor.

Already using the portable NBA 2K27 launcher? Extract 2K Hub into that
launcher's folder, next to its `Data` and `Library`, before choosing
**Install 2K Hub**, and your settings and library come along.

## How releases work

- Each version is a GitHub Release tagged `<tool>-v<version>` (`launcher`
  is 2K Hub), with one zip of the application folder and its `release.json`
  file list.
- `index.json` lists the current version of each tool on the `dev` and
  `stable` channels. It is signed with the publisher key; 2K Hub refuses any
  index or package that doesn't match that signature and the file hashes.

`index.json` is written by the release scripts. Don't edit it by hand: an
edited index fails its signature check and 2K Hub ignores it.
