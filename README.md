# barcode-with-imgick
PHP scipt for generating barcode (barcod 39) with imagick 
generated image will of the follwong spec

300 dpi
32 bit dpth
CMYK/RGB
260 px width and 270 px height [both are customiizable]

usage:

require './barcodeImagick.php';
$bc = new Barcode391('string  to encode in barcode');
$bc_im = $bc->draw();

