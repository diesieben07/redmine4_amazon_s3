This [Redmine](http://www.redmine.org) 4 plugin stores file attachments on [Amazon S3](http://aws.amazon.com/s3) instead of the local filesystem.

This is based on monkey-patching Redmine's code. Keep an eye on https://www.redmine.org/issues/33188 for
the upstream issue about migration to ActiveStorage.

## Installation instructions

clone the plugin into plugins and name it "amazon_s3"

copy the default configuration into your Redmine setup  
```cp plugins/amazon_s3/config/amazon_s3.example.yml config/amazon_s3.yml```

update your dependencies  
```bundle```

delete the .git directory of the plugin and commit it to your favorite version control system  
```rm -Rf plugins/redmine_s3/.git```

## Attributions and license

This project is a fork of https://github.com/jhovad/redmine4_amazon_s3,
which is a fork of https://github.com/x3ro/redmine_amazon_s3,
which is a fork of https://github.com/ka8725/redmine_s3,
which is a fork of http://github.com/tigrish/redmine_s3.

The forks must continue.

See the `LICENSE` file.
