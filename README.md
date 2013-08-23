nginx-aws
=========

Cloudformation template to create an [NGINX](http://nginx.org/) instance built with [Google PageSpeed](https://developers.google.com/speed/pagespeed/) and whatever options are required.

Based on the instructions to [Build ngx_pagespeed From Source](https://developers.google.com/speed/pagespeed/module/build_ngx_pagespeed_from_source)..

Includes support for SPDY and also the [Amazon S3 Proxy Authentication Module](https://github.com/anomalizer/ngx_aws_auth) as an example of customizing the build.
