# Top Computer Vision Papers in March 2023

Computer vision, a field of artificial intelligence focused on enabling machines to interpret and understand the visual world, is rapidly evolving with groundbreaking research and technological advancements. 

In March 2023, several top-tier academic conferences and journals showcased innovative research in computer vision, presenting exciting breakthroughs in various subfields such as image recognition, vision model optimization, generative adversarial networks (GANs), image segmentation, video analysis, and more. 

In this notebook, we will provide a comprehensive overview of the most significant papers published in March 2023, highlighting the latest research and advancements in computer vision. The papers can be in this 9 categories:

* [Image Recognition](https://github.com/youssefHosni/Montly-Top-Computer-Vision-Papers/blob/main/Top%20CV%20Papers%20in%20March%202023.md#:~:text=1.%20Image%20Recognition)
* [Vision Model Optimization](https://github.com/youssefHosni/Montly-Top-Computer-Vision-Papers/blob/main/Top%20CV%20Papers%20in%20March%202023.md#:~:text=2.%20Vision%20Model%20Optimization)
* [Generative Adversarial Networks (GANS)]()
* [Image Segmentation]()
* [Video Analysis]()
* [Image & Video Editing]()
* [Text to Image Generation]()
* [Image & Video Reconstruction]()
* [Action Recognition]()



<h4 align="left">1. Image Recognition </h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[Your Diffusion Model is Secretly a Zero-Shot Classifier](https://arxiv.org/abs/2303.16203) | [:octocat:](https://diffusion-classifier.github.io) | In this paper, the authors show that the density estimates from large-scale text-to-image diffusion models like Stable Diffusion can be leveraged to perform zero-shot classification without any additional training. The  generative approach to classification, which they called Diffusion Classifier, attains strong results on a variety of benchmarks and outperforms alternative methods of extracting knowledge from diffusion models. Although a gap remains between generative and discriminative approaches on zero-shot recognition tasks, they found that this diffusion-based approach has stronger multimodal relational reasoning abilities than competing discriminative approaches.|
| []()  | | |
| []()  | | |
| []()  | | |


<h4 align="left">2. Vision Model Optimization </h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
| [Scaling Vision-Language Models with Sparse Mixture of Experts](https://arxiv.org/abs/2303.07226) | -- |In this paper, the authors explore the effectiveness of MoE in scaling vision-language models, demonstrating its potential to achieve state-of-the-art performance on a range of benchmarks over dense models of equivalent computational cost. |
| []()  | | |
| []()  | | |


<h4 align="left"> 3. Generative Adversarial Networks (GANS) </h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[StyleGANEX: StyleGAN-Based Manipulation Beyond Cropped Aligned Faces](https://arxiv.org/abs/2303.06146) |[:octocat:](https://www.mmlab-ntu.com/project/styleganex/) | In this paper, authors  propose a simple and effective solution to this limitation by using dilated convolutions to rescale the receptive fields of shallow layers in StyleGAN, without altering any model parameters. This allows fixed-size small features at shallow layers to be extended into larger ones that can accommodate variable resolutions, making them more robust in characterizing unaligned faces. |
| [Consistency Models](https://arxiv.org/abs/2303.01469)|-- |The authors propose consistency models, a new family of generative models that achieve high sample quality without adversarial training. They support fast one-step generation by design, while still allowing for few-step sampling to trade compute for sample quality. |
|[Scaling up GANs for Text-to-Image Synthesis](https://mingukkang.github.io/GigaGAN/static/paper/gigagan_cvpr2023_compressed.pdf) |[:octocat:](https://mingukkang.github.io/GigaGAN/) |Can we scale up GANs to benefit from large datasets like LAION? In this paper, the authors found that naÏvely increasing the capacity of the StyleGAN architecture quickly becomes unstable. They introduced GigaGAN, a new GAN architecture that far exceeds this limit, demonstrating GANs as a viable option for text-to-image synthesis. GigaGAN offers three major advantages. First, it is orders of magnitude faster at inference time, taking only 0.13 seconds to synthesize a 512px image. Second, it can synthesize high-resolution images, for example, 16-megapixel pixels in 3.66 seconds. Finally, GigaGAN supports various latent space editing applications such as latent interpolation, style mixing, and vector arithmetic operations. |
| []()  | | |
| []()  | | |



<h4 align="left">4. Image Segmentation:</h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[Mask-free OVIS: Open-Vocabulary Instance Segmentation without Manual Mask Annotations](https://arxiv.org/abs/2303.16891) |[:octocat:](https://vibashan.github.io/ovis-web/) |This paper proposes a manual-mask-free approach for open-vocabulary instance segmentation leveraging a pre-trained vision-language model. Specifically, the authors generate pseudo-masks annotations for objects of interest from image-caption pairs using pre-trained VLM and weakly-supervised proposal and segmentation networks. These generated pseudo-mask annotations are then used to train an instance segmentation model, completely eliminating the need for human-provided box-level or pixel-level annotations.  |
| [Open-Vocabulary Panoptic Segmentation with Text-to-Image Diffusion Models](https://arxiv.org/pdf/2303.04803.pdf) |[:octocat:](https://jerryxu.net/ODISE/) |Text-to-image diffusion models have shown the remarkable capability of generating high-quality images with diverse open-vocabulary language descriptions. This demonstrates that their internal representation space is highly correlated with open concepts in the real world. Text-image discriminative models like CLIP, on the other hand, are good at classifying images into open-vocabulary labels. The authors propose to leverage the frozen representation of both these models to perform panoptic segmentation of any category in the wild. |
| [Open-world Instance Segmentation: Top-down Learning with Bottom-up Supervision](https://arxiv.org/abs/2303.05503) |[:octocat:](https://tarun005.github.io/UDOS/)|In this paper authors present UDOS for instance segmentation in an open world by leveraging weak supervision from unsupervised bottom-up segmentation algorithms like selective search. They  first predict part masks corresponding to objects, followed by affinity-based grouping and refinement modules to predict full-instance masks for both seen and unseen objects in an image. They achieved significantly better results compared to existing SOTA on open-world instance segmentation on several datasets |
| []()  | | |
| []()  | | |


<h4 align="left">5. Video Analysis:</h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
| [Unmasked Teacher: Towards Training-Efficient Video Foundation Models](https://arxiv.org/abs/2303.16058)|[:octocat:](https://github.com/OpenGVLab/unmasked_teacher)  | |
| []()  | | |
| []()  | | |
| []()  | | |


<h4 align="left">6. Image & Video Editing:</h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
| [Video-P2P: Video Editing with Cross-attention Control]()  | | |
| [Edit-A-Video: Single Video Editing with Object-Aware Consistency]()  |  | |
| [VIVE3D: Viewpoint-Independent Video Editing using 3D-Aware GANs]()  | | |
| [StyleDiffusion: Prompt-Embedding Inversion for Text-Based Editing]()  | | |
| [MDP: A Generalized Framework for Text-Guided Image Editing by Manipulating the Diffusion Path]()  | | |
| [StyO: Stylize Your Face in Only One-Shot]()  | | |
| [Zero-Shot Video Editing Using Off-The-Shelf Image Diffusion Models]()  | | |



<h4 align="left">7. Text to Image Generation:</h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
|[One Transformer Fits All Distributions in Multi-Modal Diffusion at Scale](https://arxiv.org/abs/2303.06555) |[:octocat:](https://github.com/thu-ml/unidiffuser) | This paper proposes a unified diffusion framework (dubbed UniDiffuser) to fit all distributions relevant to a set of multi-modal data in one model. Inspired by the unified view, UniDiffuser learns all distributions simultaneously with a minimal modification to the original diffusion model - perturbs data in all modalities instead of a single modality, inputs individual timesteps in different modalities, and predicts the noise of all modalities instead of a single modality. |
| [HOLODIFFUSION: Training a 3D Diffusion Model using 2D Images](https://arxiv.org/abs/2303.16509)  | | |
| [Highly Personalized Text Embedding for Image Manipulation by Stable Diffusion](https://arxiv.org/abs/2303.08767)  | | |
| [Encoding Visual Concepts into Textual Embeddings for Customized Text-to-Image Generation](https://arxiv.org/abs/2302.13848)|[:octocat:](https://github.com/csyxwei/ELITE) | |
| [TRACT: Denoising Diffusion Models with Transitive Closure Time-Distillation](https://arxiv.org/abs/2303.04248) | | |
| [Zeroth-Order Optimization Meets Human Feedback: Provable Learning via Ranking Oracles](https://arxiv.org/abs/2303.03751)|[:octocat:](https://github.com/TZW1998/Taming-Stable-Diffusion-with-Human-Ranking-Feedback)| |
| [Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models](https://arxiv.org/abs/2303.04671) |[:octocat:](https://github.com/microsoft/visual-chatgpt) | |
| [Cones: Concept Neurons in Diffusion Models for Customized Generation](https://arxiv.org/abs/2303.05125)  | | |
| [Let 2D Diffusion Model Know 3D-Consistency for Robust Text-to-3D Generation](https://arxiv.org/abs/2303.07937) |[:octocat:](https://ku-cvlab.github.io/3DFuse/) | |
| [SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://arxiv.org/abs/2211.12194) |[:octocat:](https://github.com/Winfredy/SadTalker) | |
| [High-resolution image reconstruction with latent diffusion models from human brain](https://www.biorxiv.org/content/10.1101/2022.11.18.517004v3)  |  | |
| [Erasing Concepts from Diffusion Models](https://arxiv.org/abs/2303.07345) |[:octocat:](https://erasing.baulab.info/) | |
| [Word-As-Image for Semantic Typography](https://arxiv.org/abs/2303.01818) |[:octocat:](https://wordasimage.github.io/Word-As-Image-Page/) | |
| [Consistent View Synthesis with Pose-Guided Diffusion Models](https://arxiv.org/abs/2303.17598)  | | |
| [Discriminative Class Tokens for Text-to-Image Diffusion Models](https://arxiv.org/abs/2303.17155) |  | |
| [Token Merging for Fast Stable Diffusion](https://arxiv.org/abs/2303.17604)|[:octocat:](https://github.com/dbolya/tomesd) | |
| [Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models](https://arxiv.org/abs/2303.11989) |[:octocat:](https://lukashoel.github.io/text-to-room/) | |
| [SoftCLIP: Softer Cross-modal Alignment Makes CLIP Stronger](https://arxiv.org/abs/2303.17561) | | |

[:octocat:]()


<h4 align="left">8. Image & Video Reconstruction:</h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
| [PixMIM: Rethinking Pixel Reconstruction in Masked Image Modeling]()  |  | |
| [X-Avatar: Expressive Human Avatars]()  | | |
| [Learning Object-Centric Neural Scattering Functions for Free-viewpoint Relighting and Scene Composition]()  | | |
| [NeRFLiX: High-Quality Neural View Synthesis by Learning a Degradation-Driven Inter-viewpoint MiXer]()  | | |
| [NeuralLift-360: Lifting An In-the-wild 2D Photo to A 3D Object with 360° Views]()  | | |
| [MobileBrick: Building LEGO for 3D Reconstruction on Mobile Devices]()  | | |
| [3D Cinemagraphy from a Single Image]()  | | |
| [NeRFMeshing: Distilling Neural Radiance Fields into Geometrically-Accurate 3D Meshes]()  | | |



<h4 align="left">9. Action Recognition:</h4>

| Paper  | Project Page | Abstract / Short Summary |
| ------------- | ------------- |------------- |
| [Vision-Language Models as Success Detectors](https://arxiv.org/abs/2303.07280) |  | |
| [SynthVSR: Scaling Up Visual Speech Recognition With Synthetic Supervision](https://arxiv.org/abs/2303.17200)  | | |

