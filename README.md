# Mobile App Statistics (Apple iOS app store)

__Analytics for Mobile Apps__

The ever-changing mobile landscape is a challenging space to navigate. . The percentage of mobile over desktop is only increasing. Android holds about 53.2% of the smartphone market, while iOS is 43%. To get more people to download your app, you need to make sure they can easily find your app. Mobile app analytics is a great way to understand the existing strategy to drive growth and retention of future user.

With million of apps around nowadays, the following data set has become very key to getting top trending apps in iOS app store. This data set contains more than 7000 Apple iOS mobile application details. The data was extracted from the iTunes Search API at the Apple Inc website. R and linux web scraping tools were used for this study.

Data collection date (from API); July 2017

Dimension of the data set; 7197 rows and 16 columns

## Content:

__appleStore.csv__

1. "id" : App ID
2. "track_name": App Name
3. "size_bytes": Size (in Bytes)
4. "currency": Currency Type
5. "price": Price amount
6. "rating_count_tot": User Rating counts (for all version)
7. "rating_count_ver": User Rating counts (for current version)
8. "user_rating" : Average User Rating value (for all version)
9. "user_rating_ver": Average User Rating value (for current version)
10. "ver" : Latest version code
11. "cont_rating": Content Rating
12. "prime_genre": Primary Genre
13. "sup_devices.num": Number of supporting devices
14. "ipadSc_urls.num": Number of screenshots showed for display
15. "lang.num": Number of supported languages
16. "vpp_lic": Vpp Device Based Licensing Enabled

__appleStore_description.csv__

1. id : App ID
2. track_name: Application name
3. size_bytes: Memory size (in Bytes)
4. app_desc: Application description

__Acknowledgements__

The data was extracted from the iTunes Search API at the Apple Inc website. R and linux web scraping tools were used for this study.

__Inspiration__

How does the App details contribute the user ratings?
Try to compare app statistics for different groups?
Reference: R package From github, with devtools::install_github("ramamet/applestoreR")

__Licence__

Copyright (c) 2018 Ramanathan Perumal

<https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps>
