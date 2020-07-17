#### 选择器
1. 标签选择器
2. 类选择器
3. ID选择器
4. 复合选择器
   `$("#body p:eq(0)").text()`

#### 选择常用方法
1. next()
2. prev()
3. parents()
4. children()
5. parent()
6. find()
7. :first
8. :last
9. eq(1)
10. selected
11. checked

#### 属性操作
1. hide()
2. show()
3. attr()
4. addClass()
5. css()
6. removeClass()

#### 节点访问
1. append()
2. remove()
3. html()
4. text()
5. removeAttr()

#### ajax访问
```javascript
$.ajax({
    type:"post",
    url:url,
    data:data,
    async:false,
    success:function(response)
    {

    }
});
```

#### 事件
1. bind()
2. click()
3. onchange()
4. on()