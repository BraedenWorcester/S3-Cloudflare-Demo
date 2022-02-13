# Content

This is a static demo website that consists of an index page with an embedded image, an embedded video, and four linked pages (all of which link back to the index page).

# Storage

All web content as seen in this repository is stored on an Amazon S3 bucket, which can be accessed from http://cs4843-ass1-bucket-hva124.s3-website-us-east-1.amazonaws.com. The bucket is configured to only allow "GetObject" requests from the public, and will otherwise deny access.

# Distribution

While the website is hosted through S3, Amazon's CloudFront service distributes the content around the world. This allows it to be generally accessed faster from this url: https://d1qte0gvgnrpjd.cloudfront.net/, regardless of location.

# Purpose and Outcome

This project was an attempt to gauge the viability of hosting a static website on S3, and distributing it via CloudFront. With the ease of set up and fast results, I have determined this to be a resoundingly effective method of ensuring easy and global access to static web content.
