# Kvasir-SEG: A Segmented Polyp Dataset
Colorectal polyp segmentation is a demanding task in medical image segmentation. Research in polyp segmentation using computer vision techniques can improve examination procedures and reduce the polyp miss rate during colonoscopy. However, finding the publicly available dataset is challenging. Even if the images are available, obtaining ground truth that shows the pixel-precise region covered by polyps is challenging. In this context, we selected the polyp class of the Kvasir dataset and annotated it with the help of a medical doctor and an expert gastroenterologist. The information about the Kvasir dataset collection procedure and dataset details can be found on this webpage. By adding ground truth and bounding box information to the Kvasir dataset's polyp class, we encourage computer vision and multimedia community researchers to develop methods that can contribute to automated polyp segmentation. 

🔍 **Use-Cases**:
- Automatic pixel-wise polyp segmentation
- Automatic polyp detection
- Medical image segmentation
- Data augmentation studies
- Benchmarking of the different deep learing methods
- Transfer learning
- Model interpretability studies 

### Kvasir-SEG sample
<img src="Kvasir-seg.png">

The figure shows the example images from Kvasir-SEG. The white mask shows the area covered by the polyp region, and the background regions contain non-polyp tissue pixels. Few image samples contain the endoscope position marking probe that shows the position from where the images were captured. The images in the Kvasir-SEG were captured using ScopeGuide (Olympus). It is to be noted that in the Kvasir-SEG, we have replaced 13 images from the polyp class to enhance the dataset quality. We have put images and masks into a separate folder. The information about the bounding box is stored in JSON file format. The image name and its corresponding ground truth are the same.

### Dataset Details
- **Size**: 46.2 MB
- **Content**: 1000 polyp images with their respective ground truth from Kvasir Dataset v2.
- **Resolution Range**: 332x487 to 1920x1072 pixels
- **Storage**: Images and masks are organized in distinct folders but share identical filenames.
- **Bounding Box Info**: Stored in JSON file format.

The bounding box (coordinate points) for the corresponding images are stored in a JSON file. This dataset is designed to push the state-of-the-art solution for the polyp detection task. Some examples of the dataset.

### Suggested Metrics
There are different metrics for evaluating the performance of the architectures on the image segmentation dataset. For medical image segmentation tasks, the most commonly used ones are the Dice coefficient and Intersection over Union (IOU). Based on related work in this field, we have used these metrics to evaluate the algorithms. In future work, we encourage using these metrics to evaluate the model's performance. In the future, it is better to include as many as possible metrics for a fair comparison of the models.

### [Download Kvasir-SEG]
The dataset can be downloaded using this [link](https://datasets.simula.no/kvasir-seg/)

📄 **Publication**:
- [Arxiv](https://arxiv.org/pdf/1911.07069.pdf)
- [Official Publication](https://link.springer.com/chapter/10.1007/978-3-030-37734-2_37)

## Citation
Please cite our paper if you find the work useful: 
<pre>
@inproceedings{jha2020kvasir,
  title={Kvasir-seg: A segmented polyp dataset},
  author={Jha, Debesh and Smedsrud, Pia H and Riegler, Michael A and Halvorsen, P{\aa}l and de Lange, Thomas and Johansen, Dag and Johansen, H{\aa}vard D},
  booktitle={MultiMedia Modeling: 26th International Conference, MMM 2020, Daejeon, South Korea, January 5--8, 2020, Proceedings, Part II 26},
  pages={451--462},
  year={2020}
}
</pre>

## Terms of use

The use of the Kvasir-SEG dataset is restricted for research and educational purposes. Using the Kvasir-SEG dataset for commercial purposes is forbidden without prior written permission. For other reasons, please feel free to contact us (see below). In all documents and publications that use the Kvasir-SEG dataset or report experimental results based on the Kvasir-SEG dataset, a reference to the dataset paper has to be included (see below). 

## Contact
please contact debeshjha1@gmail.com for any further questions. 

