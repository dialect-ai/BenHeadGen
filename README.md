# Shironaam

This is the official repository contains the code, data, and models of the paper titled [**"Shironaam: Bengali News Headline Generation using Auxiliary Information"**](https://aclanthology.org/2023.eacl-main.4/), accepted for publication in Proceedings of the 17th Conference of the European Chapter of the Association for Computational Linguistics (EACL’23), May 2-6, 2023.

## Table of Contents

- [Shironaam](#shironaam)
  - [Table of Contents](#table-of-contents)
  - [Abstract](#abstract)
  - [Dataset](#dataset)
  - [Implementation](#implementation)
  - [License](#license)
  - [Citation](#citation)
  - [Contributors](#contributors)
  - [Acknowledgement](#acknowledgement)

## Abstract
> *Automatic headline generation systems have the potential to assist editors in finding interesting headlines to attract visitors or readers. However, the performance of headline generation systems remains challenging due to the unavailability of sufficient parallel data for low-resource languages like Bengali and the lack of ideal approaches to develop a system for headline generation using pre-trained language models, especially for long news articles. To address these challenges, we present Shironaam, a large-scale dataset in Bengali containing over 240K news article-headline pairings with auxiliary data such as image captions, topic words, and category information. Unlike other headline generation models, this paper uses this auxiliary information to better model this task. Furthermore, we utilize the contextualized language models to design encoder-decoder model for Bengali news headline generation and follow a simple yet cost-effective coarse-to-fine approach using topic-words to retrieve important sentences considering the fixed length requirement of the pre-trained language models. Finally, we conduct extensive experiments on our dataset containing news articles of 13 different categories to demonstrate the effectiveness of incorporating auxiliary information and evaluate our system on a wide range of metrics. The experimental results demonstrate that our methods bring significant improvements (i.e., 3 to 10 percentage points across all evaluation metrics) over the baselines. Also to illustrate the utility and robustness, we report experimental results in few-shot and non-few-shot settings.*

## Dataset
Dataset used in this work can be found here: [full version](https://drive.google.com/u/5/uc?id=1VQ8NzfGxn1R1xLxexGmR5sHT3q0VTxyj&export=download), [training set](https://drive.google.com/u/5/uc?id=1LsxHyVtuV1ZIpFZc1nSc7jPSGvPSEE4v&export=download), [validation set](https://drive.google.com/u/5/uc?id=1-ek33XYfg2Q9sRRIlP3wcbtNFlPqA4i4&export=download), [test set](https://drive.google.com/u/5/uc?id=12m7r9q0oXu-TCDrGv20D_LD5QsRWRGpd&export=download).

## Implementation
**Code for this work will be published soon**

## License
Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). Copyright of the dataset contents belongs to the original copyright holders.

## Citation
If you find this work useful for your research, please consider citing:
```
@inproceedings{akash-etal-2023-shironaam,
    title = "Shironaam: {B}engali News Headline Generation using Auxiliary Information",
    author = "Akash, Abu Ubaida  and
      Nayeem, Mir Tafseer  and
      Shohan, Faisal Tareque  and
      Islam, Tanvir",
    booktitle = "Proceedings of the 17th Conference of the European Chapter of the Association for Computational Linguistics",
    month = may,
    year = "2023",
    address = "Dubrovnik, Croatia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.eacl-main.4",
    pages = "52--67",
}
```

## Contributors
- Abu Ubaida Akash (akash.ubaida@gmail.com)
- Mir Tafseer Nayeem (mnayeem@ualberta.ca)
- Faisal Tareque Shohan (faisaltareque@hotmail.com)
- Tanvir Islam (tislam@hawaii.edu)

## Acknowledgements
- This work is the outcome of the ongoing research at [Dialect AI Research Group](https://github.com/dialect-ai).
- Mir Tafseer Nayeem is supported by [Huawei](https://digitalpower.huawei.com/en/) Doctoral Fellowship.


