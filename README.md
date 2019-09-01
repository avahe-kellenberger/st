# st

st (simple/suckless terminal) is an application from suckless.org. This is my customized build.

## Setup

1. Clone the repository
2. `cd st`
3. `# make clean install`
4. Symlink `externalpipe.sh` to `$HOME/.config/st/externalpipe.sh`

## Notes

externalpipe.sh is currently bare, but will be an easily configurable script used to parse the current output of the terminal. All link copying/opening/etc will be moved to this script in the near future.

