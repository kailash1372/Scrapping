# Scrapping
Web Scrapping Restaurants Menu and Modifiers
-Web Scrapping using website's APIs and optimizing it.
## Steps:
Moniter the website's network requests, use the find tool to search for a item name sometimes it's not that easy as using the find tool.
after finding the api curvert the cUrl using curlconverter into python code, this can then be used to identify the variables required to change them to get data for all stores.
these apis genrally return data in json format, we can convert these into python dictionary and them decode them to obtain the necessary data.
right now we can just use traditional loop to get data for all the stores but it's important to understand that we might be making anywhere from 100-500000 requests, so traditional loop would take forever to complete these requests, enter async|multi-threading, using either of the techniques we can make utilize all the cores of our cpu at once ensuring we are using all the resources we have to complete our tasks faster.
