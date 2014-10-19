# wkhtmltopdf for Centos6 0.12.1 qtwebkit

[All the binaries for Centos6 from http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profburial/wkhtmltopdf-binaries-centos6": "0.12.1"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```
vendor/bin/wkhtmltoimage-amd64-centos6

vendor/bin/wkhtmltoimage-i386-centos6

vendor/bin/wkhtmltopdf-amd64-centos6

vendor/bin/wkhtmltopdf-i386-centos6
```

Enjoy the bin files!