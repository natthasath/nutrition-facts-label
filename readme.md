
# Nutrition Facts Label
The project of Master Degree in NIDA
Documentation for data science and other people interest this project

[![Watch the video](https://www.loom.com/share/4c4eae267b4a4f3bb08a2ae244a0ee65)](https://www.loom.com/share/4c4eae267b4a4f3bb08a2ae244a0ee65)

## Structure
```

```

## Technical
* Table Detection
* Text Detection & Extraction
* OCR Image Processing
* Image Post-Processing

## Preqisition
Download and Install tool for run code this project
- [Git](https://git-scm.com/download/win)
- [Python 3.0+](https://www.python.org/downloads/release/python-3410/)
- [Dataset Open Food Facts](https://world.openfoodfacts.org)

## Clone Repository
```
# git clone https://github.com/natthasath/nutrition-facts-label.git
# cd nutrition-facts-label
```

## Create Virtualenv
```
# mkvirtualenv nutrition
# lsvirtualenv nutrition
# workon nutrition
```

## Install Package
```
# pip install -r requirements.txt
# pip freeze
```

## Run
```
# cd nutrition-facts-label/nutrition_extractor
# python detection.py -i data/test_images/ocr_eng_07.jpg
# python detection.py -i data/test_images/ocr_eng_07.jpg --debug
```

## Result
```
# data/result/output.jpg
# data/nutrition.csv
```

## License
Codeinsane License.
