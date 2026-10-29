# 2K Tools releases

Release packages for the 2K Tools Hub and the tools it installs: the NBA 2K27
Launcher, the NBA 2K27 Exporter and the 2K Roster Editor.

- Each tool version is a GitHub Release tagged `<tool>-v<version>`, with one
  zip of that tool's application folder and its `release.json` file list.
- `index.json` lists the current version of each tool on the `dev` and
  `stable` channels. It is signed with the publisher key; the Hub refuses any
  index or package that doesn't match that signature and the file hashes.

`index.json` is written by the Hub's release scripts. Don't edit it by hand:
an edited index fails its signature check and the Hub ignores it.
