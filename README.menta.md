# pkg-polo-tweaks (Menta Linux)

Debian packaging of Polo Tweaks (https://github.com/KeremSoke/polo-tweaks), the settings
program for the Polo compositor. Built from git snapshot 77d677d (no release at HEAD;
tag v1.0.0 is older). Runtime Depends: polo (its GSettings schemas must be installed).

Version: `0.1.0+git<date>.<hash>-1mentaN`. CI clones the exact commit from the version
string and builds the orig tarball with git archive; pushes to master publish a rolling
`latest` release.
