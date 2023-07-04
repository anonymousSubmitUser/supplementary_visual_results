# Rebuttal

## Reviewer 4Bp3

![vary_depth_1](figs/vary_depth_1.png)

**Figure 1: Out-painting results of scenes with variable depth on SUN360 Dataset. All scenes presented have objects which are very close to the camera. For both "overlap" and "wide baseline" cases, our method is able to accurately estimate the relative pose of input image pairs and generate plausible panoramas.**

![vary_depth_1](figs/vary_depth_2.png)

**Figure 2: To illustrate that the significant accuracy drop-off of "wide baseline" cases does not substantially influenced the generation quality, we present some failure samples where the predicted relative poses are inaccurate while our model still generates reasonable results.**

![vary_depth_1](figs/laval_low_light.png)

**Figure 3: Out-painting results on scenes with extremely low illumination. The inputs are acquired by reducing the exposure parameters on original raw images from Laval Indoor Dataset. From above it can be found that our method tends to generate panoramas with normal lighting, this limitation is caused by the lack of low-light training data.**