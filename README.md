# varDumpAsText
Simple and cool tool for echo array as text in command line.

## Usage and example output

```php
include 'varDumpAsText.php';

$array = [
	// ...
];
echo rt($array)
```

#### var_dump output

```php
array(2) {
  ["update_id"]=>
  int(404926057)
  ["message"]=>
  array(5) {
    ["message_id"]=>
    int(4456)
    ["from"]=>
    array(4) {
      ["id"]=>
      int(000000)
      ["first_name"]=>
      string(8) "عباس"
      ["last_name"]=>
      string(10) "شکیبا"
      ["username"]=>
      string(12) "abbasShakiba"
    }
    ["chat"]=>
    array(5) {
      ["id"]=>
      int(000000)
      ["first_name"]=>
      string(8) "عباس"
      ["last_name"]=>
      string(10) "شکیبا"
      ["username"]=>
      string(12) "abbasShakiba"
      ["type"]=>
      string(7) "private"
    }
    ["date"]=>
    int(1493642471)
    ["text"]=>
    string(5) "Hello"
  }
}
```

#### rt() Output 

```
[ref]
ref.update_id= 404926057
ref.message.message_id= 4456
ref.message.from.id= 000000
ref.message.from.first_name= عباس
ref.message.from.last_name= شکیبا
ref.message.from.username= abbasShakiba
ref.message.chat.id= 000000
ref.message.chat.first_name= عباس
ref.message.chat.last_name= شکیبا
ref.message.chat.username= abbasShakiba
ref.message.chat.type= private
ref.message.date= 1493642471
ref.message.text= Hello
```

## Similar projects

- [Kint](http://raveren.github.io/kint/)
- [dump_r](https://github.com/leeoniya/dump_r.php)
- [Krumo](http://sourceforge.net/projects/krumo/)
- [dBug](http://dbug.ospinto.com/)
- [symfony-vardumper](http://www.sitepoint.com/var_dump-introducing-symfony-vardumper/)
