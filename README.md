<h1><u>Traditional Chinese Landscape Painting Dataset </u></h1>


<b>Paper Title</b>: "End-to-End Chinese Landscape Painting Creation Using Generative Adversarial Networks"\
<b>ArXiv:</b> https://arxiv.org/abs/2011.05552 \
<b>Abstract:</b> \
Current GAN-based art generation methods produce unoriginal artwork due to their dependence on conditional input. Here, we propose Sketch-And-Paint GAN (SAPGAN), the first model which generates Chinese landscape paintings from end to end, without conditional input. SAPGAN is composed of two GANs: SketchGAN for generation of edge maps, and PaintGAN for subsequent edge-to-painting translation. Our model is trained on a new dataset of traditional Chinese landscape paintings never before used for generative research. A 242-person Visual Turing Test study reveals that SAPGAN paintings are mistaken as human artwork with 55% frequency, significantly outperforming paintings from baseline GANs. Our work lays a groundwork for truly machine-original art generation.

*Sketch-And-Paint GAN, compared with baseline models:*
![Alt Text](https://github.com/alicex2020/Chinese-Landscape-Painting-Dataset/blob/main/paper-figure.jpg)

---


Here, we provide the dataset used to train our Sketch-And-Paint GAN model. The dataset consists of 2,192 high-quality traditional Chinese landscape paintings (中国山水画). All paintings are sized 512x512, from the following sources:
* <a href=https://artmuseum.princeton.edu/search/collections>Princeton University Art Museum</a>, 362 paintings
* <a href=https://harvardartmuseums.org/collections/api>Harvard University Art Museum</a>, 101 paintings
* <a href=https://metmuseum.github.io/>Metropolitan Museum of Art</a>, 428 paintings
* <a href=http://edan.si.edu/openaccess/apidocs/>Smithsonian's Freer Gallery of Art</a>, 1,301 paintings

For more details about dataset collection methodology, please see the <a href=https://arxiv.org/abs/2011.05552>paper</a>.

Dataset Samples:\
![Alt Text](https://github.com/alicex2020/Chinese-Landscape-Painting-Dataset/blob/main/dataset-samples.jpg)

---

Please cite the paper if you choose to use this dataset for your research.

```
@misc{xue2020endtoend,
      title={End-to-End Chinese Landscape Painting Creation Using Generative Adversarial Networks}, 
      author={Alice Xue},
      year={2020},
      eprint={2011.05552},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
