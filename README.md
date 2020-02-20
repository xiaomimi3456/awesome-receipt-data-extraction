# Awesome receipt data extraction

This repository contains resources helpful if you are going to build a system for fiscal receipt data extraction.

## List of documents

| Year    | Type of document | Title, authors                                                                                                                                                                                                                                           | Works on                                                                                 | Dataset, quantity, country of origin                                                                | Receipt detection | Receipt localization | Receipt normalization | Text line segmentation | Optical character recognition | Semantic analysis |
| ------- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ----------------- | -------------------- | --------------------- | ---------------------- | ----------------------------- | ----------------- |
| 2019.09 | Conference Paper | [EATEN: Entity-aware Attention for Single Shot Visual Text Extraction](reviews/guo2019eaten.md)<br/>He Guo, Xiameng Qin, Jiaming Liu, Junyu Han, Jingtuo Liu, Errui Ding                                                                                 | train ticket photos and synthetic images of  train tickets, passports and business cards | EATEN<br/>2000 real train ticket + synth: 300k train ticket + 100k passport + 200k business card    | ❌                 | ❌                    | ❌                     | ❌                      | ❌                             | ✔️                |
| 2019.06 | Preprint         | [CUTIE: Learning to Understand Documents with Convolutional Universal Text Information Extractor](reviews/zhao2019cutie.md)<br/>Xiaohui Zhao, Endi Niu, Zhuo Wu, and Xiaoguang Wang                                                                      | receipts' text from OCR                                                                  | Proprietary<br/>4484, Spain<br/>+<br/>SROIE 2019<br/>1000                                           | ❌                 | ❌                    | ❌                     | ❌                      | ❗                             | ✔️                |
| 2019.06 | Conference Paper | [A Multitask Network for Localization and Recognition of Text in Images](reviews/sarshogh2019multi.md)<br/>Mohammad Reza Sarshogh, Keegan E. Hines                                                                                                       | synthetically-generated documents                                                        | Proprietary<br/>10000                                                                               | ❌                 | ❌                    | ❌                     | ✔️                     | ✔️                            | ❌                 |
| 2019.05 | Conference Paper | [Deep Learning Approach for Receipt Recognition](reviews/le2019deep.md)<br/>Le Duc, Anh & Pham, Dung & Nguyen, Tuan                                                                                                                                      | scanned receipts                                                                         | SROIE 2019<br/>1000                                                                                 | ❌                 | ✔️                   | ❌                     | ✔️                     | ✔️                            | ❌                 |
| 2019.03 | Conference Paper | [Graph Convolution for Multimodal Information Extraction from Visually Rich Documents](reviews/liu2019graph.md)<br/>Xiaojing Liu, Feiyu Gao, Qiong Zhang, Huasha Zhao                                                                                    | receipts' text segments from OCR                                                         | Value-Added Tax Invoices (VATI)<br/>3000<br/>+<br/>International Pur- chase Receipts (IPR)<br/>1500 | ❌                 | ❌                    | ❌                     | ❌                      | ❌                             | ✔️                |
| 2018.03 | Conference Paper | [Optical Character Recognition Engine to extract Food-items and Prices from Grocery Receipt Images via Templating and Dictionary-Traversal Technique](reviews/sohani2018optical.md)<br />Ali Sohani, Rafi Ullah, Faraz Ali, Athaul Rai,  Richard Messier | photos of receipts                                                                       | N/A                                                                                                 | ❌                 | ✔️                   | ✔️                    | ❌                      | ❗                             | ✔️                |
| 2018.02 | Journal Article  | [OCR Engine to Extract Food-Items, Prices, Quantity, Units from Receipt Images, Heuristics Rules Based Approach](reviews/ullah2018ocr.md)<br />Rafi Ullah, Ali Sohani, Athaul Rai, Faraz Ali, Richard Messier                                            | photos of receipts                                                                       | N/A                                                                                                 | ❌                 | ✔️                   | ✔️                    | ❌                      | ❗                             | ✔️                |
| 2018    | BSc thesis       | [Utilize OCR text to extract receipt data and classify receipts with common Machine Learning algorithms](reviews/odd2018utilize.md)<br />Joel Odd, Emil Theologou                                                                                        | photos of receipts                                                                       | Proprietary<br />556, Sweden                                                                        | ❌                 | ❌                    | ❌                     | ❌                      | ❗                             | ✔️                |
| 2018    | Journal Article  | [Preprocessing Photos of Receipts for Recognition](reviews/korobacz2018preprocessing.md)<br/>Wojciech Korobacz, Marek Tabędzki                                                                                                                           | photos of receipts                                                                       | Proprietary<br/>240                                                                                 | ❌                 | ✔️                   | ✔️                    | ❌                      | ❗                             | ❌                 |
| 2017.12 | Conference Paper | [OCR Engine to extract Food-items and Prices from Receipt Images via Pattern matching and heuristics approach](reviews/ullah2017ocr.md)<br />Rafi Ullah, Ali Sohani, Faraz Ali, Athaul Rai                                                               | photos of receipts                                                                       | N/A                                                                                                 | ❌                 | ✔️                   | ✔️                    | ❌                      | ❗                             | ✔️                |
| 2017.10 | Conference Paper | [Deep Learning for automatic sale receipt understanding](reviews/raoui2017deep.md)<br/>Rizlene Raoui-Outach, Cecile Million-Rousseau , Alexandre Benoit and Patrick Lambert                                                                              | photos of receipts                                                                       | Propietary<br/>3000                                                                                 | ✔️                | ✔️                   | ✔️                    | ✔️                     | ❗                             | ❗                 |
| 2015.08 | Journal Article  | [OCR accuracy improvement on document images through a novel pre-processing approach](reviews/harraj2015ocr.md)<br/>Abdeslam El Harraj, Naoufal Raissouni                                                                                                | scanned documents                                                                        | MTDB<br/>500                                                                                        | ❌                 | ❌                    | ✔️                    | ❌                      | ❌                             | ❌                 |
