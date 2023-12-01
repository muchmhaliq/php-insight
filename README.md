# PHP Insight
---------
PHP Insight was carefully crafted to simplify the analysis of your code directly, and is the perfect starting point to analyze the code quality of your PHP projects.

### Installation
```bash
composer require mashmhaliq/php-insight
```

### How to Usage
```php
use PHPInsight\Sentiment;
#....
$analyzer = new Sentiment();
$analyzer->categorise($string); #return text category, positive, negative or neutral
$scores = $analyzer->score($string);

#Returns text scores, for example
#(
#    [neg] => 0.865
#    [neu] => 0.108
#    [pos] => 0.027
#)
```
