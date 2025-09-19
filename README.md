# Group_project_MetadataExtractionPipeline
SEM Metadata Extraction from Images 
This Python project extracts metadata from Scanning Electron Microscope (SEM) TIFF images and converts it into JSON format. It supports complex metadata stored as XML or key-value pairs inside the image files.
Features:
 1) Extracts SEM metadata from TIFF images.
 2) Converts nested XML and key-value pairs into clean JSON.
 3) Handles multiple edge cases, including tuples, lists, and bytes.
 4) Saves JSON output to a separate folder.
Requirements:
 1)Python 3.8+
 2)Pillow (pip install pillow)
 3)SEMMeta Python library (pip install sem-meta)
Usage :
1)Place all your SEM TIFF images in the Btest/ folder.
2)Run the Python script
3)python extract_metadata.py
4)The JSON metadata for each image will be saved in the Btest_json2/ folder.
