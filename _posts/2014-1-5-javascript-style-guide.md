---
layout: post
title:  "javascript style guide"
date:   2014-1-5 20:42
categories: web javascript
---
###大括号  
尽量使用大括号，甚至实在可选的情况下，都使用大括号。很多情况下如果只有一条语句可以省略大括号，但是为了一致性和更方便升级，最好都使用大括号。  
例如：  

    //不提倡  
    for (var i = 0; i < 10; i += 1)
        alert(i);
但是如果以后想要在这个循环中增加就会出现：

    for （var i = 0; i < 10; i += 1)
        alert(i);
        alert(n);
这样就不是不规范了，而是错误了，所以无论何种情况都一直使用大括号：

    //提倡
    for (var i = 0; i < 10; i += 1) {
        alert(i);
    }  
大括号位置:  

    {% highlight javascript %}
    //提倡
    function foo() {
        return {
            name: "polande";
        }
    }

    if (a > b) {
        return a;
    } else {
        return b;
    }
    {% endhighlight %}
因为js会默认为语句末尾添加分号这样有时就会出现问题  
###空格  
使用空格比较好的位置：  

- 在分开for循环的各个部分的分号之后: 例如， for (var i = 0; i < 10; i += 1)  
- 在for循环初始化的多个变量中：for (var i = 0, max = 10; i < 10; i += 1)  
- 在限定数组项的逗号后面: var a = [1, 2, 3];  
- 对象属性的逗号之后和将属性名和属性值分开的冒号之后: var o = {a: 1, b: 2};  
- 分开函数中各个参数的逗号之后: myFun(a, b, c)  
- 在函数声明的大括号之前: muFun() {}  
- 在匿名函数表达式之后: var myFun = function () {};  
- 分隔操作符和操作例如在 +, -, *, /, <, >, +=, >=, <=, ===, &&, ||, 等之后使用  
- 可以使用空行来分隔不同的单元  

###命名约定  
- 构造函数首字母大写  
    var admin =  new Person();  
- 单词组合形式的:  
   - 构造函数使用大驼峰式: MyFun();  
   - 函数名和方法名使用小驼峰: myFun();  
   - 非函数的变量使用: fist_name;

###注释  
注释要适当，不要太多  
    单行注释 `// 注释符前留有一个空格`  
    多行注释:  

    /*  
     * 星号对齐    
     */  

    函数和方法注释:  

    /**
     * 方法说明
     * @method 方法名
     * @for 所属类名
     * @param {参数类型} 参数名 参数说明
     * @return {返回值类型} 返回值说明
     */
<<<<<<< HEAD
参考[dd](http://www.lifefrom.com/qianduan/336.html)  
=======

>>>>>>> 897e179aed9ea5dba4b5ffa3a5d76353b2deff80

