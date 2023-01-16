# html
##  a标签的使用 target的设置表示重新在一个端口打开链接地址
```html
<a target="_blank" href=""></a>
```
## input 的使用
```html
 <input type="text">
    <input type="textarea">
    <input type="date" min="2022-01-01">    
    <input type="range">    
    <input type="number" min="1" max="5">
    <label for="">
        <input type="radio" name="sport">瑜伽
    </label>
    <label for="">
        <input type="radio" name="sport">羽毛球
    </label>

    <select name="clothes" id="">
        <option value="衣服">衣服</option>
        <option value=" ">裤子</option>
        <option value="袜子">袜子</option>
        <option value="鞋子">鞋子</option>
    </select>

    <input list="cities" type="text"> 城市
    <datalist  id="cities">
        <!-- 注意这里一定要设置value才行，给输入框提示已经有的选择 -->
        <option value="Wuhan"></option>
        <option value="Yunnan">Yunnan</option>
        <option value="">Beijing</option>
    </datalist>
 

```