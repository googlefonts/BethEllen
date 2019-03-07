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
