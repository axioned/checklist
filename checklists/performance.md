---
title: Web Performance
category: Front-End
date: '2020-03-20'
tags: ['performance', 'speed']
description: The checklist for front-end developers to make sure their website is accessible for everyone!
---

- [ ] Page weight  
      The weight of each page is between 0 and 500 KB. Use tools like [imgix Page Weight Tool](https://pageweight.imgix.com/).

- [ ] Minified HTML, CSS and JS  
      Your HTML, CSS and JS files are minified.

- [ ] Lazy loading  
      Images, scripts and CSS need to be lazy loaded to improve the response time of the current page (See details in their respective sections)

- [ ] Cookie size  
      If you are using cookies be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

- [ ] DNS resolution  
      DNS of third-party services that may be needed are resolved in advance during idle time using dns-prefetch.

- [ ] Preconnection  
      DNS lookup, TCP handshake and TLS negotiation with services that will be needed soon is done in advance during idle time using preconnect.

- [ ] Prefetching  
      Resources that will be needed soon (e.g. lazy loaded images) are requested in advance during idle time using prefetch.

- [ ] Preloading  
      Resources needed in the current page (e.g. scripts placed at the end of <body>) in advance using preload.

- [ ] Google PageSpeed  
      All your pages were tested (not only the homepage) and have a score of at least 90/100 on [PageSpeed Insights](https://pagespeed.web.dev/) on Desktop and Mobile.

- [ ] Use a Content Delivery Network (CDN)  
      Identify and list out static assets and use/replace them with a CDN link if possible.

## Wordpress

### Image Optimization

- [ ] Install WP Smush. Resize images to existing upload directory.
- [ ] Image formats like JPEG 2000, JPEG XR, and WebP often provide better compression than PNG or JPEG, which means faster downloads and less data consumption.
- [ ] Add images of the required dimension.

### Code improvements and clean up

- [ ] Fixing HTML document with HTML parsing standards.
- [ ] Validate code & fix document, Code which is coming from theme can be fixed, some code is added by plugins directly deactivate plugin if not required.
- [ ] Optimize JS and PHP code - reducing looping, conditional logics and etc."
