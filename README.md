Panostream - Video stream panorama
==================================

To iterate quickly in development, launch Chrome with the following flags:

<code>
--allow-file-access-from-files
--use-fake-ui-for-media-stream
</code>

Then open the panostream.html file using a file:// URL.

Example for Canary on Mac:

<code>
/Applications/Google\ Chrome\ Canary.app/Contents/MacOS/Google\ Chrome\ Canary --allow-file-access-from-files --use-fake-ui-for-media-stream
<code>

For quick development, panostream.html can be accessed on this URL:

<code>
http://htmlpreview.github.io/?https://github.com/Miguelao/panostream/blob/master/panostream.html
</code>

### How to compile and run the PNaCl module

Make sure you have NaCl SDK [1] installed in your (Linux/Mac) machine. Export
its root `export NACL_SDK_ROOT=/path/to/naclsdk/pepper_33`, then from the
panostream folder run `make` and then `make serve` (python needed). The served
page can be accessed locally in http://localhost:5103/panostream.html.



[1]: https://developers.google.com/native-client/sdk/download
