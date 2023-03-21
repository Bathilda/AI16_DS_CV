# AI6_DS_CV

## 1. install
### Clone repo and install requirements.txt in a Python>=3.7.0 environment

```
git clone https://github.com/Bathilda/AI16_DS_CV.git
%cd /AI16_DS_CV/
pip install -r requirements.txt
```


## 2. Inference  
### detect.py runs inference on a variety of sources and saving results to runs/detect.  

```
python detect.py --weights best.pt --source 0                               # webcam
                                            img.jpg                         # image
                                            vid.mp4                         # video
                                            screen                          # screenshot
                                            path/                           # directory
                                            list.txt                        # list of images
                                            list.streams                    # list of streams
                                            'path/*.jpg'                    # glob
                                            'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream

```
