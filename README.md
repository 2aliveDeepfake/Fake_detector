# Fake_detector_train
※ Fake detector train code ※
  
  
아래 링크에 들어가서 faster_rcnn_inception_v2_coco 다운로드 (원하는 모델)
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md  
Download =>  faster_rcnn_inception_v2_coco  

Git link of tutorial, Clone and merge with tenserflow object_detection  
https://github.com/tensorflow/models  
https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10  
=> 참고한 튜토리얼  


1. C:\\tensorflow1 폴더를 생성  
2. C:\\tensorflow1 폴더에 https://github.com/tensorflow/models => models-master zip 파일을 풀고 models-master 이름을 models로 변경  
3. TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10 => github zip 파일 다운로드, 압축 해제
  
4. C:\tensorflow1\models\research\object_detection 폴더에 3번 파일 전체 복사하고 붙여넣기  
![Alt text](/readme/img1.jpg)
  
  ============================================================================================
  수정만 하는 경우
  
새로 detector를 학습시키려면, 폴더 내 파일들 삭제 (폴더는 남겨두고):  
	• \object_detection\images\train and \object_detection\images\test 내의 모든 파일  
	• \object_detection\images 내의 “test_labels.csv” and “train_labels.csv”  
	• \object_detection\training 내의 모든 파일  
	• \object_detection\inference_graph 내의 모든 파일  
