# data

The `chocolate` data set contains information about chocolate bars and reviews written by experts. It contains 9 variables with 1795 observations. The data contain information about the company who makes the chocolate bars, the percent of cocoa, where the company is located, bean type & origin, and review (out of 5 stars). It comes from the kaggle data set, Chocolate Bar Ratings: Extensive EDA, by Will Canniford. The original data can be found [here](https://www.kaggle.com/code/willcanniford/chocolate-bar-ratings-extensive-eda/data).

## Static_list

Each row corresponds to a unique expert review of a chocolate.

| Variable                               | Description                                                                        |
|----------------------------------------|------------------------------------------------------------------------------------|
| `Company \n(Maker-if known)`            | Name of the company manufacturing the bar.|
| `Specific Bean Origin\nor Bar Name"`   | The specific geo-region of origin for the bar.|
| `REF`                                 | review ID that corresponds to when the review was entered in the database.|
| `Review\nDate`                         | Date of publication of the review.|
| `Cocoa\nPercent`                       | Cocoa percentage (darkness) of the chocolate bar being reviewed.|
| `Company\nLocation`                    | Manufacturer base country.|
| `Rating`                              | An Expert's rating of the chocolate bar. Our dependent variable.|
| `Bean\nType`                           | The variety (breed) of bean used, if provided.|
| `Broad Bean\nOrigin`                   | The broad geo-region of origin for the bean.|
