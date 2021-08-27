# README

项目文档，主要包括CV检测的几个常用框架

- YOLOv5_source：YOLOv5主体文件，该上传文本可直接执行LableImg，XML文件转换，CV采集等功能（需要预先安装setup.ipynb中的宏包）
- Deepsort：YOLOv5+Deepsort，可按照`master`文件下的`setup.ipynb`执行
- Paddle：百度开源的深度学习框架，支持很多的深度学习网络以及项目方案，而且都有比较好的中文文档支持
- Yolov5+Deepsort+plot_line：在原有Deepsort项目中加入的画线功能，可实现cv识别计数

```bash
# 查询大于1M的文件，方面上传
find ./ -type f -size +1M

./.git/objects/eb/69077f6ba1676d9fc0ba3e4cada645c5ab7245
./.git/objects/eb/c1ac4840f8d5b9225130fe1d20b4fb8a1a3132
./.git/objects/a4/b6fe0178c891c3840e2b647e26d5b9010da741
./.git/objects/15/5d5128422d7e02499554e42c02f33514803a41
./.git/objects/2b/5a3b83e4abbc316768faac5fc9b16b94f52b20
./.git/objects/d6/2b8eeb3870e20e0067864ac00b4b1ba23acf7c
./.git/objects/bf/47c97d6002f92fc0c46af0862babc53967e7bf
./.git/objects/69/f28b73b02da6b4aa3d0dfb1567a30893d59d0e
./.git/objects/d9/9fb1fd198f1f8b6e003741375e9aa5524f117a
./.git/objects/aa/23ae1f1ee21f3de41f88ac535ca168305ae08e
./.git/objects/aa/f9c59bc18f09a342b13e88d966c590b7c16024
./.git/objects/bb/69b57b7efabc86a48527a11a4602eaaf83ca00
./.git/objects/bb/tmp_obj_amVXbs
./.git/objects/bb/8588ae652d94592866a90a1aa359e9d7ad16b4
./.git/objects/38/04187bd7b64973d7c0b937ed1bb0c502abb343
./.git/objects/81/1a9c2280d54e4d1953a24448653d16c4544747
./.git/objects/28/7bd571e12277f6bf11e90150bb20b738cadc6d
./.git/objects/d2/53aae653c8b9d31d924a47dca3e5ebabc52df6
./.git/objects/e2/8fadae95a4eb113ae11d0018609896c2101c20
./.git/objects/78/b6e6f9f67e742cad73fdc2211677e4e0cff7f5
./.git/objects/f1/0b3b2dbb26355697020015218bd84c1fad1a64
./.git/objects/e9/e3fbd6b046f7ed60808ae6396f58a4006c4414
./.git/objects/08/499a1842a6e8b386477c01f8be6787d6aa49bc
./.git/objects/b9/9a7abf052d34be6ccf672467d0d77b36d2b4f9
./.git/objects/19/4ee1c935335a45589845e0595ec094fcb39094
./.git/objects/7f/a825ee6c746c62766075f55486b23c60ab4d76
./.git/objects/41/b26caf11e65ae88b2838112a47d0de48e89d8c
./.git/objects/1c/4c9df6e15caf71f77f6d971b07466a1fc11610
./.git/objects/f8/d7a8e028db12cd07ccd6af2cbb364c9b904e49
./.git/objects/fe/eaddd45122a5c07f589654492bf1c8bbd3f67e
./.git/objects/bc/5efcdcb400dd7c835d168d4f11a273207c8761
./.git/objects/0a/13498621542f3d33043463e298d24a6d3b1827
./.git/objects/de/b438cf676c1bfbbe0f6c256d06526705bc2b24
./.git/objects/47/ab7ae3b4698c18a70513e262274f2bfeb98622
./.git/objects/d4/4bb120251c2ba008f2f847868070e377cafa1d
./Paddle/PPD/configs/keypoint/football_keypoint.gif
./Paddle/PPD/models/pedestrian_yolov3_darknet/model.pdiparams
./Paddle/PPD/models/pedestrian_yolov3_darknet/model.pdmodel
./Paddle/PPD/models/pedestrian/pedestrian_yolov3_darknet.pdparams
./Paddle/PPD/docs/images/mot16_jde.gif
./Paddle/PPD/docs/images/mot_pose_demo_640x360.gif
./Paddle/PPD/static/docs/images/obj365_gt.png
./Paddle/PPD/static/docs/images/obj365_pred.png
./Paddle/PPD/static/docs/images/oidv5_gt.png
./Paddle/PPD/static/docs/images/football.gif
./Paddle/PPD/static/demo/mask_rcnn_demo.ipynb
./Paddle/PPD/demo/P0861__1.0__1154___824.png
./Paddle/PPD/demo/P0072__1.0__0___0.png
./Paddle/detections/dam2.mp4
./Paddle/detections/dam1.mp4
./Paddle/results/dam2.mp4
./Paddle/results/dam1.mp4
./Yolov5+Deepsort+plot_line/deep_sort/deep_sort/deep/checkpoint/ckpt.t7
./Yolov5+Deepsort+plot_line/video/vehicle1.mp4
./Yolov5+Deepsort+plot_line/video/vehicle.mp4
./Yolov5+Deepsort+plot_line/video/test.mp4
./Yolov5+Deepsort+plot_line/video/vehicle2.mp4
./Yolov5+Deepsort+plot_line/weights/yolov5m.pt
./Yolov5+Deepsort+plot_line/result/result.mp4
./YOLOv5_source/yolov5/models/yolov5s.pt
./YOLOv5_source/yolov5/wryh.ttf
./YOLOv5_source/yolov5/weights/yolov5m.pt
./YOLOv5_source/yolov5/weights/yolov5s6.pt
./YOLOv5_source/yolov5/weights/yolov5m6.pt
./YOLOv5_source/yolov5/weights/yolov5x.pt
./YOLOv5_source/yolov5/weights/yolov5x6.pt
./YOLOv5_source/yolov5/weights/yolov5l.pt
./YOLOv5_source/yolov5/weights/yolov5l6.pt
./YOLOv5_source/yolov5/weights/YOLOv5m6-Argoverse.pt
./YOLOv5_source/yolov5/weights/yolov5s.pt
./Deepsort/wryh.ttf
./Deepsort/inference/output/vehicle.mp4
./Deepsort/MOT16_eval/track_all.gif
./Deepsort/MOT16_eval/track_pedestrians.gif
./Deepsort/deep_sort_pytorch/deep_sort/deep/checkpoint/ckpt.t7
./Deepsort/deep_sort_pytorch/deep_sort/deep/checkpoint/original_ckpt.t7
```

