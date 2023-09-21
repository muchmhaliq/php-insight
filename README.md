# PHP Insight
---------

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