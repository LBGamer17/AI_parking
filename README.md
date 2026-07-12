To run on Raspberry Pi 5:

Download all the files

cd ~/AI_parking/AI_parking
source yolo-pi-env/bin/activate

python my_model/yolo_detect.py \
    --model my_model/my_model_ncnn_model \
    --source picamera0 \
    --thresh 0.35 \
    --resolution 640x480

deactivate
