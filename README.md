# Visualization of Latent Space of Discrete Distribution Networks during Optimization
**Uncompressed raw video of [YouTube version](https://youtu.be/J4aOdyb7A58) and [BiliBili version](https://www.bilibili.com/video/BV11tjdzbEoD/)**

Due to GitHub's restriction on uploading files larger than 100MB, the video was split into two segments. The following command is needed to merge them:
```bash
ffmpeg -f concat -safe 0 \
       -i <(printf "file '%s'\n" "$PWD"/DDN_latent_vis_with_BGM_{0,1}.mp4) \
       -c copy -movflags +faststart output.mp4
```


<!-- clip 1
<video controls muted loop playsinline width="512px"> 
  <source src="DDN_latent_vis_with_BGM_0.mp4" type="video/mp4">
</video> -->
---

This video demonstrates the changes in the latent space of Discrete Distribution Networks when fitting the handwritten digits dataset (MNIST).  
Discrete Distribution Networks is a brand new generative model accepted by ICLR 2025.  
For a detailed explanation of this visualization, please refer to Figure 6 in the original paper.  

Paper: arxiv.org/abs/2401.00036  
Page: discrete-distribution-networks.github.io/  

#GenerativeModels  #DDN #ICLR #MachineLearning #deeplearning



