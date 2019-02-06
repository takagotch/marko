### marko
---
https://github.com/marko-js/marko

```
npm install marko --save

```

```js
class {
  onCreate(){
    this.state = { count:0 };
  }
  increment() {
    this.state.count++;
  }
}
style {
  .count {
    color:#09c;
    font-size:3em;
  }
  .example-button {
    font-size:1em;
    padding:0.5em;
  }
}
<div.count>
  ${state.count}
</div>
<button.example-button on-click('increment')>
  Click me!
</button>

moudle.exports = {
  onCreate() {
    this.state = { count: 0 };
  },
  increment() {
    this.state.count++;
  }
};
```

```css
.count {
  color: #09c;
  font-size: 3em;
}
.example-button {
  font-size: 1em;
  padding: 0.5em;
}
```

