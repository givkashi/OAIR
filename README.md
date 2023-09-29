# Aesthetic-aware image retargeting based on foreground–background separation and PSO optimization

Accepted in Multimedia Tools and Applications, Springer Journal
[[Springer Link](https://link.springer.com/article/10.1007/s11042-023-16959-6)]

<details>
    <summary>Abstract (click to view)</summary>
    Image retargeting aims at altering images’ size while preserving important content and minimizing noticeable distortions. However, previous image retargeting methods create outputs that suffer from artifacts and distortions. Besides, most previous works attempt to retarget the background and foreground of the input image simultaneously. Simultaneous resizing of the foreground and background causes changes in the aspect ratios of the objects. The change in the aspect ratio is specifically not desirable for human objects. We propose a retargeting method that overcomes these problems. The proposed approach consists of the following steps. Firstly, an inpainting method uses the input image and the binary mask of foreground objects to produce a background image without any foreground objects. Secondly, the seam carving method resizes the background image to the target size. Then, a super-resolution method increases the input image quality, and we then extract the foreground objects. Finally, the retargeted background and the extracted super-resolued objects are fed into a particle swarm optimization algorithm (PSO). The PSO algorithm uses aesthetic quality assessment as it's objective function to identify the best location and size for the objects to be placed on the background. We used the image quality assessment and aesthetic quality assessment measures to show our superior results compared to popular image retargeting techniques.
</details>

<div>
    <img src="./Block diagram.png" width="90%">
</div>
(*Block diagram of the proposed method. Block (a) foreground processing, block (b) background processing, and block (c) foreground-background merging)

---

* [Our Dataset](https://github.com/givkashi/OAIR/tree/main/dataset)


## Dataset References
* [HKU-IS](https://i.cs.hku.hk/~yzyu/research/deep_saliency.html)
* [CascadePSP](https://github.com/hkchengrex/CascadePSP)

## Citation
If you found this article helpful, please consider citing: 
```
Naderi, M.R., Givkashi, M.H., Karimi, N. et al.
Aesthetic-aware image retargeting based on foreground–background separation and PSO optimization.
Multimed Tools Appl (2023).
https://doi.org/10.1007/s11042-023-16959-6
```
