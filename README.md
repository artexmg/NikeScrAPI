# NikeScrAPI class

## Scrape Nike Website

This class is highly configurable, look the options to set it up correctly
The results are stored in a predefined file
Intermediate results for each shoe category are stored in temporary files

ussage:

```
nikeAPI = NikeScrAPI(max_pages=300,
                     get_description=True,
                     path='data')
```
