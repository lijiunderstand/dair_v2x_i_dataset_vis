# steps

## create python env and install packages
python3.8 -m venv Env
source Env/bin/activate

pip install --upgrade pip
pip install -r requirements.txt

## dataset convert to kitti format
python convert.py

## data visualization
python dair_3D_detection_viewer.py

