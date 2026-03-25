# PolSAR-generation
This repository provides the code and related datasets for the paper *Azi-Vec: High-resolution Azimuth-Sensitive PolSAR Image Generation for Vehicle Automatic Target Recognition*.<br>
This project is still in progress, and the related code is currently being further organized, standardized, and refined.<br>
<br>
The related datasets can be accessed as follows:<br>
🔹 The HH-channel dataset is available on the [download page](https://www.scidb.cn/file?fid=1d2a817c2267d47a9a5eb74ce86cc79d&mode=front).<br>
The single-polarization dataset is designed for high-resolution SAR target recognition applications. Through scene setup, flight path planning, and radar data acquisition, high-resolution SAR target data from four scenes were collected. The dataset covers 21 vehicle types in 7 major categories, with backgrounds including concrete ground, grassland, and shrubs. It includes both Ku-band and X-band data, with observation angles covering 5 elevation angles and 72 azimuth angles, forming a total of 3,308 SAR target chip samples. The dataset provides both SAR amplitude images and the corresponding complex-valued data, which can support research on high-resolution SAR target recognition, target scattering characteristic analysis, and related methods.<br>
📘 Detailed dataset information is available on the [description page](https://www.sciengine.com/CSD/doi/10.11922/11-6035.csd.2025.0094.zh).<br>
🔹 The PolSAR dataset is available on the [download page](https://www.scidb.cn/detail?dataSetId=0378a4e05fdf43c4b81187e4448e369c&version=V1).<br>
The PolSAR dataset covers 21 vehicle types in 7 major categories, with three typical background types: concrete ground, grassland, and shrubs. It includes both Ku-band and X-band data, 5 elevation angles, and up to 72 azimuth angles, providing a total of 3,308 Pauli-RGB images and the corresponding polarimetric scattering matrix data. This dataset can provide high-quality support for research on vehicle target polarimetric scattering characteristic analysis, fine-grained recognition, few-shot learning, and domain adaptation, and can further facilitate the reliable application of PolSAR target recognition technology.<br>

If you use the above two datasets, please cite:<br>

```bibtex
@article{Wang2025HRSARVehicleDataset,
  author  = {Wei Wang and Huiqiang Zhang and Hongqi Fan and Zhongjie Wu and Bingwei Hui and Tianpeng Liu and Shujie Wu and Deliang Xiang and Chaofu Wei and Yingbing Ma},
  title   = {A dataset of high-resolution SAR vehicle target recognition},
  journal = {China Scientific Data},
  year    = {2025},
  doi     = {10.11922/11-6035.csd.2025.0094.zh},
  url     = {https://www.sciengine.com/CSD/doi/10.11922/11-6035.csd.2025.0094.zh}
}

@misc{ 0378a4e05fdf43c4b81187e4448e369c,
  author       = {Wang Wei and Deng Jie and Fan Hongqi and Wu Zhongjie and Quan Sinong and Hui Bingwei and Liu Tianpen and Wu Shujie and Xiang Deliang and Wei Chaofu},
  title        = {{High-resolution Airborne PolSAR vehicle target recognition dataset}},
  year         = 2025,
  month        = nov,
  publisher    = {Science Data Bank},
  version      = {V1},
  doi          = {10.57760/sciencedb.j00001.01627},
  url          = https://doi.org/10.57760/sciencedb.j00001.01627
}
