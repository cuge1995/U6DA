# U6DA
official Pytorch implementation of paper '[Adversarial samples for deep monocular 6D object pose estimation](https://arxiv.org/abs/2203.00302)'


## U6DA-Linemod
The dataset can be download from [Google Drive](https://drive.google.com/file/d/1jmELumR2CuIXv1urLykoHoFtiMdg9xWx/view?usp=sharing) and [Baidu Pan](https://pan.baidu.com/s/12VREdD1BqFRTUtE-laomJg) (code: jcfm)

After download and unzip, back up the original data first, then:
```
cp ape/* lm/test/000001/rgb/
cp benchvise/* lm/test/000002/rgb/
cp cam/* lm/test/000004/rgb/
cp can/* lm/test/000005/rgb/
cp cat/* lm/test/000006/rgb/
cp driller/* lm/test/000008/rgb/
cp duck/* lm/test/000009/rgb/
cp eggbox/* lm/test/000010/rgb/
cp glue/* lm/test/000011/rgb/
cp holepuncher/* lm/test/000012/rgb/
cp iron/* lm/test/000013/rgb/
cp lamp/* lm/test/000014/rgb/
cp phone/* lm/test/000015/rgb/
```

* Our codes coming soon!

## Citation
if you find our work useful in your research, please consider citing:
```
@article{zhang2022adversarial,
  title={Adversarial samples for deep monocular 6D object pose estimation},
  author={Zhang, Jinlai and Li, Weiming and Liang, Shuang and Wang, Hao and Zhu, Jihong},
  journal={arXiv preprint arXiv:2203.00302},
  year={2022}
}
```
