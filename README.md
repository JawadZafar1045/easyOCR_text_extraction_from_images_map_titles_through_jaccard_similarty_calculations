# easyOCR_text_extraction_from_images_map_titles_through_jaccard_similarty_calculations

## Overview

This project aims to recognize game titles from images using the EasyOCR library and map the extracted text to a database of game titles using the Jaccard similarity algorithm. The system provides an efficient way to catalog and organize game collections without manual input.

## Dependencies

- Python 3.x
- OpenCV (cv2)
- EasyOCR
- Matplotlib

Install the required dependencies using the following command:

```bash
pip install opencv-python-headless easyocr matplotlib
```

## Usage

1. Ensure you have the necessary dependencies installed.
2. Clone this repository to your local machine.
3. Place your images containing game titles in the specified directory.
4. Update the `image_path` variable in the `main()` function of the `easy-jaccard.py` file to point to the location of your image.
5. Run the `easy-jaccard.py` file using Python:

```bash
python `easy-jaccard.py`
```

The program will display the image with bounding boxes around the detected text and print the recognized game title.

## Customization

- You can modify the list of original game titles in the `load_original_titles()` function to suit your collection.
- Fine-tune the Jaccard similarity threshold in the `calculate_jaccard_similarity()` function to adjust the sensitivity of the matching algorithm.
- Experiment with different preprocessing techniques or OCR models to improve text extraction accuracy.

## Contributing

Contributions are welcome! If you have any ideas for improvements or encounter any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
