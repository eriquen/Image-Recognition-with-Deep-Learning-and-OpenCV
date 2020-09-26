# Image Recognition with Deep Learning and OpenCV

## Dependencies
```
OpenCV
CUDA Toolkit 10.1 
CuDNN for CUDA 10.1
```

## Create Facial Embeddings 
```
python encode_faces.py --dataset dataset --encodings encodings.pickle
```

## Run
### For Picture Face Recognition
```
python recognize_faces_image.py --encodings encodings.pickle --image examples/<Image Name>
```
### Real-time Face Recognition
```
python recognize_faces_video.py --encodings encodings.pickle --output output/webcam_face_recognition_output.avi --display 1
```

## Original Article
Source: https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/
