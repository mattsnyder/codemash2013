# Test Double
_@andrewvida @searls_

__jasmine-fixture__ => Provides the `affix` method for extracting html for
use in specs

## CoffeeScript
Benefit of CoffeeScript, compiles and is guaranteed to pass
__js-lint__. Reduces IE bugs by 99.99%!

```coffeescript
class window.Panda
    disposition: -> "sad"
```
```javascript
window.Panda = function(){};
Panda.prototype.disposition = function(){
  return "sad";
}
```
### JavaScript to CoffeeScript
* `{}` becomes `->`
* `this` becomes `this.`

## jasmine-given
```coffeescript
describe "Panda" ->
  Given -> @subject = new Panda
  
  describe "disposition", ->
    When -> @result = @subject.disposition()
    Then -> expect(@result).toBe("sad")
```

Can chain `Then` together
```coffeescript
  (Then -> expect(@result).toBe("sad")).
  Then -> expect(@result).toBe("sad")
```

Drop expectation and use expression that returns explicit `true` or `false`
```coffeescript
  Then -> @result == "sad"
```

Expecting an exception to be thrown
```coffeescript
  Then -> expect(->@thingy()).toThrow("got an error")
```
