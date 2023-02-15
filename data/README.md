# Data

## Data Descriptions

The `chocolate` data set contains information about chocolate bars and reviews written by experts. It contains 9 variables with 1795 observations. The data contain information about the company who makes the chocolate bars, the percent of cocoa, where the company is located, bean type & origin, and review (out of 5 stars). It comes from the kaggle data set, Chocolate Bar Ratings: Extensive EDA, by Will Canniford. The original data can be found [here](https://www.kaggle.com/code/willcanniford/chocolate-bar-ratings-extensive-eda/data).

The second data set, `con2cont`, contains information about different countries and the continents and sub-regions they are located in, their official nomenclature, and country/regional codes. The data set has 9 columns and 249 rows with each row representing a country. Since we are grouping the company locations with their continents, we only select the variables that contain information about the country names and the continent they are located in to be used in our analysis. The data comes from Kaggle and the original data can be found in this [link](https://www.kaggle.com/datasets/statchaitya/country-to-continent).

The third data set, `world`, contains the necessary coordinates for plotting respective countries. It comes from the `maps` package and lists the points required to be connected to create all the countries.


### Data Set 1: chocolate

Name in repo: `/project-01-o_ggs/data/flavors_of_cacao[1].csv`

Each row corresponds to a unique expert review of a chocolate.

| Variable                               | Description                                                                        |
|----------------------------------------|------------------------------------------------------------------------------------|
| `Company \n(Maker-if known)`           | Name of the company manufacturing the bar.|
| `Specific Bean Origin\nor Bar Name`    | The specific geo-region of origin for the bar.|
| `REF`                                  | review ID that corresponds to when the review was entered in the database.|
| `Review\nDate`                         | Date of publication of the review.|
| `Cocoa\nPercent`                       | Cocoa percentage (darkness) of the chocolate bar being reviewed.|
| `Company\nLocation`                    | Manufacturer base country.|
| `Rating`                               | An Expert's rating of the chocolate bar. Our dependent variable.|
| `Bean\nType`                           | The variety (breed) of bean used, if provided.|
| `Broad Bean\nOrigin`                   | The broad geo-region of origin for the bean.|

### Data Set 2: con2cont

Name in repo: `/project-01-o_ggs/data/countryContinent.csv`

Each row corresponds to a unique country and it's general information.

| Variable                               | Description                                                                        |
|----------------------------------------|------------------------------------------------------------------------------------|
| `country`                              | Name of the country |
| `code_2`                               | Official, abbreviated name of the country, expressed in 2 letters |
| `code_3`                               | Official, abbreviated name of the country, expressed in 3 letters |
| `country_code`                         | Country code of the country|
| `iso_3166_2`                           | Internationally recognized codes of letters and/or numbers used to refer to countries expressed in 2 letters |
| `continent`                            | Continent the country is located in |
| `sub_region`                           | Sub-region the country is located in |
| `region_code`                          | Numeric region code of the country |
| `sub_region_code`                      | Numeric sub-region code of the country |

### Data Set 3: world

Each row corresponds to a unique point in the polygon that makes up a country.

| Variable                               | Description                                                                        |
|----------------------------------------|------------------------------------------------------------------------------------|
| `long`                                 | The longitude of the coordinates for one point of the polygon|
| `lat`                                  | The latitude of the coordinates for one point of the polygon|
| `group`                                | The number of the country which the point belongs to, alphabetically|
| `order`                                | The order in the list the point is|
| `region`                               | The name of the country the point belongs to|
| `subregion`                            | The sub-region of the country, if applicable, the point belongs to|