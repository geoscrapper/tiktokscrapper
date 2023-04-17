# tiktokscrapper
 TikTok Scraper. Download video posts, collect/check  phone number/user/trend/hashtag/music feed metadata, sign URL and etc. 


Features
    Check , Brute force Phone numbers , Usernames
    Download unlimited post metadata from the User, Hashtag, Trends, or Music-Id pages
    Save post metadata to the JSON/CSV files
    Download media with and without the watermark and save to the ZIP file
    Download single video without the watermark from the CLI
    Sign URL to make custom request to the TikTok API
    Extract metadata from the User, Hashtag and Single Video pages
    Save previous progress and download only new videos that weren't downloaded before. This feature only works from the CLI and only if download flag is on.
    View and manage previously downloaded posts history in the CLI
    Scrape and download user, hashtag, music feeds and single videos specified in the file in batch mode
    
    

Installation

 git clone https://github.com/geoscrapper/tiktokscrapper

 pip install tiktokthon==0.1




USAGE



 In Terminal
 $ tiktok-scraper --help
 $ tiktok-scraper check --phone --username=@ahmedshah
 ...phone -> 19235564445
