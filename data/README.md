# data

The `chocolate` data set contains information about chocolate bars and reviews written by experts. It contains 9 variables with 1795 observations. The data contain information about the company who makes the chocolate bars, the percent of cocoa, where the company is located, bean type & origin, and review (out of 5 stars). It comes from the kaggle data set, Chocolate Bar Ratings: Extensive EDA, by Will Canniford. The original data can be found [here](https://www.kaggle.com/code/willcanniford/chocolate-bar-ratings-extensive-eda/data).

## Static_list

Each row corresponds to a unique expert review of a chocolate

| Variable                               | Description                                                                        |
|----------------------------------------|------------------------------------------------------------------------------------|
| `company_maker_if_known`              | Name of the company manufacturing the bar.|
| `specific_bean_origin_or_bar_name`    | The specific geo-region of origin for the bar.|
| `ref`                                 | review ID that corresponds to when the review was entered in the database.|
| `review_date`                         | Date of publication of the review.|
| `cocoa_percent`                       | Cocoa percentage (darkness) of the chocolate bar being reviewed.|
| `company_location`                    | Manufacturer base country.|
| `rating`                              | An Expert's rating of the chocolate bar. Our dependent variable.|
| `bean_type`                           | The variety (breed) of bean used, if provided.|
| `broad_bean_origin`                   | The broad geo-region of origin for the bean.|
