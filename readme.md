# Kroki Encoder Decoder

This HTML file contains a JavaScript-based Kroki Encoder/Decoder. It allows users to encode and decode Kroki URLs back into code. The code runs entirely in the browser, with no backend required. 

The file contains two functions: 
- decode(): Decodes a Kroki URL and displays the result in the "resultshowarea" div.
- encode(): Encodes a string to Kroki URL format and displays the result in the "resultshowarea" div.

The file also contains three helper functions:
- encodeToKroki(): Encodes a string to Kroki URL format.
- utf8_encode(): Encodes a string to UTF8 Unit8Array.
- decodeFromKroki(): Decodes a string from Kroki URL format.

To use the Kroki Encoder/Decoder, simply enter the code to encode or decode as a Kroki URL in the "inputtext" textarea and click the "Encode" or "Decode" button. The result will be displayed in the "resultshowarea" div.

Please note that this snippet may not function properly. For encoding and working with Kroki, we recommend using https://kroki.io/.