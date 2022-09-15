# OAIR: Object-Aware Image Retargeting Using PSO and Aesthetic Quality Assessment

[[arXiv](https://arxiv.org/abs/2209.04804)]

<details>
    <summary>Abstract (click to view)</summary>
    Image retargeting aims at altering images’ size while preserving important content and minimizing noticeable distortions. However, previous image retargeting methods create outputs that suffer from artifacts and distortions. Besides, most previous works attempt to retarget the background and foreground of the input image simultaneously. Simultaneous resizing of the foreground and background causes changes in the aspect ratios of the objects. The change in the aspect ratio is specifically not desirable for human objects. We propose a retargeting method that overcomes these problems. The proposed approach consists of the following steps. Firstly, an inpainting method uses the input image and the binary mask of foreground objects to produce a background image without any foreground objects. Secondly, the seam carving method resizes the background image to the target size. Then, a super-resolution method increases the input image quality, and we then extract the foreground objects. Finally, the retargeted background and the extracted super-resolued objects are fed into a particle swarm optimization algorithm (PSO). The PSO algorithm uses aesthetic quality assessment as it's objective function to identify the best location and size for the objects to be placed on the background. We used the image quality assessment and aesthetic quality assessment measures to show our superior results compared to popular image retargeting techniques.
</details>

* [Our Dataset](https://github.com/givkashi/OAIR/tree/main/dataset)
## Our results
Coming soon

## Dataset References
* [HKU-IS](https://i.cs.hku.hk/~yzyu/research/deep_saliency.html)
* [CascadePSP](https://github.com/hkchengrex/CascadePSP)
