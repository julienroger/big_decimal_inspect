### Before

```ruby
BigDecimal.new("5000.1234")
=> #<BigDecimal:7f9c81844020,'0.50001234E4',18(18)>
```

### After

```ruby
BigDecimal.new("5000.1234")
=> #<BigDecimal:"5000.1234">
```

[![Circle CI](https://circleci.com/gh/wealthsimple/big_decimal_inspect.svg?style=svg)](https://circleci.com/gh/wealthsimple/big_decimal_inspect)
