# General Test

## EDA

### Sphere Sub structure

![sphere_images](images/sphere_images.png)

### Vort Sub structure

![vort_images](images/vort_images.png)

### No Sub structure

![sphere_images](images/no_substructure_images.png)


## Results

| Method             | Description | Result (Accuracy) |
|--------------------|-------------|-------------------|
|Basic CNN           | custom CNN network with no pretrain weights| Not Converging |
|MobileNetV3 small| MobileNetV3 architecture pretrained on Imagenet| 0.711|
|MobileViT | Visual Attention Transformer pretrained on Imagenet | 0.908 |

### Best Results
![stats](images/best_results_conf.png)
![stats](images/best_results_stats.png)
![stats](images/best_results_auc.png)
![stats](images/best_results_micro.png)
![stats](images/best_results_ovr_sphere.png)
![stats](images/best_results_ovr_vort.png)
![stats](images/best_results_ovr.png)