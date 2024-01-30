# Counting-grains
A set of notebooks  to count the grains on a dish

We use EfficientSAM in our workflow, 

This basically involves generating a grid of point prmpts over the image and getting the relevant masks. 

Since the original image is large, we slice it into smaller windows and run EfficientSAM. The annotated images are then stiched back. 

For the curious:

```
Total number of grains: 39690
```
