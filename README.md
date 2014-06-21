MimosaJustACoffeeScriptFile
===========================

A very stripped down example for the purposes of illustrating Mimosa's simplicity.

### Usage

* `npm install -g mimosa`
* `git clone https://github.com/dbashford/MimosaJustACoffeeScriptFile`
* `cd MimosaJustACoffeeScriptFile`
* `mimosa build`

### Config?

```javascript
exports.config = {
  "modules": ["coffeescript", "coffeelint", "jshint"]
}
```

3 lines.  Mostly just 2.  

I added [CoffeeLint](http://www.coffeelint.org/) and [JSHint](http://www.jshint.com/) support for kicks.  Config stays the same size.
