# Content

This is a static demo website that consists of an index page with an embedded image, an embedded video, and four linked pages (all of which link back to the index page).

# Storage

All web content as seen in this repository is stored on an Amazon S3 bucket, which has been set up to be completely inaccessible to the public.

# Distribution/Access

While the S3 bucket is normally inaccessible, an exception is made for Amazon's CloudFront service, which distributes the web content content globally. 
The website is accessible through https://d1qte0gvgnrpjd.cloudfront.net/ or the insecure http://d1qte0gvgnrpjd.cloudfront.net/. Either URL will return 'index_v2.html', the index page.
