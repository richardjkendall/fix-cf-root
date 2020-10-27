# fix-cf-root

Lambda@Edge function to fix CloudFront URLs which don't specify a filename.

E.g. changes /blog/ to /blog/index.html.

You can change the code if you use a different root file name.

Should be attached to the origin request chain in CloudFront.
