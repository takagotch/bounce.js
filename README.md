### bounce.js
---
https://github.com/tictail/bounce.js

http://bouncejs.com/

```
npm install
bower install

grunt serve
grunt test

bower install bounce.js
npm install bounce.js
```

```js
var bounce = new Bounce();
bounce
  .translate({
    from: { x: -300, y: 0 },
    to: { x: 0, y: 0 },
    duration: 600,
    stiffness: 4
  })
  .scale({
    from: { x: 1, y: 1 },
    to: { x: 0.1, y: 2.3 },
    easing: "sway",
    duration: 800,
    delay: 65,
    stiffness: 2
  })
  .scale({
    from: { x: 1, y: 1},
    to: { x: 5, y: 1},
    duration: 300,
    delay: 30,
  })
.applyTo(document.querySelectorAll(".animation-target"));

Bounce.isSupported()

bounce.remove()

bounce.applyTo($(".animation-target")).then(function(){
  console.log("Animation Complete");
});

var bounce = new Bounce();
bounce.rotate({
  from: 0,
  to: 90
});
bounce.define("my-animation");

var bounce = new Bounce();
bounce.rotate({
  from: 0,
  to: 90
});
bounce.applyTo(document.querySelectorAll(".animation-target"))
// bounce.applyTo($(".animation-target"));

var bounce = new Bounce();
bounce.rotate({
  from: 0,
  to: 90
});

var bounce = new Bounce();
bounce.translate({
  from: { x: 0, y: 0 },
  to: { x: 100, y: 0 }
});

var bounce = new Bounce();
bounce.skew({
  from: { x: 0, y: 0 },
  to: { x: 20, y: 0 }
});

var bounce = new Bounce();

var bounce = new Bounce();
bounce.scale({
  from: { x: 0.5, y: 0.5 },
  to: { x: 1, y: 1 }
});
```

```
```

