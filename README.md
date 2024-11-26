# ESRN RRBG CONVERTER

## Preface

<p align="justify">While I was working on the upscaling method for images
using ESRGAN models, the question arose as to how I could utilise all available
ESRGAN models with the approach I am working with.</p>

<p align="justify">If you use ESRGAN models from external sources, you will
receive RRBD error messages that indicate a formatting problem.</p>

<p align="justify">A basic converter can be found in the ESRGAN sources. I have
adapted this for my purposes.</p>

<p align="justify">Now upscaler from AUTOMATIC1111 as well as other resources 
available to me.</p>

## How to Use the Converter

You need following two files from the scripts folder.

```
RRDBNet_arch.py
```

```
converter_RRDB_models.py
```

<p align="justify"><code>converter_RRDB_models.py</code> is the converter and <code>RRDBNet_arch.py</code> contains the classes
which are required to run the converter. The latter file is imported from the converter.</p>

Run the converter as follows:

```
python3 converter_RRDB_models.py 4x_Superscale-SP8000G.pth
```

<p align="justify"></p>

## Reference

[1] https://github.com/xinntao/ESRGAN

[2] https://github.com/xinntao/Real-ESRGAN

[3] https://huggingface.co/

[4] https://openmodeldb.info/

