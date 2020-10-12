# DC-Recovery-JPEG
This is the official implementation of the following [paper](https://link.springer.com/chapter/10.1007/978-3-030-34139-8_26):

> *DC Coeﬃcients Recovery from AC Coeﬃcients in the JPEG Compression Scenario*
>
> Han Qiu, Qinkai Zheng, Meikang Qiu, Gerard Memmi
>
> *Abstract*With the deployment of multimedia compression techniques, contents such as images or videos are transmitted through resource-constrained networks such as Internet of Things (IoT) scenarios. Traditional multimedia compression methods based on spatial-frequency transforms and coding techniques have been progressively improving and approaching the theoretical limit of Shannon. Therefore some new approaches are proposing to transmit only a part of the compressed data and recover the missing part at the receiver’s end. In this paper, we propose to follow this idea to highly enhance the JPEG compression by transmitting all AC coefficients and only four DC coefficients of one image. On the receiver’s end, we propose two methods to rebuild the missing DC coefficients based on the remaining DCT coefficient relationships. The first method considers the pixel relationship compared with the adjacent blocks on multiple directions. The second method considers not only the pixel relationship between adjacent blocks but also the existing relationship inside the adjacent blocks. As a result, our proposed method recovers the transmitted JPEG image with more than 25 dB considering PSNR while transmitting only 40–60% of the size of the JPEG images.

If you have any question, please raise an issue or contact ```qinkai.zheng1028@gmail.com```. 

## DEMO



## Requirements

* cv2==3.4.2
* numpy==1.15.4

## Citation

``````
@inproceedings{qiu2019dc,
  title={DC Coefficients Recovery from AC Coefficients in the JPEG Compression Scenario},
  author={Qiu, Han and Zheng, Qinkai and Qiu, Meikang and Memmi, Gerard},
  booktitle={International Conference on Smart Computing and Communication},
  pages={266--276},
  year={2019},
  organization={Springer}
}
``````

