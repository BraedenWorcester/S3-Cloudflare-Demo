# Content

This is a static demo website that consists of an index page with an embedded image, an embedded video, and four linked pages (all of which link back to the index page).

# Storage

All web content as seen in this repository is stored on an Amazon S3 bucket, which has been set up to be completely inaccessible to the public.

# Distribution/Access

While the S3 bucket is normally inaccessible, an exception is made for Amazon's CloudFront service, which distributes the web content around the world. 
The website is accessible through https://d1qte0gvgnrpjd.cloudfront.net/ or the insecure http://d1qte0gvgnrpjd.cloudfront.net/. Either URL will return 'index_v2.html', the index page.

# Purpose and Outcome

This project was an attempt to gauge the viability of hosting a static website on S3, and distributing it via CloudFront. With the ease of set up and fast global results, I have determined this to be a resoundingly effective method of getting a static website up and running.
