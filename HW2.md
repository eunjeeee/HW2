# Homework Assignment 2 
### Eulerian Video Magnification

<p align='right'>
  2021314078 배은지
</p>

Eulerian Video Magnification : 육안으로 볼 수 없는 미묘한 변화들을 추출하는 알고리즘

<p align='center'>
  <img src='./image/original.PNG' width="500px">
</p>

두 동영상 ( face, baby ) 에서 아래와 같은 순서로 진행
1. If your video has color, transform it to an appropriate color space.
2. Create a Laplacian pyramid for each video frame.
3. Band-pass filter the time series for each pixel, on all levels of the pyramid.
4. Magnify bands of interest by some scale.
5. Reverse the Laplacian pyramid and undo the color transform to obtain the final output.


