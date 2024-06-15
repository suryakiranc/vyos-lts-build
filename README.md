# vyos-lts-build

This repository is dedicated to compiling VyOS 1.4+ LTS images. When using it, you’ll need to fork it to your own account.

And for the usage instructions:

Modify the .github/workflow/build-lts.yaml file, specifically line 23 where RELEASE_VERSION=1.4.0-epa1 is set. After making the necessary changes and saving the file, add a git tag. When you push the tag, the compilation process will automatically start, and the release will be published.
