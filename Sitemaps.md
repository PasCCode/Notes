# Sitemaps

## Supported Formats

    1. XML
    2. RSS, mRSS & Atom 1.0
    3. Text file (needs to be UTF-8 encoded)
    4. Google site automatically generate a sitemap

## Guidelines

- Google will crawl URLs exactly are they are listed, always use absolute paths

- a sitemap can be posted anywhere on the site, but a sitemap affects onlz descendants of the parent directory

- do not include sessions IDs from URLs in the sitemap to reduce duplicate crawling of those URLs

- alternate language versions of an URL should be advertised using *hreflang annotations*

- sitemap files must be UTF-8 encoded and URLs escaped appropriately

- break up large sitemaps into smaller sitemaps: maximum size 50,000 URLs/50MB uncompressed
  - use a *sitemap index file* to list all individual sitemaps and submit this file instead of individual sitemaps

- list only *canonical URLs* in sitemaps

- Google doesn't check a sitemap every time it crawls a website
  - webmaster need to notify Google if the sitemap has changed
    1. Option: submit the new sitemap via Seach Console
    2. Insert the following line anywhere in the `robots.txt`, specifying the path to the sitemap `Sitemap: http://example.com/sitemap_location.xml`
