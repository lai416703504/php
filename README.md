#PHP小技巧

```php
$a??$b
``` 
相当于 
```php
isset($a)?$a:$b;
```

与$a?:$b是不同的 $a==false的时候这个是会等于$b的