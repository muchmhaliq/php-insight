# PHP Insight Sentiment Analysis
---------
Sentiment analysis is the process of analyzing digital text to determine whether the emotional tone of the message is positive, negative, or neutral. Sentiment analysis tools can scan this text to automatically determine the author's attitude toward a topic.

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
