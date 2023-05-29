# abc2xml
The script is taken from https://wim.vree.org/svgParse/abc2xml.html and the only purpose of this repository is to have quick access to the script with the steps required to use it easily for importing ABC files into Musescore.
For the full documentation, please go to https://wim.vree.org/svgParse/abc2xml.html .

The ```test.abc``` file is taken from https://thesession.org/tunes/60

In order to use the script, follow the steps:

## Verify python version

This script requires Python 2.7, so check the version with:

```bash
which python
```

You should see the following output:

```bash
/Library/Frameworks/Python.framework/Versions/2.7/bin/python
```

## Create virtualenv

```bash
source myenv/bin/activate
```

## Activate virtualenv

```bash
source myenv/bin/activate
```

## Run the script

```python
python abc2xml.py test.abc > output.xml
```

The script will override the ``output.xml``` file.

## Deactivate virtualenv

Once finished, we can deactivate the virtualenv with the command:

```bash
deactivate
```
