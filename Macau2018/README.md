## About the Dataset
---

This dataset contains the `monthly tourist arrival volumes` and `Search Intensity Indices` (SII) data of `Macau` from January 2011 to August 2018. There are 259 features in total:

* The first column is the date
* The second and the third columns are the arrival data
* The column (#4-#214) are 211 related keywords are obtained from [Google Trends](https://trends.google.com) and 
* The rest 45 columns are keywords collected from [Baidu Index](https://zhishu.baidu.com).

The mainland China and global monthly  tourist arrival volumes for Macau were collected from [Statistics and Census Services（DSEC）](https://www.dsec.gov.mo/Statistic.aspx?NodeGuid=251baebb-6e5b-4452-8ad1-7768eafc99ed) of the Macau government, while those Search Intensity Indices (SII) data were collected from [Google Trends](https://trends.google.com) and [Baidu Index](https://zhishu.baidu.com) using a developed tool.

---
### **Additional information**
---


| Field | Value |
| --- | --- |
| Title | Macau2018 |
| Type | Dataset |
| Language | English & Chinese (Simplified) |
| License |   |
| Data Status | static |
| Update Frequency | annually |
| Date Published | 2019-1-14  |
| Date Updated |  2018-9-27 |
| Portal | https://github.com/tulip-lab/open-data/Macau2018 |
| Publisher |[TULIP Lab](http://www.tulip.org.au/) |




---
### Citations
---

If you use it for a scientific publication, please include a reference to this paper. 

* Rob Law, Gang Li, Davis Fong, Xin Han (2019). Tourism Demand Forecasting: A Deep Learning Approach. Annals of Tourism Research

`BibTex` information:

    @article{LLFHDeep2019,
    title = {Tourism Demand Forecasting: A Deep Learning Approach},
    volume = {XX},
    issn = {XXX-XX},
    doi = {xxxxxx},
    journal = {Annals of Tourism Research},
    author = {Law, Rob and Li, Gang and Fong, Davis and Han, Xin},
    month = xxx,
    year = {2019},
    keywords = {Big data analytics,Deep Learning,Search query data,Tourism demand forecast},
    pages = {XX-XX},
    }

You can feel free to use the datasets (for academic purpose only) at your own risk. For other purposes, please contact **A/Prof. Gang Li** (gangli AT tulip.org.au).


---
### Data Description
---


The following tables show all features in Macau2018 Dataset.

#### Date & Arrival data

| No. | Feature Name | Description | Data Type |
|---|---|---|---|
| 1 | Date | non-null | object |
| 2 | Arrival (Mainland China) | non-null | int64 |
| 3 | Arrival (Global) | non-null | int64 |

 ####  Features from `Google Trends`.

| No. | Feature Name                      | Description | Data Type | No. | Feature Name                     | Description | Data Type |
|-----|-----------------------------------|-------------|-----------|-----|----------------------------------|-------------|-----------|
| 4   | Hong Kong casino                  | non-null    | int64     | 110 | banyan tree macau                | non-null    | int64     |
| 5   | Shows in Macau                    | non-null    | int64     | 111 | macau cheap flights              | non-null    | int64     |
| 6   | Singapore to Macau                | non-null    | int64     | 112 | venetian hotel                   | non-null    | int64     |
| 7   | Macau Airlines                    | non-null    | int64     | 113 | macau food blog                  | non-null    | int64     |
| 8   | Macau on map                      | non-null    | int64     | 114 | macau tourism board              | non-null    | int64     |
| 9   | Tiger Airways                     | non-null    | int64     | 115 | hong kong travel                 | non-null    | int64     |
| 10  | Cathay Pacific                    | non-null    | int64     | 116 | flights to macau from singapore  | non-null    | int64     |
| 11  | Show in Macau                     | non-null    | int64     | 117 | mgm                              | non-null    | int64     |
| 12  | Macau Venetian                    | non-null    | int64     | 118 | city of dreams                   | non-null    | int64     |
| 13  | Galaxy Macau Hotel                | non-null    | int64     | 119 | macau tour package               | non-null    | int64     |
| 14  | Macau grand hotel                 | non-null    | int64     | 120 | macau travel blog                | non-null    | int64     |
| 15  | Macau Tauranga                    | non-null    | int64     | 121 | macau gaming show                | non-null    | int64     |
| 16  | casino in Macau                   | non-null    | int64     | 122 | the house of dancing water       | non-null    | int64     |
| 17  | mgm macau                         | non-null    | int64     | 123 | weather hk                       | non-null    | int64     |
| 18  | macau ferry terminal              | non-null    | int64     | 124 | hong kong disneyland             | non-null    | int64     |
| 19  | macau restaurant jamaica          | non-null    | int64     | 125 | hong kong macau map              | non-null    | int64     |
| 20  | macao                             | non-null    | int64     | 126 | macau time                       | non-null    | int64     |
| 21  | map of hong kong                  | non-null    | int64     | 127 | hong kong ferry                  | non-null    | int64     |
| 22  | macau food festival               | non-null    | int64     | 128 | air asia                         | non-null    | int64     |
| 23  | cheap flights                     | non-null    | int64     | 129 | macau weather today              | non-null    | int64     |
| 24  | hong kong to macau travel time    | non-null    | int64     | 130 | weather singapore                | non-null    | int64     |
| 25  | venetian hotel macau              | non-null    | int64     | 131 | best hotel macau                 | non-null    | int64     |
| 26  | macau nightlife                   | non-null    | int64     | 132 | sands casino                     | non-null    | int64     |
| 27  | royal hotel                       | non-null    | int64     | 133 | halal food in macau              | non-null    | int64     |
| 28  | macau ferry schedule              | non-null    | int64     | 134 | macau show bar                   | non-null    | int64     |
| 29  | cebu pacific                      | non-null    | int64     | 135 | lisboa casino                    | non-null    | int64     |
| 30  | jetstar                           | non-null    | int64     | 136 | hotel lisboa macau               | non-null    | int64     |
| 31  | thailand                          | non-null    | int64     | 137 | singapore                        | non-null    | int64     |
| 32  | flights to hong kong              | non-null    | int64     | 138 | from hong kong to macau          | non-null    | int64     |
| 33  | macau food                        | non-null    | int64     | 139 | venetian casino macau            | non-null    | int64     |
| 34  | macau hotel venetian              | non-null    | int64     | 140 | shopping in hong kong            | non-null    | int64     |
| 35  | hotel in macau                    | non-null    | int64     | 141 | venetian macau casino            | non-null    | int64     |
| 36  | flights to macau                  | non-null    | int64     | 142 | shopping in macau                | non-null    | int64     |
| 37  | hong kong macau ferry             | non-null    | int64     | 143 | macau food festival 2014         | non-null    | int64     |
| 38  | weather in macau                  | non-null    | int64     | 144 | singapore airlines               | non-null    | int64     |
| 39  | macau restaurant menu             | non-null    | int64     | 145 | hong kong tourism                | non-null    | int64     |
| 40  | macau weather                     | non-null    | int64     | 146 | venetian macau                   | non-null    | int64     |
| 41  | wing on travel                    | non-null    | int64     | 147 | macau shopping mall              | non-null    | int64     |
| 42  | china map                         | non-null    | int64     | 148 | macau shopping guide             | non-null    | int64     |
| 43  | macaulay culkin                   | non-null    | int64     | 149 | ferry macau to hong kong airport | non-null    | int64     |
| 44  | taboo show macau                  | non-null    | int64     | 150 | hk to macau                      | non-null    | int64     |
| 45  | dancing water show macau schedule | non-null    | int64     | 151 | macau food guide                 | non-null    | int64     |
| 46  | best food in macau                | non-null    | int64     | 152 | hong kong weather                | non-null    | int64     |
| 47  | hotel macau                       | non-null    | int64     | 153 | casino lisboa macau              | non-null    | int64     |
| 48  | agoda                             | non-null    | int64     | 154 | world map                        | non-null    | int64     |
| 49  | macau hotel                       | non-null    | int64     | 155 | hong kong to macau ferry         | non-null    | int64     |
| 50  | hongkong                          | non-null    | int64     | 156 | macau hotels                     | non-null    | int64     |
| 51  | asia travel                       | non-null    | int64     | 157 | macau food festival 2017         | non-null    | int64     |
| 52  | city of dreams macau              | non-null    | int64     | 158 | air macau                        | non-null    | int64     |
| 53  | hong kong airport to macau        | non-null    | int64     | 159 | macau things to do               | non-null    | int64     |
| 54  | hong kong airport to macau ferry  | non-null    | int64     | 160 | google flights                   | non-null    | int64     |
| 55  | dancing water macau               | non-null    | int64     | 161 | hotel lisboa                     | non-null    | int64     |
| 56  | macau magic show                  | non-null    | int64     | 162 | macau china                      | non-null    | int64     |
| 57  | china                             | non-null    | int64     | 163 | google map                       | non-null    | int64     |
| 58  | weather hong kong                 | non-null    | int64     | 164 | what to do in macau              | non-null    | int64     |
| 59  | macau portuguese restaurant       | non-null    | int64     | 165 | wing on travel macau             | non-null    | int64     |
| 60  | best food in hong kong            | non-null    | int64     | 166 | macau food festival 2012         | non-null    | int64     |
| 61  | macau china weather               | non-null    | int64     | 167 | weather in hong kong             | non-null    | int64     |
| 62  | macau gaming lounge & bar         | non-null    | int64     | 168 | galaxy casino                    | non-null    | int64     |
| 63  | galaxy macau                      | non-null    | int64     | 169 | hongkong tourism                 | non-null    | int64     |
| 64  | hong kong ferry to macau          | non-null    | int64     | 170 | hong kong to macau               | non-null    | int64     |
| 65  | ferry terminal                    | non-null    | int64     | 171 | wynn casino                      | non-null    | int64     |
| 66  | hong kong light show              | non-null    | int64     | 172 | macao restaurant                 | non-null    | int64     |
| 67  | travel to macau                   | non-null    | int64     | 173 | macau city                       | non-null    | int64     |
| 68  | macau chinese restaurant          | non-null    | int64     | 174 | macau light show                 | non-null    | int64     |
| 69  | hk to macau ferry                 | non-null    | int64     | 175 | map of macau                     | non-null    | int64     |
| 70  | casinos macau                     | non-null    | int64     | 176 | macau weather december           | non-null    | int64     |
| 71  | macau tourism                     | non-null    | int64     | 177 | house of dancing water           | non-null    | int64     |
| 72  | macau shows                       | non-null    | int64     | 178 | macau airport                    | non-null    | int64     |
| 73  | indian restaurant in macau        | non-null    | int64     | 179 | hongkong macau ferry             | non-null    | int64     |
| 74  | hong kong macau                   | non-null    | int64     | 180 | macau restaurant tauranga        | non-null    | int64     |
| 75  | bangkok                           | non-null    | int64     | 181 | ferry to macau                   | non-null    | int64     |
| 76  | super show 4 macau                | non-null    | int64     | 182 | macau hk ferry                   | non-null    | int64     |
| 77  | hong kong airport                 | non-null    | int64     | 183 | travel agency                    | non-null    | int64     |
| 78  | restaurant in macau               | non-null    | int64     | 184 | wynn macau                       | non-null    | int64     |
| 79  | macau food festival 2015          | non-null    | int64     | 185 | macau food festival 2016         | non-null    | int64     |
| 80  | macau restaurants                 | non-null    | int64     | 186 | macau casino                     | non-null    | int64     |
| 81  | best restaurant in macau          | non-null    | int64     | 187 | macau island                     | non-null    | int64     |
| 82  | macau water show                  | non-null    | int64     | 188 | restaurants in macau             | non-null    | int64     |
| 83  | china travel                      | non-null    | int64     | 189 | macau ferry                      | non-null    | int64     |
| 84  | macau travel guide                | non-null    | int64     | 190 | ferry macau hong kong            | non-null    | int64     |
| 85  | galaxy casino macau               | non-null    | int64     | 191 | macau ferry terminal hong kong   | non-null    | int64     |
| 86  | openrice                          | non-null    | int64     | 192 | hongkong map                     | non-null    | int64     |
| 87  | hong kong shopping                | non-null    | int64     | 193 | macau ferry from hong kong       | non-null    | int64     |
| 88  | hongkong weather                  | non-null    | int64     | 194 | macau ferry terminal map         | non-null    | int64     |
| 89  | good food in macau                | non-null    | int64     | 195 | ozone bar hong kong              | non-null    | int64     |
| 90  | hong kong hotel                   | non-null    | int64     | 196 | galaxy hotel                     | non-null    | int64     |
| 91  | macau restaurant hong kong        | non-null    | int64     | 197 | iifa awards 2013 macau full show | non-null    | int64     |
| 92  | hongkong macau                    | non-null    | int64     | 198 | macau galaxy                     | non-null    | int64     |
| 93  | weather in macau in december      | non-null    | int64     | 199 | macau map                        | non-null    | int64     |
| 94  | weather forecast                  | non-null    | int64     | 200 | hotel in hong kong               | non-null    | int64     |
| 95  | accommodation in macau            | non-null    | int64     | 201 | weather forecast hong kong       | non-null    | int64     |
| 96  | cheap flights to macau            | non-null    | int64     | 202 | macau world map                  | non-null    | int64     |
| 97  | venetian macau shopping           | non-null    | int64     | 203 | venetian casino                  | non-null    | int64     |
| 98  | agoda macau                       | non-null    | int64     | 204 | airasia                          | non-null    | int64     |
| 99  | hong kong                         | non-null    | int64     | 205 | macau package                    | non-null    | int64     |
| 100 | macau currency                    | non-null    | int64     | 206 | hong kong map                    | non-null    | int64     |
| 101 | macau shopping festival           | non-null    | int64     | 207 | grand macau casino               | non-null    | int64     |
| 102 | iifa awards 2013 full show        | non-null    | int64     | 208 | hong kong ferry terminal         | non-null    | int64     |
| 103 | hong kong weather forecast        | non-null    | int64     | 209 | macau tower                      | non-null    | int64     |
| 104 | venetian                          | non-null    | int64     | 210 | bali                             | non-null    | int64     |
| 105 | heart bar macau                   | non-null    | int64     | 211 | macau hong kong                  | non-null    | int64     |
| 106 | galaxy                            | non-null    | int64     | 212 | macao casino                     | non-null    | int64     |
| 107 | weather forecast in macau         | non-null    | int64     | 213 | food festival macau              | non-null    | int64     |
| 108 | halal food in hong kong           | non-null    | int64     | 214 | skyscanner                       | non-null    | int64     |
| 109 | food in macau                     | non-null    | int64     |     |                                  |             |           |

#### Features from `Baidu Index`.

| No. | Feature Name    | Description | Data Type | No. | Feature Name     | Description | Data Type |
|-----|-----------------|-------------|-----------|-----|------------------|-------------|-----------|
| 215 | AGODA           | non-null    | int64     | 238 | 澳门旅游景点大全 | non-null    | int64     |
| 216 | macaulay culkin | non-null    | int64     | 239 | 澳门机场         | non-null    | int64     |
| 217 | Skyscanner      | non-null    | int64     | 240 | 澳门美食         | non-null    | int64     |
| 218 | 中国地图        | non-null    | int64     | 241 | 澳门美食地图     | non-null    | int64     |
| 219 | 亚洲旅行        | non-null    | int64     | 242 | 澳门美食节       | non-null    | int64     |
| 220 | 亚洲航空        | non-null    | int64     | 243 | 澳门航空         | non-null    | int64     |
| 221 | 亚航            | non-null    | int64     | 244 | 澳门赌场         | non-null    | int64     |
| 222 | 国泰航空        | non-null    | int64     | 245 | 澳门酒店         | non-null    | int64     |
| 223 | 威尼斯人酒店    | non-null    | int64     | 246 | 澳门银河         | non-null    | int64     |
| 224 | 威尼斯赌场      | non-null    | int64     | 247 | 米高梅           | non-null    | int64     |
| 225 | 巴里            | non-null    | int64     | 248 | 谷歌地图         | non-null    | int64     |
| 226 | 捷星航空        | non-null    | int64     | 249 | 轮渡码头         | non-null    | int64     |
| 227 | 新加坡天气      | non-null    | int64     | 250 | 香港             | non-null    | int64     |
| 228 | 梦想之城        | non-null    | int64     | 251 | 香港到澳门       | non-null    | int64     |
| 229 | 泰国            | non-null    | int64     | 252 | 香港地图         | non-null    | int64     |
| 230 | 澳门            | non-null    | int64     | 253 | 香港天气         | non-null    | int64     |
| 231 | 澳门住宿        | non-null    | int64     | 254 | 香港天气预报     | non-null    | int64     |
| 232 | 澳门住宿攻略    | non-null    | int64     | 255 | 香港旅游         | non-null    | int64     |
| 233 | 澳门地图        | non-null    | int64     | 256 | 香港机场         | non-null    | int64     |
| 234 | 澳门塔          | non-null    | int64     | 257 | 香港购物         | non-null    | int64     |
| 235 | 澳门天气        | non-null    | int64     | 258 | 香港赌场         | non-null    | int64     |
| 236 | 澳门威尼斯人    | non-null    | int64     | 259 | 香港酒店         | non-null    | int64     |
| 237 | 澳门币          | non-null    | int64     |     |                  |             |           |

