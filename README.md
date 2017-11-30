# TweenJS
TweenJS是用于Javascript简单的tweening库。
它与EaselJS库集成得很好，但不依赖于或特定用它(尽管它在默认情况下使用相同的Ticker和Event类)。它支持数字对象属性和CSS样式属性的渐变。

### 例子
该API非常简单，但功能非常强大，通过链接命令可以很容易地创建复杂的tweens。
```
var tween = createjs.Tween.get(myTarget)
    .to({x:300},400)
    .set({label:"hello!"})
    .wait(500).to({alpha:0,visible:false},1000)
    .call(onComplete);
```

