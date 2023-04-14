# Top Computer Vision Papers in March 2023

* [Image Recognition]()
* [Vision Model Optimization]()
* [Generative Adversarial Networks (GANS)]()
* [Image Segmentation]()
* [Video Analysis]()
* [Image & Video Editing]()
* [Text to Image Generation]()
* [Image & Video Reconstruction]()
* [Action Recognition]()



<h4 align="left">Image Classification:</h4>

| Paper  | Links | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[Your Diffusion Model is Secretly a Zero-Shot Classifier](https://arxiv.org/abs/2303.16203) | [:octocat:](https://diffusion-classifier.github.io) | In this paper, the authors show that the density estimates from large-scale text-to-image diffusion models like Stable Diffusion can be leveraged to perform zero-shot classification without any additional training. The  generative approach to classification, which they called Diffusion Classifier, attains strong results on a variety of benchmarks and outperforms alternative methods of extracting knowledge from diffusion models. Although a gap remains between generative and discriminative approaches on zero-shot recognition tasks, they found that this diffusion-based approach has stronger multimodal relational reasoning abilities than competing discriminative approaches.|
| []()  | | |
| []()  | | |
| []()  | | |


<h4 align="left">Vision Model Optimization:</h4>

| Paper  | Links | Abstract / Short Summary |
| ------------- | ------------- |------------- |
| [Scaling Vision-Language Models with Sparse Mixture of Experts](https://arxiv.org/abs/2303.07226) | -- |In this paper, the authors explore the effectiveness of MoE in scaling vision-language models, demonstrating its potential to achieve state-of-the-art performance on a range of benchmarks over dense models of equivalent computational cost. |
| []()  | | |
| []()  | | |



<h4 align="left">Text to Image Generation:</h4>

| Paper  | Links | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[One Transformer Fits All Distributions in Multi-Modal Diffusion at Scale](https://arxiv.org/abs/2303.06555) |[:octocat:](https://github.com/thu-ml/unidiffuser) | This paper proposes a unified diffusion framework (dubbed UniDiffuser) to fit all distributions relevant to a set of multi-modal data in one model. Inspired by the unified view, UniDiffuser learns all distributions simultaneously with a minimal modification to the original diffusion model - perturbs data in all modalities instead of a single modality, inputs individual timesteps in different modalities, and predicts the noise of all modalities instead of a single modality. |
| []()  |  | |
| []()  | | |
| []()  | | |
| []()  | | |

<h4 align="left">Image Segmentation:</h4>

| Paper  | Links | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[Mask-free OVIS: Open-Vocabulary Instance Segmentation without Manual Mask Annotations](https://arxiv.org/abs/2303.16891) |[:octocat:](https://vibashan.github.io/ovis-web/) |This paper proposes a manual-mask-free approach for open-vocabulary instance segmentation leveraging a pre-trained vision-language model. Specifically, the authors generate pseudo-masks annotations for objects of interest from image-caption pairs using pre-trained VLM and weakly-supervised proposal and segmentation networks. These generated pseudo-mask annotations are then used to train an instance segmentation model, completely eliminating the need for human-provided box-level or pixel-level annotations.  |
| [Open-Vocabulary Panoptic Segmentation with Text-to-Image Diffusion Models](https://arxiv.org/pdf/2303.04803.pdf) |[:octocat:](https://jerryxu.net/ODISE/) |Text-to-image diffusion models have shown the remarkable capability of generating high-quality images with diverse open-vocabulary language descriptions. This demonstrates that their internal representation space is highly correlated with open concepts in the real world. Text-image discriminative models like CLIP, on the other hand, are good at classifying images into open-vocabulary labels. The authors propose to leverage the frozen representation of both these models to perform panoptic segmentation of any category in the wild. |
| [Open-world Instance Segmentation: Top-down Learning with Bottom-up Supervision](https://arxiv.org/abs/2303.05503) |[:octocat:](https://tarun005.github.io/UDOS/)|In this paper authors present UDOS for instance segmentation in an open world by leveraging weak supervision from unsupervised bottom-up segmentation algorithms like selective search. They  first predict part masks corresponding to objects, followed by affinity-based grouping and refinement modules to predict full-instance masks for both seen and unseen objects in an image. They achieved significantly better results compared to existing SOTA on open-world instance segmentation on several datasets |
| []()  | | |
| []()  | | |

<h4 align="left"> Generative Adversarial Networks (GANS) </h4>

| Paper  | Links | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[StyleGANEX: StyleGAN-Based Manipulation Beyond Cropped Aligned Faces](https://arxiv.org/abs/2303.06146) |[:octocat:](https://www.mmlab-ntu.com/project/styleganex/) | In this paper, authors  propose a simple and effective solution to this limitation by using dilated convolutions to rescale the receptive fields of shallow layers in StyleGAN, without altering any model parameters. This allows fixed-size small features at shallow layers to be extended into larger ones that can accommodate variable resolutions, making them more robust in characterizing unaligned faces. |
| [Consistency Models](https://arxiv.org/abs/2303.01469)|-- |The authors propose consistency models, a new family of generative models that achieve high sample quality without adversarial training. They support fast one-step generation by design, while still allowing for few-step sampling to trade compute for sample quality. |
|[Scaling up GANs for Text-to-Image Synthesis](https://mingukkang.github.io/GigaGAN/static/paper/gigagan_cvpr2023_compressed.pdf) |[:octocat:](https://mingukkang.github.io/GigaGAN/) |Can we scale up GANs to benefit from large datasets like LAION? In this paper, the authors found that naÏvely increasing the capacity of the StyleGAN architecture quickly becomes unstable. They introduced GigaGAN, a new GAN architecture that far exceeds this limit, demonstrating GANs as a viable option for text-to-image synthesis. GigaGAN offers three major advantages. First, it is orders of magnitude faster at inference time, taking only 0.13 seconds to synthesize a 512px image. Second, it can synthesize high-resolution images, for example, 16-megapixel pixels in 3.66 seconds. Finally, GigaGAN supports various latent space editing applications such as latent interpolation, style mixing, and vector arithmetic operations. |
| []()  | | |
| []()  | | |

