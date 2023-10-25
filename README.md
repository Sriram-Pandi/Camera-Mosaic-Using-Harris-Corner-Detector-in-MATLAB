**Title:** Camera Mosaic Using Harris Corner Detector in MATLAB

**Description:**

The objective of this laboratory experiment is to understand the basics of camera calibration and image mosaicing. The project utilizes the Harris corner detector for feature detection and emphasizes the process of creating image mosaics, which involve stitching together multiple overlapping images to create a panoramic view.

**Steps Involved**:

1. **Camera Calibration**:
   - Utilized the Caltech Camera Calibration toolbox for MATLAB.
   - Printed a calibration pattern and mounted it on a flat surface.
   - Captured multiple images of the calibration pattern from varying angles, ensuring that the pattern occupied most of the frame.
   - Performed camera calibration to obtain intrinsic and extrinsic parameters, and ensured that the reprojection error was minimal.

2. **Feature Detection using Harris Corner Detector**:
   - Used the provided Harris feature detector to identify corners in the images.
   - Experimented with the parameters of the Harris detector to get well-distributed features across each image.

3. **Image Mosaicing**:
   - Captured overlapping images of a mural on the Latino Students Center (LSC) building.
   - Employed the feature-based panoramic image stitching example from MATLAB as a template.
   - Created a panoramic mosaic of the LSC building, ensuring the images were stitched seamlessly.
   - Repeated the mosaicing process for a cinder block wall using multiple overlapping images.
   - Analyzed the performance of the mosaicing algorithm with varying degrees of overlap: 15% and 50%.

4. **Analysis and Observations**:
   - Evaluated the performance of the Harris corner detector in detecting features across different images.
   - Analyzed the results of the image mosaicing process for different scenes and overlaps.
   - Documented challenges, modifications made, and insights drawn from the mosaicing process.

By the end of this project, I acquired a deep understanding of the principles behind camera calibration, feature detection, and image mosaicing. I was also able to critically evaluate the performance of the Harris corner detector and its application in creating image mosaics. The project underscored the importance of feature detection in the domain of computer vision and its vast applications in real-world scenarios.
