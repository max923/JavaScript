# JavaScript 全攻略：克服 JS 的奇怪部分

## Global Environment:
 * .Global Object -- Web(window)
 * .this
## Hoising
> Setup Memory Space for Variables and Functions "Hoisting"
```javascript
    b() // called b
    console.log(a) // undefined
    var a = 'Hello word'
    function b () {
      console.log('called b')
  }
```
