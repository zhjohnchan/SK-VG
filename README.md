# SK-VG
The official dataset of [Advancing Visual Grounding with Scene Knowledge: Benchmark and Method](https://openaccess.thecvf.com/content/CVPR2023/papers/Song_Advancing_Visual_Grounding_With_Scene_Knowledge_Benchmark_and_Method_CVPR_2023_paper.pdf).

## Introduction
We introduce a challenging task that requires VG models to reason over **(image, scene knowledge, query)** triples and build a new dataset named SK-VG on top of real images through manual annotations.
In SK-VG, the image content and referring expressions  are not sufficient to ground the target objects, forcing the models to have a reasoning ability on the long-form scene  knowledge.

![image](assets/animation.gif)

## An example
```angular2html
{
      "image_name": "3853.jpg",
      "knowledge": "The man on the far right of the image is Spider-Man Bruce. A spider is painted on his back. His enemy Brandon is floating in the air across from him, wearing sunglasses. Brandon's servant Tom is behind Brandon, holding a cane in his hand. Bruce comes to destroy them today.",
      "ref_exp": "Bruce's enemy Brandon",
      "bbox": {
        "x": 1063.1217116217117,
        "y": 385.6505161505161,
        "width": 430.26939726939736,
        "height": 705.6600066600066
      }
}
```

## Data

You can download the dataset from [Google Drive](https://drive.google.com/file/d/1XShB2JK0WDG_KDRE2obCHuAjkoCmTo4f/view?usp=sharing).

## Citation
If you find this dataset helpful, please cite the paper below.

```angular2html
@inproceedings{chen2023advancing,
        title={Advancing Visual Grounding With Scene Knowledge: Benchmark and Method},
        author={Chen, Zhihong and Zhang, Ruifei and Song, Yibing and Wan, Xiang and Li, Guanbin},
        booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
        pages={15039--15049},
        year={2023}
}
```