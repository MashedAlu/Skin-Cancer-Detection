# Skin-Cancer-Detection
Prediction and detection of Skin Cancer types using Vision Transformers and VGG-16

The models used are:
VGG-16 : CNN using 16 layers of 2x2 Convolutional filters. Lightweight but powerful
Swin Transformer : Lightweight transformer using Self-Attention Windows.
Vision Transformer : 

## Dataset
The dataset was a modified version of HAM10000 Dataset, with 10,017 images of lesions
There were 7 classes:
Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions:

Actinic keratoses and intraepithelial carcinoma / Bowen's disease ( **AKIEC** ),
basal cell carcinoma ( **BCC** ),
benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, **BKL** ),
dermatofibroma ( **DF** ),
melanoma ( **MEL** ),
melanocytic nevi ( **NV** )
vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, **VASC** )

## Model Parameters
Swin Transformer - 147K
Vision Transformer - 1.1M
VGG-16 - 14.7M
