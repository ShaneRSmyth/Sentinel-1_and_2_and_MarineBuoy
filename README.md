# Sentinel-1_and_2_and_MarineBuoy

## Sentinel-1, Sentinel-2, Marine Buoy Datasets and Links

The dataset, available via the Google Drive link below, comprises two Sentinel-1 SAR TIF files, one Sentinel-2 NDWI TIF file, and one buoy data CSV. 

- 'SAR_Image_1' features a VV polarization band.
- 'SAR_Image_3' includes VV and VH polarization bands. 
- 'ndwi_image' consists of a Near infrared (NIR) and green band.

The remote sensing data from the Sentinel satellite was retrieved using the Google Earth Engine API in Python. The code for downloading the data manually is provided in the 'Initial_Testing' Google Colab file within this repository. All code and datasets are open-source.

### Dataset and Resources

- [Link to dataset on Google Drive](https://drive.google.com/drive/folders/1asqryUKy602B5n6aBy_l3EOv99AYPGOu?usp=sharing)
- [Google Earth Engine](https://earthengine.google.com/)
- [Marine Buoy Data Website](https://www.marine.ie/)
- [Sentinel-1 Satellite Website](https://sentinel.esa.int/web/sentinel/missions/sentinel-1)
- [Sentinel-2 Satellite Website](https://sentinel.esa.int/web/sentinel/missions/sentinel-2)

### Notes on the Data

The data was obtained and is presented in the original format, with detailed descriptions as follows:

- **SAR_Image_1.tif**: Contains synthetic aperture radar (SAR) data with VV polarization. Suitable for various analyses including surface roughness and change detection.
- **SAR_Image_3.tif**: Contains SAR data with VV and VH polarization, providing additional capabilities for distinguishing different types of land cover and use.
- **ndwi_image.tif**: Features the Normalized Difference Water Index (NDWI) using NIR and green bands, helpful in delineating water bodies.

### Contribution

This project is open-source and contributions are welcome.
