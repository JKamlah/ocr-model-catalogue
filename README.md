# OCR Model Catalogue

Welcome to our repository, where we have compiled a diverse range of Layout Analysis (LA) and Optical Character Recognition (OCR) models. 
This collection is aimed at providing researchers, developers, and hobbyists with easy access to a variety of OCR models.

## About OCR

Optical Character Recognition (OCR) is a field of study that involves the conversion of typed, handwritten, 
or printed text into machine-encoded text. 
OCR technology is used to digitize printed texts, so that they can be electronically edited, searched, 
stored more compactly, and used in machine processes such as machine translation, text-to-speech, and data mining.

We have LA und OCR models for different OCR-Engines
- [Kraken]()
- [Tesseract]()
- [Calamari]() 

## Repository Structure

The structure of the repo is the following:

```
├── LICENSE.md
└── data
   └── OCR-Model as submodule   
 ```       

Here's our OCR Model Catalogue:


<!-- Models !-->
## 📂 Models
Model|OCR-Engine|Type of model|Description|Default model
---|---|---|---|---
[German print](data/german-print/data/kraken/text/german_print)|Kraken|Text recognition|Kraken model for german prints trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-print-ocr-model/tree/main/data/kraken/text/german_print/german_print.mlmodel" download>Download</a>
[German print](data/german-print/data/tesseract/best/german_print)|Tesseract|Text recognition|OCR model for german prints trained from several datasets. Best model variant for Tesseract. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-print-ocr-model/tree/main/data/tesseract/best/german_print/german_print_20.traineddata" download>Download</a>
[German print](data/german-print/data/tesseract/fast/german_print)|Tesseract|Text recognition|OCR model for german prints trained from several datasets. Fast model variant for Tesseract. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-print-ocr-model/tree/main/data/tesseract/fast/german_print/german_print_20.traineddata" download>Download</a>
[German newspapers](data/german-newspapers/data/kraken/text/german_newspapers_topologies/kraken)|Kraken|Text recognition|Kraken model with kraken topology for german newspapers trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/kraken/text/german_newspapers/german_newspapers_kraken.mlmodel" download>Download</a>
[German newspapers](data/german-newspapers/data/kraken/text/german_newspapers_topologies/sgd)|Kraken|Text recognition|Kraken model with sgd topology for german newspapers trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/kraken/text/german_newspapers/german_newspapers_sgd.mlmodel" download>Download</a>
[German newspapers](data/german-newspapers/data/kraken/text/german_newspapers_topologies/htr+)|Kraken|Text recognition|Kraken model with htr+ topology for german newspapers trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/kraken/text/german_newspapers/german_newspapers_htr.mlmodel" download>Download</a>
[German newspapers](data/german-newspapers/data/kraken/text/german_newspapers_topologies/htru)|Kraken|Text recognition|Kraken model with htru topology for german newspapers trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/kraken/text/german_newspapers/german_newspapers_htru.mlmodel" download>Download</a>
[German newspapers](data/german-newspapers/data/kraken/text/german_newspapers_topologies/gpt)|Kraken|Text recognition|Kraken model with gpt topology for german newspapers trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/kraken/text/german_newspapers/german_newspapers_gpt.mlmodel" download>Download</a>
[German newspapers](data/german-newspapers/data/kraken/text/german_newspapers)|Kraken|Text recognition|Kraken (default) model for german newspapers trained from several datasets. See https://github.com/UB-Mannheim/kraken/wiki/Training-German-Print|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/kraken/text/german_newspapers/german_newspapers.mlmodel" download>Download</a>
[German newspapers](data/german-newspapers/data/tesseract/best/german_newspapers)|Tesseract|Text recognition|OCR model for german newspapers trained from several datasets. Best model variant for Tesseract. See https://github.com/UB-Mannheim/kraken/wiki/Training-german-newspapers|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/tesseract/best/german_newspapers/german_newspapers_2023.traineddata" download>Download</a>
[German newspapers](data/german-newspapers/data/tesseract/fast/german_newspapers)|Tesseract|Text recognition|OCR model for german newspapers trained from several datasets. Fast model variant for Tesseract. See https://github.com/UB-Mannheim/kraken/wiki/Training-german-newspapers|<a href="https://github.com/JKamlah/german-newspapers-ocr-model/tree/main/data/tesseract/fast/german_newspapers/german_newspapers_2023.traineddata" download>Download</a>
[UBMA Segmentation](data/ubma-segmentation/data/kraken/layout/ubma_segmentation)|Kraken|Layout analysis|Kraken segmentation model for a wide range of materials.|<a href="https://github.com/JKamlah/ubma-segmentation-ocr-model/blob/main/data/kraken/layout/ubma_segmentation/ubma_segmentation.mlmodel" download>Download</a>
[Historical Reports 2col](data/historical-reports-2col/data/kraken/layout/historical_reports_2col)|Kraken|Layout analysis|A Kraken segmentation model for 2 column layout.|<a href="https://github.com/JKamlah/historical-reports-2col-ocr-model/blob/main/data/kraken/layout/historical_reports_2col/historical_reports_2col.mlmodel" download>Download</a>

<!-- /Models !-->


## License
See the LICENSE file in the repository for more details.

## Contact
For any queries or suggestions, feel free to open an issue in this repository, or contact us at [OCR-Helpdesk](jan.kamlah@uni-mannheim.de).
Thank you for exploring our OCR Models Collection. We hope this repository aids you in your text recognition projects and research!

            
           





  
