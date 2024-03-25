# detecting-defective-bottles-
detect defective bottles using python 
**README.md**

# Bottle Inspection System

This repository contains Python code for a Bottle Inspection System. The system aims to automate the inspection process for bottles in images, checking various aspects such as label alignment, cap presence, underfilling, and overall bottle shape.

## Prerequisites

To run the code, you need the following dependencies:

- Python 3.x
- OpenCV (cv2)
- NumPy

You can install these dependencies using pip:

```
pip install opencv-python numpy
```

## Usage

To use the Bottle Inspection System, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/bottle-inspection-system.git
```

2. Navigate to the directory:

```
cd bottle-inspection-system
```

3. Run the main script:

```
python main.py
```

This will execute the main script, which contains functions to inspect bottles in images.

## Functions

### 1. `detect_missing_bottle(image)`

This function detects if a bottle is missing in a specified region of the input image.

### 2. `is_bottle_underfilled(image)`

This function determines if a bottle is underfilled based on the percentage of black pixels within a specified region of the input image.

### 3. `is_bottlelabel_missing(image)`

This function detects if a bottle is missing its label based on the percentage of black pixels within a specified region of the input image.

### 4. `detect_cap(image, pixels_per_cm, cap_segments)`

This function identifies bottles with caps in specified segments of the input image.

### 5. `is_label_not_printed(image)`

This function checks if a label is not printed or lightly printed on a bottle within a specified region of the input image.

### 6. `verify_label_alignment(img)`

This function verifies the alignment and clarity of a label within a specified segment of the input image.

### 7. `check_bottle_shape(image)`

This function checks the shape of a bottle within the input image, ensuring it meets specified criteria.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or additional features you'd like to see in the Bottle Inspection System.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
