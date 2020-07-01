#### 返回 min（包含）～ max（包含）之间的数字

```js
function getRndInteger(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
```

#### 返回 min（包含）～ max（不包含）之间的数字

```js
function getRndInteger(min, max) {
  return Math.floor(Math.random() * (max - min)) + min;
}
```

