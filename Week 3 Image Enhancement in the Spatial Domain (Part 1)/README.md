# Week 3 Image Enhancement in the Spatial Domain (Part 1)

This week is about Image Enhancement in the Spatial Domain.

This lab contains

- **Image Negatives/ Nagative Transformation**: Enhancing white or grey detail embedded in dark regions of an image, especially when the black areas are dominant in size.
- **Power-Law Transformation**: Use gamma correction which enhances the given images by power-law response phenomena.
- **Piecewise-Linear Transformations**
  - **Gray-level Slicing**: Enhance the low contrast images.
    - Background change to black (interval [A, B] -> 255, others -> 0)
    - Background unchange (interval [A, B] -> 255, others -> stay the same)
  - **Bit-Plane Slicing**: Highlighting the contribution made by each bit is useful and used in image compression. *Most significant bits contains the majority of the visually
significant data*.
