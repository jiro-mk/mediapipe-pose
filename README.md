# mediapipe-pose

MediaPipeで姿勢推定を実行します。

ウェブカメラを使用したリアルタイムの実行と、画像ファイルを読み込んでの実行の2種類です。

リアルタイム処理では取得したランドマークを画像上にプロットして表示します。

静止画の処理では3次元のプロットを表示します。


# DEMO

静止画を用いた姿勢推定結果

![image](https://user-images.githubusercontent.com/93971055/155551785-a3e5e396-b629-4d05-902c-a0b31d0592df.png)


![image](https://user-images.githubusercontent.com/93971055/155551886-d6efec69-b342-482b-8111-0cee91959efe.png)



# Requirement

mediapipe                    0.8.9.1

opencv-python                4.5.5.62   

Tensorflow                   2.3.0 or Later

tf-nightly                   2.5.0.dev or later 



# Usage


```bash
git clone https://github.com/jiro-mk/Mediapipe_3ddraw.git
cd mediapipe-pose
python pose_webcam.py

python pose_image.py
```


# Note
MediaPipeの姿勢推定で取得できるランドマークは以下のようになります。

![image](https://user-images.githubusercontent.com/93971055/155552406-0f7173f1-f700-46a4-8864-e0e0e5b487ad.png)

# Author

jiro-mk
