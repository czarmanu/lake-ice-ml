# Multi-Sensor Lake Ice Monitoring with Machine (Deep) Learning


This is a consolidated repository outlining our research works on lake ice monitoring using machine (deep) learning approaches. These works are part of the two projects ([LIP1](https://prs.igp.ethz.ch/research/completed_projects/integrated-monitoring-of-ice-in-selected-swiss-lakes.html), [LIP2](https://prs.igp.ethz.ch/research/current_projects/integrated-lake-ice-monitoring-and-generation-of-sustainable--re.html)) funded by [MeteoSwiss](https://www.meteoswiss.admin.ch/) under the [GCOS Switzerland](https://www.meteoswiss.admin.ch/home/research-and-cooperation/international-cooperation/gcos.html) framework.

## Contents

[1. Ice Monitoring in Swiss Lakes from Optical Satellites and Webcams Using Machine Learning](#rs_mdpi_2020)

## Lake Ice Detection from Sentinel-1 SAR with Deep Learning 

<img src="figures/title_figure_isprs2020_sar_paper.jpg" alt="drawing" width="500"/>

This work was presented at the [ISPRS Congress 2020](http://www.isprs2020-nice.com/index.php/virtualevent-2/).  Access the paper [here](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-3-2020/409/2020/).

We use the Sentinel-1 Synthetic Aperture Radar data downloaded from the [Google Earth Engine](https://developers.google.com/earth-engine/guides/sentinel1) platform to detect lake ice with the state-of-the-art semantic segmentation network Deeplab v3+. Here, we model lake ice detection as a 2-class (frozen, non-frozen) classification problem. 
Access the tensorflow-based repository [here](https://github.com/czarmanu/sentinel_lakeice) to browse the CNN code, pre-trained model etc.

Please cite the following paper if you use this project in your research:

> @article{tom_aguilar_2020:isprs,<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;author    = {Manu Tom and Roberto Aguilar and Pascal Imhof and Silvan Leinss and Emmanuel Baltsavias and Konrad Schindler},<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;title     = {Lake Ice Detection from Sentinel-1 SAR with Deep Learning},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;journal   = {ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci.},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year      = {2020},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;volume    = {V-3-2020},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pages     = {409--416},<br>
}
[link text](#abcde)


<a name="rs_mdpi_2020">
## Ice Monitoring in Swiss Lakes from Optical Satellites and Webcams Using Machine Learning
</a>

<img src="figures/graphical_abstract_rs2020_paper.png" alt="drawing" width="500"/>

This work was published at the [MDPI Remote Sensing](https://www.mdpi.com/journal/remotesensing) journal. Access the paper [here](https://www.mdpi.com/2072-4292/12/21/3555).

We detect lake ice in MODIS and VIIRS optical satellite images using support vector machines aided by an automatic feature seclection by XGBoost. Here, we cast lake ice detection as a 2-class (frozen, non-frozen) classification problem. Additionally, we use the freely available (online) webcam data to monitor lake ice using Deep-U-Lab network. Access the tensorflow-based repository [here](https://github.com/czarmanu/deeplab-lakeice-webcams) to browse the Deep-U-Lab code, pre-trained model etc.

Kindly cite the following paper, if you use this project in your research:

> @article{tom_prabha_2020:isprs,<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;author    = {Manu Tom and Rajanie Prabha and Tianyu Wu and Emmanuel Baltsavias and Laura Leal-Taixe and Konrad Schindler},<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;title     = {Ice Monitoring in Swiss Lakes from Optical Satellites and Webcams Using Machine Learning},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;journal   = {Remote Sens.},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year      = {2020},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;volume    = {12},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;issue     = {21},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pages     = {3555},<br>
}
    
## Photi-LakeIce Dataset

<img src="figures/photi-lake-ice_dataset.png" alt="drawing" width="500"/>

The dataset and pre-trained model (Deep-U-Lab) can be found [here](https://github.com/czarmanu/photi-lakeice-dataset).

Kindly cite the following paper, if you use this dataset in your research:

> @article{tom_prabha_2020:isprs,<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;author    = {Manu Tom and Rajanie Prabha and Tianyu Wu and Emmanuel Baltsavias and Laura Leal-Taixe and Konrad Schindler},<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;title    = {Ice Monitoring in Swiss Lakes from Optical Satellites and Webcams Using Machine Learning},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;journal   = {Remote Sens.},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year      = {2020},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;volume    = {12},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;issue     = {21},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pages     = {3555},<br>
}

## Lake Ice Detection in Crowd-sourced images using Deep-U-Lab

<img src="figures/crowd-sourced_isprs2020_webcam_paper.png" alt="drawing" width="500"/>

More details [here](https://github.com/czarmanu/deeplab-lakeice-webcams).

Kindly cite the following paper, if you use this research in your work:

> @article{prabha_tom_2020:isprs,<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;author    = {Rajanie Prabha and Manu Tom and Mathias Rothermel and Emmanuel Baltsavias and Laura Leal-Taixe and Konrad Schindler},<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;title    = {Lake Ice Monitoring with Webcams and Crowd-Sourced Images},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;journal   = {ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci.},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year      = {2020},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;volume    = {V-2-2020},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pages     = {549--556},<br>
}

## Lake Ice Monitoring with Webcams using Tiramisu Network

<img src="figures/webcams_tiramisu_isprs2018.png" alt="drawing" width="500"/>

More details [here](https://github.com/czarmanu/tiramisu_keras).

Please cite the following paper, if you use this project in your research:

> @article{xiao_rothermel_2018:isprs,<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;author    = {Muyan Xiao and Mathias Rothermel and Manu Tom and Silvano Galliani and Emmanuel Baltsavias and Konrad Schindler},<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;title    = {Lake Ice Monitoring with Webcams},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;journal   = {ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci.},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year      = {2018},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;volume    = {IV-2},<br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pages     = {311--317},<br>
}

## Automatic Lake Detection using Deep-U-Lab

<img src="figures/lake_detection_rs2020.png" alt="drawing" width="500"/>

Details coming soon ...

## Other related publications

>1. Tom et al. 2020: [Integrated monitoring of ice
in selected Swiss lakes](https://arxiv.org/abs/2008.00512). Final Project Report, 2020

>2. Tom et al. 2018: [Lake ice detection in low-resolution optical satellite images](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/IV-2/279/2018/). 

>3. Rothermel et al. 2018: [Monitoring der vereisung von Schweizer seen mit webcams](https://ethz.ch/content/dam/ethz/special-interest/baug/igp/photogrammetry-remote-sensing-dam/documents/pdf/Papers/Webcams_Geomatik_9-2018.pdf)

>4. Tom et al. 2017: [Ice detection in Swiss lakes using MODIS data](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/236400/1/Tom_ETHZ_ACRS17.pdf)


## Licence

MIT License

Copyright (c) 2020 ETH Zurich

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Author: Manu Tom
