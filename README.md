# Kvasir-SEG: A Segmented Polyp Dataset

📑 **Please find the paper here**: [Kvasir-SEG: A Segmented Polyp Dataset](https://arxiv.org/pdf/1911.07069.pdf),

Colorectal polyp segmentation is a demanding task in medical image segmentation. Research in polyp segmentation using computer vision techniques can improve examination procedures and reduce the polyp miss rate during colonoscopy. However, finding the publicly available dataset is challenging. Even if the images are available, obtaining ground truth that shows the pixel-precise region covered by polyps is challenging. In this context, we selected the polyp class of the Kvasir dataset and annotated it with the help of a medical doctor and an expert gastroenterologist. The information about the Kvasir dataset collection procedure and dataset details can be found on this webpage. By adding ground truth and bounding box information to the Kvasir dataset's polyp class, we encourage computer vision and multimedia community researchers to develop methods that can contribute to automated polyp segmentation. 

🔍 **Use-Cases**:
- Semantic sementation
- Polyp segmentation
- Medical image segmentation
- Benchmarking of the different deep learing

### Dataset sample
<img src="Kvasir-seg.png">



The figure shows the example images from Kvasir-SEG. The white mask shows the area covered by the polyp region, and the background regions contain non-polyp tissue pixels. Few image samples contain the endoscope position marking probe that shows the position from where the images were captured. The images in the Kvasir-SEG were captured using ScopeGuide (Olympus). It is to be noted that in the Kvasir-SEG, we have replaced 13 images from the polyp class to enhance the dataset quality. We have put images and masks into a separate folder. The information about the bounding box is stored in JSON file format. The image name and its corresponding ground truth are the same.

### Kvasir-SEG Dataset Details
The Kvasir-SEG dataset (size 46.2 MB) contains 1000 polyp images and their corresponding ground truth from the Kvasir Dataset v2. The resolution of the images contained in Kvasir-SEG varies from 332x487 to 1920x1072 pixels. The images and its corresponding masks are stored in two separate folders with the same filename. The image files are encoded using JPEG compression, and online browsing is facilitated. The open-access dataset can be easily downloaded for research and educational purposes.

The bounding box (coordinate points) for the corresponding images are stored in a JSON file. This dataset is designed to push the state-of-the-art solution for the polyp detection task. Some examples of the dataset.

### Suggested Metrics
There are different metrics for evaluating the performance of the architectures on the image segmentation dataset. For medical image segmentation tasks, the most commonly used ones are the Dice coefficient and Intersection over Union (IOU). Based on related work in this field, we have used these metrics to evaluate the algorithms. In future work, we encourage using these metrics to evaluate the model's performance. In the future, it is better to include as many as possible metrics for a fair comparison of the models.

## Downloadable link: 

Kvasir-SEG can be downloaded from [here](https://datasets.simula.no/kvasir-seg/). No prior permission is required for downloading when using the dataset for academic and research purposes. For commercial purposes, prior permission is required. We have received a few requests to use the dataset for commercial purposes and have approved them all. The dataset has also been used in a few competitions and challenges. The baseline results can be found here. Through these baseline results, we also invite other medical image analysis and multimedia research to develop and improve the current SOTA. Portions of the research community have adopted the Kvasir-SEG to benchmark their new ML algorithms and develop novel methods on the dataset.

## Publication:
[Arxiv] (https://arxiv.org/pdf/1911.07069.pdf)
[Official publication](https://link.springer.com/chapter/10.1007/978-3-030-37734-2_37)

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

