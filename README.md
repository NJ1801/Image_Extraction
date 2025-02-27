# Image Extraction and Data Processing

## Overview
This project extracts text from images using **PaddleOCR**, processes the extracted text, and formats it into structured data using **Pandas**. The extracted data is saved as CSV files and later modified manually before reprocessing.

## Requirements
Ensure you have the following dependencies installed before running the script:

```sh
pip install paddleocr
pip install pandas
pip install paddlepaddle
pip install openpyxl
```

## Workflow
1. **Extract Text from Images:**
   - The script processes multiple images using **PaddleOCR**.
   - Extracted text and confidence scores are saved as CSV files.

2. **Modify Extracted Data Manually:**
   - The extracted CSV files are manually edited and saved as Excel files.

3. **Reprocess Modified Data:**
   - The script loads modified Excel files.
   - Extracted key-value pairs are processed into structured data.
   - The final structured data is saved as CSV files.

## File Structure
```
📂 Image_Extraction
│-- extracted_text_1.csv    # Extracted text from image 1
│-- extracted_text_3.csv    # Extracted text from image 3
│-- Modified_data/
│   │-- modified_text_1.xlsx  # Manually modified data for image 1
│   │-- modified_text_3.xlsx  # Manually modified data for image 3
│-- Final_Output_1.csv       # Processed structured data for image 1
│-- Final_Output_3.csv       # Processed structured data for image 3
│-- script.py                # Main Python script
│-- README.md                # This file
```

## Usage
1. **Run the script** to extract text from images:
   ```sh
   python script.py
   ```
2. **Modify extracted CSV files** manually and save them as Excel files.
3. **Re-run the script** to process modified files and generate structured data.

## Output
The final structured data is saved as:
- `Final_Output_1.csv`
- `Final_Output_3.csv`

## Notes
- Ensure the modified Excel files contain a column named `Text` for proper processing.
- File paths should be updated as needed in the script.

## Support the project

<a href="https://www.linkedin.com/in/nagarajanbj/" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-black.png" alt="Buy Me A Coffee" height="45" width="163" ></a>


#### Happy Coding  ♥️

## Author
Developed by **Nj** 🚀

