# Alura Data miner
Crawls and Scrap all videos from a fomation you want and download in batch(downloading is optional).  
Attention, you need to be a paid member to work. And nope, I didn't code anything to treat errors like wrong username/password or link yet.

By the way, the links for the video resets daily. Pay attention when downloading.

# # Alura Data miner Documentation
AluraLogin:  
-Login on the site. Only needed to crawl and scrap a formation.  
-Uses AluraScraper and AluraCrawler as subclasses, so you only need to create one object.
  
AluraScraper:  
-scraps categories formations from formation page  
-scraps json requests from video links  
-Saves formation categories, formation category, and formations from a category in properties  
usage: AluraScraper.formations, AluraScraper.categories, AluraScraper.category 

AluraCrawler:  
-Choose formation you wanna crawl  
-crawls formation links with video
-Saves link formation and links with video from a formation into properties.
usage: AluraCrawler.link, AulraCrawler.links


# File Parser Documentation
json_decoder():  
  decodes json chunks from a text file
 
get_files():  
  download batch of links from a text file
