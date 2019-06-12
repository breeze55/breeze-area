## breeze-date

这是一个基于原生JavaScript开发的移动端省市县三级联动插件

## 版本 

[测试版本]

0.0.0

## 安装

使用npm下载源文件


```
npm install breeze-area --save
```

直接使用script引用

```js
<script src="../dist/breeze-area-0.0.0.min.js"></script>
```

## 使用

```js
<script type="text/javascript">
  var config1 = {
    target: "picker-date1",
    type: "area",
    ensureCallback: function(value) {
      console.log(value);
      return value;
    }
  };
  new BreezeArea(config1);
</script>
```

## 参数
```
```

|        参数       |   类型   | 默认值  |             说明             |
|-------------------|----------|----------|-------------------------------------|
| target              | String    | “picker”       | 目标元素id          |
| currentValue             | Array   | 0      | 当前地区 |
| ensureCallback       | Function   | 空函数   | 点击确定之后执行回调函数          |

## 演示

[demo](https://breeze55.github.io/breeze-area/example/index.html)

```
如果你感觉好用，欢迎给我打赏
```
![avatar](https://raw.githubusercontent.com/breeze55/static/master/breeze.png)

## License
[MIT](https://github.com/breeze55/breeze-area/blob/master/LICENSE)
