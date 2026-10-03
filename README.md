# ML Gesture Training

This project contains image datasets and a pre-trained model for hand gesture recognition.

**Note:** The contents of this project are designed to be used with the [Google Teachable Machine](https://teachablemachine.withgoogle.com/) website.

## How to Use

You can use the resources in this repository in two ways on the Teachable Machine platform:

### 1. Upload the Pre-trained Model
You can use the model files located in the `tm-my-image-model/` directory (which includes `model.json`, `metadata.json`, and `weights.bin`) directly with Teachable Machine.

### 2. Train a New Model
You can use the provided image datasets to train a completely new model on the website. The images are categorized into the following gesture folders:
- `fist/`
- `open-palm/`
- `peace/`
- `point/`

To do this:
1. Go to [Teachable Machine](https://teachablemachine.withgoogle.com/).
2. Create an **Image Project**.
3. Create classes for each gesture and upload the images from the respective folders.
4. Train your new model!
