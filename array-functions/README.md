
## ফাংসন্টি দুটি এরে থেকে সার্চ করার জন্য ব্যবহার করা হয়।

* in_array() = এই ফাংসন দিয়ে ব্যবহার করলে বুলিয়ান ভ্যলু রিটার্ন করবে। ১/০

```php
$a = array("a" => "red", "b" => "green", "c" => "blue" , "d" => "yellow");

if(in_array('red', $a)){
    echo 'Yes';
}else{
    echo 'No';
}
```

* in_search() = এই ফাংসন দিয়ে ব্যবহার করলে index/ key রিটার্ন করবে। যদি index array হয় তবে index রিটার্ন করবে । আর যদি Associative arry হয় তবে key রিটার্ন করবে।

```php
$a = array("a" => "red", "b" => "green", "c" => "blue" , "d" => "yellow");

print_r(array_search('red', $a));

restult is "a".




$d = array('Mango', 'Apple');

print_r(array_search('Mango', $d));

restult is "0".
```

