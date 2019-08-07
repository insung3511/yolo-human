# Yolo-human
Yolo 알고리즘을 활용하여 사람이라는 객체를 찾는 알고리-즘 <br/>
~~음 해커톤에서 쓰기 위한 코드..~~ <br/>

그럼 이제 디렉토리 설명을 해볼까요?

# Directory
<pre>
.
├── README.md
├── asdf.py
├── bluetooth.py
├── images
│   ├── baggage_claim.jpg
│   ├── dining_table.jpg
│   ├── living_room.jpg
│   ├── soccer.jpg
│   └── yg.png
├── output
│   ├── airport_output.avi
│   └── asdf.jpg
├── result0.jpg
├── test.png
├── videos
│   ├── airport.mp4
│   ├── car_chase_01.mp4
│   ├── car_chase_02.mp4
│   └── overpass.mp4
├── yolo-coco
│   ├── coco.names
│   ├── yolov3.cfg
│   └── yolov3.weights
├── yolo.py
└── yolo_video.py

4 directories, 21 files
</pre>
일단 사실 이 코드의 대부분 거의 모든 것은 <a href="https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/"> 이 문서 </a> 를 수정해 가면서 했다. yolo-coco에 <b>yolov3.weights</b> 없을 수 있다. 음 이는 파일이 너무 무거워서 깃허브에서 올릴수가 없다는데.. 이는 아래 명령어를 통해서 다운 받으면 된다. 
```shell
wget https://pjreddie.com/media/files/yolov3.weights 
```
yolo-coco에는 공부한 데이터들을 넣어둔 것 인데, 이 안에 있는 파일들이 없으면 특정 객체 (Object) 를 찾을 수 없을 것이다. 그러니 매-우 중요하다..  <br/>
videos 디렉토리 안에는 yolo_video.py를 위한 테스트 영상들이 들어가 있다. 사진으로만 할꺼다 하면 필요 없을수 있다. ~~사실 나도 그렇다..ㅎ~~ 조만간 삭제할 예정이다. 정 필요 하다 하면 위에 걸어둔 문서로 확인 하길. 