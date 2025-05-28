# Skin-Cancer-Detection
Prediction and detection of Skin Cancer types using Vision Transformers and VGG-16

The models used are:
- VGG-16 : CNN using 16 layers of 2x2 Convolutional filters. Lightweight but powerful
- Swin Transformer : Lightweight transformer using Self-Attention Windows.
- Vision Transformer : Basic Vision Transformer with GRAD-Cam for explainability

All data was preprocessed and augmented to simulate real, worst-case scenarios

## Dataset
The dataset was a modified version of HAM10000 Dataset, with 10,017 images of lesions
There were 7 classes:
Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions:

1. Actinic keratoses and intraepithelial carcinoma / Bowen's disease ( **AKIEC** )
2. basal cell carcinoma ( **BCC** )
3. benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, **BKL** )
4. dermatofibroma ( **DF** )
5. melanoma ( **MEL** ),
6. melanocytic nevi ( **NV** )
7. vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, **VASC** )


## Model Parameters
- Swin Transformer - 147K
- Vision Transformer - 1.1M
- VGG-16 - 14.7M




