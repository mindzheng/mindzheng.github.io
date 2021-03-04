# Methods

### 对象赋值

```javascript
/**
 * 对象赋值并且是只赋值目标对象中有的属性
 * @param target 目标对象
 * @param source 源数据
 */
setData(target, source) {
    Object.keys(target).forEach(key => { target[key] = source[key] || target[key]})
}
```

