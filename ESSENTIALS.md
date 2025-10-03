[💎 Ruby](https://docs.ruby-lang.org/en/master/index.html) Essentials
=====================================================================


[⌨️ Syntax](https://docs.ruby-lang.org/en/master/syntax_rdoc.html)
-----------

### [Conditionals](https://docs.ruby-lang.org/en/master/syntax/control_expressions_rdoc.html#label-if+Expression)
```ruby
if true then print 'Hi' else print 'Bye' end
```

### [Loops](https://docs.ruby-lang.org/en/master/syntax/control_expressions_rdoc.html#label-while+Loop)
```ruby
for each in hashmap do print each end
```


[⚙️ Core Classes](https://docs.ruby-lang.org/en/master/index.html?search=Test%3A%3AUnit%3A%3AAssertion#label-Core+Classes+and+Modules)
-----------------

### [Hash Class](https://docs.ruby-lang.org/en/master/Hash.html)
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


[🏛️ Standard Library](https://docs.ruby-lang.org/en/master/standard_library_md.html)
---------------------

### [Test::Unit](https://test-unit.github.io/test-unit/en/)
```ruby
require 'test/unit/assertions'
include Test::Unit::Assertions

assert(expression, message=nil)
assert(message=nil) { expressions }
```
