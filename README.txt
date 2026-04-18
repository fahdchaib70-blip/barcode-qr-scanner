This folder contains the input images used to test the barcode and QR code scanner.

The dataset was manually created and includes different types of images to evaluate the performance of the system under various conditions.

Content of the dataset:

1. Simple barcode images
- Images containing a single 1D barcode
- Used to verify basic detection and decoding

2. Mixed QR code and barcode images
- Images containing both QR codes and barcodes
- Used to test multi-object detection and decoding

3. Multiple QR code images
- Images containing several QR codes in the same image
- Used to evaluate the ability to detect multiple regions

4. Complex scenes
- Images where codes are placed in different positions and backgrounds
- Used to test robustness of detection (different colors, layouts, spacing)

5. Realistic examples
- Poster-style or design images containing QR codes
- Used to simulate real-world use cases

Purpose of the dataset:

- Test preprocessing (grayscale and blur)
- Evaluate edge detection and contour extraction
- Validate barcode and QR code localization
- Test decoding accuracy using pyzbar
- Demonstrate batch processing on multiple images

Notes:

- Images vary in size, resolution, and complexity
- Some images contain multiple codes
- Some images are intentionally more complex to highlight limitations of the system