# Beth Ellen

The sources in `sources/` were converted from this repository's FontForge
`.sfd` sources using [babelfont-rs](https://github.com/simoncozens/babelfont-rs),
and build with [gftools-builder](https://github.com/simoncozens/gftools-rust)
and fontc. Every change made to the `.sfd` before converting it is its own
commit in this repository's history.

The original FontForge sources remain in the git history.

How these sources were checked against the released fonts (the tools, this family's plan and the logs): https://github.com/felipesanches/gf-source-modernization.

## Original README

# BethEllen
Font project repo for the Beth Ellen font by Rod Jelinski

# Build instructions

The commands below should install TTX and use it to generate the truetype binary:

```bash
virtualenv venv3 -ppython3
. venv3/bin/activate
pip install fontTools
ttx BethEllen-Regular.ttx
```

# Font project source files

This font was originally created on Adobe Illustrator, using a plugin called Fontself. The original file is located for reference in this repo at old/BethFont.ai but the more recent work on the font has been done using fontTool's ttx and FontForge. The latest changes are always made to the TTX and SFD files.
