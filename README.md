# Tensorflow.js 스터디

- [예제 코드](https://github.com/jungin500/tensorflowjs-study/blob/master/sketch.js) 실행 → YOLO 모델이 평균 14fps 정도로 구동
  - WebGL 구동 기준
  - GPU: GTX 1080 Ti (Driver 455.41)
  - OS: Windows 10 Edu. Insider Preview Build 20175.1000
  - Browser: Micorosoft Edge 84.0.522.44 64-bit)
  - Issues: 브라우저가 Tensorflow.js OOM으로 자주 죽음 (maybe ML5.js의 문제?)
  
- 아직은 GPU Native Support 또는 Browser 전용 lightweight Model 최적화까지 가지 않을 경우 사용 어려울수도?  
  (추가적으로 많이 테스트해보지는 못함)
