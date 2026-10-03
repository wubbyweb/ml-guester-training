Open Palm — hand sign training images
207 JPEG photographs, 100x100 RGB.
  train/       176 images fed to the network
  validation/  31 images held out and never trained on

Source: Sign Language Digits Dataset by Arda Mavi and students of the Ankara
Turkish Sign Language school. https://github.com/ardamavi/Sign-Language-Digits-Dataset
Licence: CC-BY-SA 4.0. This folder is the dataset's handshape "5", renamed
"Open Palm" for what it looks like.

The model resized each image to 64x64 and scaled pixels to 0-1. Training
applied random horizontal flip, rotation +/-15 deg, zoom +/-18%, translation
+/-12%, contrast +/-25% and brightness +/-18%. The split was stratified at 85/15
with seed 1337; manifest.csv records which file landed where.
