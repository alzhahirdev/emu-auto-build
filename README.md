# GitHub Actions build for an Emulator

This repository contains the workflow to build a particular open source emulator. As of 19 March 2024, the emulator's repository is hosted on GitHub and GitLab. This repository is not associated with the developers of said emulator in any way whatsoever. This repository is intended for educational purposes only, and all relevant credits are available below.

> [!warning]
> Do not run other people's code on your computer, unless you are sure and fully trust them.\
> You might lose your data if you are not careful with running untrusted code on your computer.

## Usage/Installing/Downloading

You should be able to find the binaries on the releases page. There's no installer, just a zip file containing the binaries that you can directly run.

## Updating the build

Just create an issue or fork this repository.

## Credits
A major part of the workflow code for the x64 build is based on the template by [threeal/cmake-action](https://github.com/threeal/cmake-action). Please forward your thanks and sponsors to them.
In addition, I had also used [softprops/action-gh-release](https://github.com/softprops/action-gh-release) for deploying the binaries to GitHub releases.
Finally, I also used [TheDoctor0/zip-release](https://github.com/TheDoctor0/zip-release) to zip the build folder for deployment.

These people deserve the kudos for figuring things out, more than I will ever do for this repository.
