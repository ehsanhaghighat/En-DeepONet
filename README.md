# Enriched DeepONet 
An enrichment approach for enhancing the expressivity of neural operators with applications to seismology

## Abstract:
The Eikonal equation plays a central role in seismic wave propagation and hypocenter localization, a crucial aspect of efficient earthquake early warning systems. Despite recent progress, real-time earthquake localization remains challenging due to the need to learn a generalizable Eikonal operator. We introduce a novel deep learning architecture, Enriched-DeepONet (En-DeepONet), addressing the limitations of current operator learning models in dealing with moving-solution operators. Leveraging addition and subtraction operations and a novel `root' network, En-DeepONet is particularly suitable for learning such operators and achieves up to four orders of magnitude improved accuracy without increased training cost. We demonstrate the effectiveness of En-DeepONet in earthquake localization under variable velocity and arrival time conditions. Our results indicate that En-DeepONet paves the way for real-time hypocenter localization for velocity models of practical interest. 
The proposed method represents a significant advancement in operator learning that is applicable to a gamut of scientific problems, including those in seismology, fracture mechanics, and phase-field problems.

![Results](predictions.gif)

```bibtex
@article{haghighat2023novel,
  title={An enrichment approach for enhancing the expressivity of neural operators with applications to seismology},
  author={Haghighat, Ehsan and Waheed, Umair bin and Karniadakis, George},
  journal={arXiv preprint arXiv:2306.04096},
  url={https://arxiv.org/abs/2306.04096},
  year={2023}
}
```

Data and code related to this work will be shared here.

## Requirements
Tested on `python>=3.8` and `python<=3.10`. Install the requirements using the following command:
```bash
pip install -r requirements.txt
```
