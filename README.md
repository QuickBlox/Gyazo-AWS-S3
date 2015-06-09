# Gyazo-AWS-S3
Script that setups Gyazo server to store images on AWS S3

# Setup
1. Create **index.php** from **index.sample.php**
2. Create **settings.php** from **settings.sample.php**
3. Put AWS settings into **settings.php**. Example:
```php
$company_name='your_company_name';

// Bitly credentials
$bitly_name='o........m';
$bitly_key='4R.......................33';

// AWS credentials
$aws_key='K5I..........EQ5';
$aws_secret='3P..........................o8';
$aws_bucket='inpic';
$aws_site='http://s3.amazonaws.com';
$cloudfront_site='http://image.company_name.com';
```
