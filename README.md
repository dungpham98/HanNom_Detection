Code from [here] (https://github.com/MhLiao/DB).
```
pip install -r requirement.txt
cd \assets\ops\dcn 
python setup.py build_ext --inplace
cd ..
cd ..
cd ..
python app.py
```
Open a web browser, go to `http://localhost:5000`
Upload `/test/LienPhai-2484.jpg` and wait...

Only want to run a sample?
```
ython demo.py experiments/seg_detector/td500_resnet18_deform_thre.yaml --image_path [IMAGE_PATH] --resume weights/final --box_thresh 0.6 --visualize

```
Finally watch your results in demo_result folder
