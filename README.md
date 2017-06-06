# MHT Extract
A simple utility for extracting images from MHT web archives.

## Example Usage

**mhte.extractEncodedFiles(mhtPath, [options])**

```
let mhte = require('./mht-extract');

let mhtPath = __dirname + "/SomeFile.mht";
let options = { outputPath: "images" };

mhte.extractEncodedFiles(mhtPath, options);
```

NB: Export will fail if the given output folder does not exist.
