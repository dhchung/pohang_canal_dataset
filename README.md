# Pohang Canal Dataset

![Pohang Canal Dataset Logo](./resource/title.png)  

## About

This dataset presents a multi-modal maritime dataset acquired in restricted waters in Pohang, South Korea. The sensor suite is composed of three LiDARs (one 64-channel LiDAR and two 32-channel LiDARs), a marine radar, two visual cameras used as a stereo camera, an infrared camera, an omnidirectional camera with 6 directions, an AHRS, and a GPS with RTK. The dataset includes the sensor calibration parameters and SLAM-based baseline trajectory. It was acquired while navigating a 7.5 km route that includes a narrow canal area, inner and outer port areas, and a near-coastal area. The aim of this dataset is to facilitate research on autonomous surface 

The detailed description about the dataset is available at [here](https://sites.google.com/view/pohang-canal-dataset/home).


## Download using AWS CLI

The dataset configuration in AWS S3 is configured as following:

![AWS Data Config](./resource/data_config.png)

The bucket s3 url is as : s3://pohang-canal-dataset

### pohang0n

There are 6 scenarios (pohang00, pohang01, pohang02, pohang03, pohang04, pohang05) where pohang01 and pohang05 is acquired at night and the rest of the scenarios are acquired at daytime. Omnidirectional images are not available for the nighttime dataset (pohang01 and pohang05).

