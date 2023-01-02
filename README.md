# NikeScrAPI class
Author: Artemio Mendoza

## Scrape Nike Website

This class is highly configurable, look the options to set it up correctly
The results are stored in a predefined file
Intermediate results for each shoe category are stored in temporary files

ussage:

```
# instantiate class
nikeAPI = NikeScrAPI(max_pages=300,
                     get_description=True,
                     path='data')
                   
# scrape data into pandas framework
nike = nikeAPI.getData()
```

Note: it will download all products listed in nike.com website, not only shoes. 
The shoe products are filtered out with:

```python
item['productType'] == 'FOOTWEAR'
```
