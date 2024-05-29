# BethEllen
Font project repo for the Beth Ellen font by Rob Jelinski

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
