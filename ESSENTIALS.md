Ruby Essentials
===============

Conditionals
------------

```ruby
if true then print 'Hi' else print 'Bye' end
```


Loops
-----

```ruby
for each in hashmap do print each end
```


Hash Class
----------

```ruby
hashmap = Hash.new       # default value is `nil`
hashmap = Hash.new(0)    # default value is `0`
hashmap = { }            # implicit definition; default value is `nil`

hashmap = { "key1" => "value1", :key2 => 2, key3: 'three', 0 => 0, [1, "arr as key"] => "Wow" }
hashmap["key1"]  # "value1"
hashmap[:key2]   # 2
hashmap[:key3]   # "three"
hashmap[0]       # 0
hashmap[[1, "arr as key"]]  # "Wow"
```


Unit Testing
------------

```ruby
require 'test/unit/assertions'
include Test::Unit::Assertions

assert(expression, message=nil)
assert(message=nil) { expressions }
```
