# `HK2012-2018`
---

| Field | Value |
| --- | --- |
| Title | HK2012-2018 |
| Type | Dataset |
| Language | English |
| License |   |
| Data Status | Static |
| Update Frequency | NO |
| Date Published | 2020-03-20  |
| Date Updated |  2020-03-20 |
| Portal | https://github.com/tulip-lab/open-data |
| URL | https://github.com/tulip-lab/open-data/tree/master/HK2012-2018|
| Publisher |[TULIP Lab](http://www.tulip.org.au/) |
| Point of Contact |[A/Prof. Gang Li](https://github.com/tuliplab) |

The dataset `HK2012-2018` contain the `monthly Hong Kong tourist arrival volumes` and `Search Intensity Indices` (SII) data of six major visitor markets from January 2012 to December 2018: `Australia`,`United Kingdom`,`Philippine`,`Singapore`,`Thailand` and `United States`.

---
### Citations
---

If you use it for a scientific publication, please include a reference to this paper.

* Yishuo Zhang, Gang Li, Birgit Muskat, Rob Law (2020). [Tourism Demand Forecasting: A Decomposed Deep Learning Approach] **Journal of Travel Research**


`BibTex` information:

    @article{ZLML2020,
    title = {Tourism Demand Forecasting: A Decomposed Deep Learning Approach},
    volume = {xx},
    doi = {xxxx},
    journal = {Journal of Travel Research},
    author = {Zhang, Yishuo and Li, Gang and Muskat, Birgit and Law, Rob},
    month = xx,
    year = {2020},
    keywords = {Tourism demand forecasting, tourism planning, AI-based forecasting, deep learning, decomposing method, over-fitting}, 
    }

The related source code for above paper can be found at [TULIP Lab Open-Code](https://github.com/tulip-lab/open-code):

* [`STL-DADLM`](https://github.com/tulip-lab/open-code/tree/master/STL-DADLM): A Deep Learning Package for STL Decomposition Tourism Demand Forecasting

---
### Data Description
---

* The first row is the field name of each column in this dataset.
* The following tables show descriptions for columns in all six data in the `HK2012-2018` Dataset.
* There are total 96 SII features in each data file.
* All the six data has the same feature names which are listed in below.

#### `HK2012-2018` SII data

| No. | Feature Name                               | Description | Data Type |
|-----|--------------------------------------------|-------------|-----------|
| 1   | Date                                       | non-null    | DateTime  |
| 2   | Arrivals                                   | non-null    | Int64     |
| 3   | Hong kong                                  | non-null    | Int64     |
| 4   | Hong kong dollar                           | non-null    | Int64     |
| 5   | Sheung Wan                                 | non-null    | Int64     |
| 6   | Tai Ping Shan Street                       | non-null    | Int64     |
| 7   | Hong kong central                          | non-null    | Int64     |
| 8   | Hong Kong Disneyland                       | non-null    | Int64     |
| 9   | hong kong dollar to rmb                    | non-null    | Int64     |
| 10  | hkd to usd                                 | non-null    | Int64     |
| 11  | Hong Kong cuisine                          | non-null    | Int64     |
| 12  | hong kong food                             | non-null    | Int64     |
| 13  | hong kong yum cha                          | non-null    | Int64     |
| 14  | hong kong best food                        | non-null    | Int64     |
| 15  | hong kong chinese food                     | non-null    | Int64     |
| 16  | hong kong food blog                        | non-null    | Int64     |
| 17  | hong kong hotel                            | non-null    | Int64     |
| 18  | silka hotel hong kong                      | non-null    | Int64     |
| 19  | hotel hong kong kowloon                    | non-null    | Int64     |
| 20  | crowne plaza hong kong kowloon east        | non-null    | Int64     |
| 21  | Grand Hyatt Hong Kong                      | non-null    | Int64     |
| 22  | airbnb                                     | non-null    | Int64     |
| 23  | hong kong accommodation                    | non-null    | Int64     |
| 24  | flights to hong kong                       | non-null    | Int64     |
| 25  | cathay pacific                             | non-null    | Int64     |
| 26  | hong kong to macau travel time             | non-null    | Int64     |
| 27  | hong kong macau ferry                      | non-null    | Int64     |
| 28  | hong kong airport to macau                 | non-null    | Int64     |
| 29  | hong kong ferry terminal                   | non-null    | Int64     |
| 30  | ferry macau to hong kong airport           | non-null    | Int64     |
| 31  | hong kong ferry                            | non-null    | Int64     |
| 32  | hongkong macau                             | non-null    | Int64     |
| 33  | hong kong airport                          | non-null    | Int64     |
| 34  | hong kong airport express                  | non-null    | Int64     |
| 35  | hong kong mtr hours                        | non-null    | Int64     |
| 36  | hong kong Transportation                   | non-null    | Int64     |
| 37  | air asia                                   | non-null    | Int64     |
| 38  | Hong Kong Airlines                         | non-null    | Int64     |
| 39  | agoda hong kong                            | non-null    | Int64     |
| 40  | asia travel hong kong                      | non-null    | Int64     |
| 41  | ocean park hong kong                       | non-null    | Int64     |
| 42  | hong kong map                              | non-null    | Int64     |
| 43  | singapore to hong kong                     | non-null    | Int64     |
| 44  | china mainland to hong kong                | non-null    | Int64     |
| 45  | hong kong light show                       | non-null    | Int64     |
| 46  | skyscanner                                 | non-null    | Int64     |
| 47  | ladies market hong kong opening hours      | non-null    | Int64     |
| 48  | Shopping in Hong Kong                      | non-null    | Int64     |
| 49  | citygate outlet                            | non-null    | Int64     |
| 50  | hong kong shopping festival                | non-null    | Int64     |
| 51  | hong kong casino                           | non-null    | Int64     |
| 52  | what to do in hong kong                    | non-null    | Int64     |
| 53  | nightlife hong kong                        | non-null    | Int64     |
| 54  | hong kong clubs                            | non-null    | Int64     |
| 55  | lan kwai fong                              | non-null    | Int64     |
| 56  | hong kong weather                          | non-null    | Int64     |
| 57  | occupy central                             | non-null    | Int64     |
| 58  | hongkong customs                           | non-null    | Int64     |
| 59  | hong kong cheap flight                     | non-null    | Int64     |
| 60  | Avenue of Stars                            | non-null    | Int64     |
| 61  | travel Tsim Sha Tsui                       | non-null    | Int64     |
| 62  | hong kong dollar to                        | non-null    | Int64     |
| 63  | hong kong currency                         | non-null    | Int64     |
| 64  | hong kong restaurant                       | non-null    | Int64     |
| 65  | hong kong travel                           | non-null    | Int64     |
| 66  | travel to Hong Kong                        | non-null    | Int64     |
| 67  | hong kong michelin                         | non-null    | Int64     |
| 68  | hong kong hotel central                    | non-null    | Int64     |
| 69  | hong kong hotel central.1                  | non-null    | Int64     |
| 70  | hong kong macao                            | non-null    | Int64     |
| 71  | hong kong asian                            | non-null    | Int64     |
| 72  | Hong Kong television drama                 | non-null    | Int64     |
| 73  | thai to hong kong                          | non-null    | Int64     |
| 74  | macau to hong kong                         | non-null    | Int64     |
| 75  | china hong kong                            | non-null    | Int64     |
| 76  | map hong kong                              | non-null    | Int64     |
| 77  | taiwan hong kong                           | non-null    | Int64     |
| 78  | japan hong kong                            | non-null    | Int64     |
| 79  | korea hong kong                            | non-null    | Int64     |
| 80  | mobile hong kong                           | non-null    | Int64     |
| 81  | eat hong kon                               | non-null    | Int64     |
| 82  | US hong kong                               | non-null    | Int64     |
| 83  | UK hong kong                               | non-null    | Int64     |
| 84  | shopping hong kong                         | non-null    | Int64     |
| 85  | street hong kong                           | non-null    | Int64     |
| 86  | price hong kong                            | non-null    | Int64     |
| 87  | ticket hong kong                           | non-null    | Int64     |
| 88  | train hong kong                            | non-null    | Int64     |
| 89  | bus hong kong                              | non-null    | Int64     |
| 90  | taxi hong kong                             | non-null    | Int64     |
| 91  | holiday hong kong                          | non-null    | Int64     |
| 92  | festival hong kong                         | non-null    | Int64     |
| 93  | hot hong kong                              | non-null    | Int64     |
| 94  | temperature hong kong                      | non-null    | Int64     |
| 95  | bar hong kong                              | non-null    | Int64     |
| 96  | air asia Hong Kong                         | non-null    | Int64     |
| 97  | Yum cha                                    | non-null    | Int64     |
| 98  | Hong Kong Convention and Exhibition Centre | non-null    | Int64     |


