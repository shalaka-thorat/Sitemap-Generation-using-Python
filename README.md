# Sitemap-Generation-using-Python
Creating Sitemap Files for a website using Python

<img src="Screenshots/1_UzKrCwQ5jRaBvjV7eaEhJA.png">

### What is Sitemap:
A sitemap is a file that provides information about pages, images, videos included on your website.<br>
Sitemaps are used by search engines like Google for efficient crawling.<br>

There are various sitemap formats such as XML, RSS, Text. XML sitemap format is popularly used and is thus demostrated in this project.<br>

### Use of Sitemap:
A sitemap is used to provide specific information about your website namely, webpages, images on the webpages.<br>
For example:<br>
A video sitemap will provide information about the video location, video title, rating and much more.<br>
An image sitemap will include the location of the images included in a specific webpage.<br>

### Types of Sitemap:
Following are the 3 types of sitemaps used widely:<br>

URL Sitemap (Basic Sitemap that most websites use)<br>
Image Sitemap<br>
Video Sitemap<br>

### Sample XML Sitemap:

\<?xml version="1.0" encoding="UTF-8"?><br>
\<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"><br>
    &emsp;\<url><br>
        &emsp;&emsp;\<loc> http://www.abc.com/ \</loc><br>
        &emsp;&emsp;\<lastmod> 2022-09-01 \</lastmod><br>
        &emsp;&emsp;\<changefreq> daily \</changefreq><br>
        &emsp;&emsp;\<priority> 0.9 \</priority>  <br>
    &emsp;\</url><br>
\</urlset>

### Contents of the Project:

Sitemap-Generation.ipynb: It is a Jupyter Notebook that explains how you can construct a basic sitemap for website and other sitemap variants as well. For demonstration, we have crawled Udemy homepage and constructed sitemap files using the URLs.<br>

Sample Sitemap Files: This folder contains all the generated sitemap files, when the above notebook is run.<br>

robots.txt: It is a file in which sitemap / sitemap index file path needs to be mentioned in order to let the crawler know he location.<br>

Screenshots: This folder contains snaps of sitemap file and sitemap_index file generated through the program. It also contains snaps of robots.txt in which how one can include the sitemap file paths.<br>

To access the Sitemap Generation code, click <a href="https://github.com/shalaka-thorat/Sitemap-Generation-using-Python/blob/main/Sitemap-Generation.ipynb">Here</a>
    
## References:

1) Sitemap: https://www.sitemaps.org/protocol.html
2) Splitting Sitemaps and Constructing Sitemap Index: https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview
3) Image Sitemap: https://developers.google.com/search/docs/crawling-indexing/sitemaps/image-sitemaps
4) Video Sitemap: https://developers.google.com/search/docs/crawling-indexing/sitemaps/video-sitemaps

## 
<br>
<img src="Screenshots/sitemap_img.jpg" height="400" width="600">
