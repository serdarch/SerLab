# SerLab

[![GitHub Repository: SERNet-Former](https://img.shields.io/badge/GitHub-SERNetFormer-yellow)](https://github.com/serdarch/SERNet-Former)
[![GitHub Repository: Efficient-ResNet](https://img.shields.io/badge/GitHub-EfficientResNet-yellow)](https://github.com/serdarch/Efficient-ResNet)
[![GitHub Repository: CNN-D3](https://img.shields.io/badge/GitHub-CNN_D3-blue)](https://github.com/serdarch/CNN-D3)
[![GitHub Repository: CNN-D3-v2](https://img.shields.io/badge/GitHub-CNN_D3_v2-blue)](https://github.com/serdarch/CNN-D3_v2)


## News
- `30 July 2024`  [CVMI 2024] The article "SERNet-Former: Segmentation by Efficient-ResNet with Attention-Boosting Gates and Attention-Fusion Networks" is accepted to The 3rd IEEE International Conference on Computer Vision and Machine Intelligence (IEEE CVMI)
- `16 May 2024`   [CVPR 2024 Workshops] The article "SERNet-Former: Semantic Segmentation by Efficient Residual Network with Attention-Boosting Gates and Attention-Fusion Networks" is now accepted to CVPR 2024 Workshops. Equivariant Vision: From Theory to Practice
[![[CVPR 2024 Workshops] YouTube Video](https://img.shields.io/badge/CVPRW'24-YouTube-red)](https://youtu.be/XXzMkotcdb4?feature=shared)
[![ArXiv paper](https://img.shields.io/badge/SERNetFormer-ArXiv-red)](https://doi.org/10.48550/arXiv.2401.15741)
- `January 2024`   SERNet-Former set state-of-the-art result on Cityscapes validation dataset for pixel-level segmentation: 87.35 % mIoU
- `January 2024`   SERNet-Former set state-of-the-art result on CamVid dataset: 84.62 % mIoU
- `January 2024`   SERNet-Former ranked as the seventh on Cityscapes test dataset for pixel-level segmentation according to PapersWithCode.com: 84.83 % mIoU


## Hall of Fame - SERNet-Former
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/sernet-former-semantic-segmentation-by/semantic-segmentation-on-camvid)](https://paperswithcode.com/sota/semantic-segmentation-on-camvid?p=sernet-former-semantic-segmentation-by)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/sernet-former-semantic-segmentation-by/2d-semantic-segmentation-on-camvid)](https://paperswithcode.com/sota/2d-semantic-segmentation-on-camvid?p=sernet-former-semantic-segmentation-by)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/sernet-former-semantic-segmentation-by/semantic-segmentation-on-cityscapes-val)](https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes-val?p=sernet-former-semantic-segmentation-by)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/sernet-former-semantic-segmentation-by/2d-semantic-segmentation-on-cityscapes-val)](https://paperswithcode.com/sota/2d-semantic-segmentation-on-cityscapes-val?p=sernet-former-semantic-segmentation-by)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/sernet-former-semantic-segmentation-by/semantic-segmentation-on-cityscapes)](https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes?p=sernet-former-semantic-segmentation-by)

## SERNet-Former Conceptual 

![Figure1](https://github.com/serdarch/SERNet-Former/assets/61043858/084416d7-f982-4f46-b1bf-871aed81557b)

(a) Attention-boosting Gate (AbG) and Attention-boosting Module (AbM) are fused into the encoder part. 

(b) Attention-fusion Network (AfN), introduced into the decoder


## Experiment Results

### CamVid Dataset 

The breakdown of class accuracies on CamVid dataset

<table><tbody>
<!-- TABLE HEADER -->
<th valign="bottom">Model</th>
<th valign="bottom">Baseline Architecture</th>  
<th valign="bottom">Building</th>
<th valign="bottom">Tree</th>
<th valign="bottom">Sky</th>
<th valign="bottom">Car</th>
<th valign="bottom">Sign</th>
<th valign="bottom">Road</th>
<th valign="bottom">Pedestrian</th>
<th valign="bottom">Fence</th>
<th valign="bottom">Pole</th>
<th valign="bottom">Sidewalk</th>
<th valign="bottom">Bicycle</th>
<th valign="bottom">mIoU</th>
<!-- TABLE BODY -->
<!-- ROW: 1 -->
<tr>
<td align="center">SERNet-Former</td>
<td align="center">Efficient-ResNet</td>
<td align="center">93.0</td>
<td align="center">88.8</td>
<td align="center">95.1</td>
<td align="center">91.9</td>
<td align="center">73.9</td>
<td align="center">97.7</td>
<td align="center">76.4</td>
<td align="center">83.4</td>
<td align="center">57.3</td>
<td align="center">90.3</td>
<td align="center">83.1</td>
<td align="center">84.62</td>
</tr>
</tbody></table>


The experiment outcomes on CamVid dataset

![camvid_output](https://github.com/serdarch/SERNet-Former/assets/61043858/f11f44a6-b245-43f1-b323-2f107f0b330e)

### Cityscapes

<table><tbody>
<!-- START TABLE -->
<!-- TABLE HEADER -->
<th valign="bottom">Model</th>
<th valign="bottom">Baseline Architecture</th>
<th valign="bottom">road</th>
<th valign="bottom">sidewalk</th>
<th valign="bottom">building</th>
<th valign="bottom">wall</th>
<th valign="bottom">fence</th>
<th valign="bottom">pole</th>
<th valign="bottom">traffic light</th>
<th valign="bottom">traffic sign</th>
<th valign="bottom">vegetation</th>
<th valign="bottom">terrain</th>
<th valign="bottom">sky</th>
<th valign="bottom">person</th>
<th valign="bottom">rider</th>
<th valign="bottom">car</th>
<th valign="bottom">truck</th>
<th valign="bottom">bus</th>
<th valign="bottom">train</th>
<th valign="bottom">motorcycle</th>
<th valign="bottom">bicycle</th>
<th valign="bottom">mIoU</th>
<!-- TABLE BODY -->
<!-- ROW: 1 -->
<tr>
<td align="center">SERNet-Former</td>
<td align="center">Efficient-ResNet</td>
<td align="center">98.2</td>
<td align="center">90.2</td>
<td align="center">94.0</td>
<td align="center">67.6</td>
<td align="center">68.2</td>
<td align="center">73.6</td>
<td align="center">78.2</td>
<td align="center">82.1</td>
<td align="center">94.6</td>
<td align="center">75.9</td>
<td align="center">96.9</td>
<td align="center">90.0</td>
<td align="center">77.7</td>
<td align="center">96.9</td>
<td align="center">86.1</td>
<td align="center">93.9</td>
<td align="center">91.7</td>
<td align="center">70.0</td>
<td align="center">82.9</td>
<td align="center">84.83</td>
</tr>
</tbody></table>

The experiment outcomes on Cityscapes dataset

![cityscapes_output](https://github.com/serdarch/SERNet-Former/assets/61043858/9a613193-6761-422c-bb7c-d2a3499548c5)
