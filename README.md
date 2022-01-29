# What i tried to accomplish
1. I tried to cache static images from the /dw/image/v2 route.
2. I was able to implement deep fetching an prefetching for the Product Description Pages by matching the routes under the various categories
3. I was able to implement deep fetching of the images on the Product description pages by finding the classnames and then appended the deepFetch object to the existing ones that deep fetched images of the Product description pages


# Feedback to layer0
I had a great time working with your service, however , being a first time layer0 user i found it a little challenging trying to go by the documentation. 


# Part 2 - Performance comparison 
After running all the test required to run:

The site i deployed recorded a largest contentful paint after 2.687s  with total blocking time of less than 5.035s and also 0 cumilative shift. I was also able to achieve 2.600s Start render time after the optimizations which beat the orignal site's 3.900s start render time. On the other hand, the original site's largest contentful paint happened after 3.896s with total blocking time of less than 4.122s.
