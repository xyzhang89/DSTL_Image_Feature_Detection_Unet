# DSTL_Image_Feature_Detection_Unet

The proliferation of satellite imagery has given us a radically improved understanding of our planet. It has enabled us to better achieve everything from mobilizing resources during disasters to monitoring effects of global warming.

The goal of [this competition](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection) is to detect and classify 10 types of objects in the given regions(1km*1km) of satellite imagery provided by [the Defence Science and Technology Laboratory (Dstl)](https://www.gov.uk/government/organisations/defence-science-and-technology-laboratory). The dataset consists of 450 images, 25 of them have training labels. The satellite images are provided in both 3-band and 16-band formats. The 16-band format includes 
Panchromatic (450-800 nm), 8 Multispectral (red, red edge, coastal, blue, green, yellow, near-IR1 and near-IR2)(400 nm - 1040 nm) and 8 SWIR (1195 nm - 2365 nm). In this competition, information of all 20 bands are utilized in training the model.

The idea of U-net is applied in this competition for training the CNN for feature detection of satellite imagery. U-net was first developped by a German research team from University of Freiburg for Biomedical Image Segmentation. U-net then shows its perfomance for image segmention problem in the Kaggle competition [Ultrasound Nerve Segmentation](https://www.kaggle.com/c/ultrasound-nerve-segmentation). In this competition, I trained different CNNs based on the idea of U-net and got good results.

The input data can be downloaded from [here](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection/data).
