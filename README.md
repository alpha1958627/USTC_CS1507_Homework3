# USTC_CS1507_Homework3
3rd homework

## distill
Install packages as follows:

```conda install --file requirements_conda.txt```

```pip install -r requirements_pip.txt```

run this
```python
# in in1k folder:
python3 distill.py --dataset=in1k --testdir /data/linshiqi047/imagenet/val \
                   --traindir=/data/ALPHAaaa/singleimage/ameyoko_dataset32_singleameyoko_init0.5_deg30_scale500_1_shear30_randinterp_False_vflipFalse_cropfirstTrue_new_50000/train --student_arch=resnet50 --teacher_arch=resnet18 
```
PS:this traindir is private ,please generate dataset by ```make_single_img_dataset```
## visualization
use ```visualization.ipynb```to visualize

get the label of object that you want to try in ```imagenet_labels.txt``` or ```old_imagenet_labels```(for inceptionv1)