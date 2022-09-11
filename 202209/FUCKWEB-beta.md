# FUCKWEB-beta

**1.以下哪一个不是JavaScript的数据类型？**

String

Boolean

***Integer***

Undefined

---

**2.单独存放 JavaScript 程序的文件扩展名是？**

java

***js***

script

prg

---

**3.获取 input 节点的正确方法是？**

```html
<form class="file" name="upload">
<input id="file" name="file" />
</form>
```

document.querySelectorAll('file')[0]

document.getElementById('file')[0]

document.getElementByTagName('file')[0]

***document.getElementById('file')*****

---

**4.三元操作，哪个语法是正确的？**

***var x=y===true?”true”:”false”;***

var x=y===true:”true”?”false”;

var x=(y===true):”true”?”false”;

var x=(y===true){“true”:”false”};

---

**5.下列事件哪个不是由鼠标触发的事件？**

click

contextmenu

mouseout

***keydown***

---

**6.以下代码执行后，console 输出的信息是？**

```javascript
for(var i = 0; i < 5; i++){
    requestAnimationFrame(() => console.log(i));
}
```

1 2 3 4 5

0 1 2 3 4

4 4 4 4 4

***5 5 5 5 5***

---

**7.如果不给cookie设置过期时间会怎么样？**

立刻过期

永不过期

cookie 无法设置

***在浏览器会话结束时过期***

---

**8.下面符合javascript变量定义规则的是？**

***_$te$t2***

with

a bc

2a

---

**9.在JavaScript中，下列不属于数组方法的是？**

concat()

sort()

reverse()

***length()***

---

**10.请问以下两次检测对象constructor是否拥有属性名1的结果分别是什么？**

```javascript
1 in Object(1.0).constructor;
Number[1] = 123;
1 in Object(1.0).constructor;
```

false、false

***false、true***

true、true

true、false

---

**11.下列关于 JavaScript 模块化的描述，错误的是？**

AMD推崇依赖前置，CMD推崇依赖就近

***Sea.js遵循AMD规范，RequireJS遵循CMD规范***

主流的模块化包括CommonJS,AMD,CMD等

模块化有利于管理模块间的依赖，更依赖模块的维护

---

**12.以下结语句中，返回true的是？**

***!![]***

1===’1’

null===undefined

!!’’

---

**13.执行下面的代码， x 的值是：**

```javascript
var str='what is this';
var x=str.search('is');
```

1

***5***

6

7

4

---

**14.在标准的 JavaScript 中， Ajax 异步执行调用基于下面哪一个机制才能实现？**

***Event和callback***

多线程操作

多CPU核

Deferral和promise

---

**15.不能从字符串 const str = 'qwbewrbbeqqbbbweebbbbqee';中能得到结果 ["b", "bb", "bbb", "bbbb"]的语句是？**

str.match(/b+/g)

***str.match(/b\*/g)***

str.match(/b{1,4}/g)

str.match(/b{1,5}/g)

---

**16.void();上面表达式的结果是？**

undefined

TypeError

null

***SyntaxError***

---

**17.JavaScript 中的数字在计算机内存中占多少个Byte？**

2Byte

4Byte

***8Byte***

16Byte

---

**18.执行以下程序，输出结果为（）**

```javascript
function Father(age){
    this.age = age
}
function Son(age){
    Father.call(this);
}
Son.prototype = Father.prototype;
Father.prototype.getAge = function(){console.log(40);}
Son.prototype.getAge = function(){console.log(18);}
var father = new Father(40);
var son = new Son(18);
son.getAge();
father.getAge();
```

***18 18***

40 40

18 40

18 undefined

---

**19.下列语句运行后哪些打印的结果是false？**

alert（2<1<3）

alert（3 == “3”）

alert（null == undefined）

***alert（null == 0）***

---

**20.请问以下JS代码的输出顺序是？**

```javascript
let date = new Date()
setTimeout(() => {
    console.log('1')
}, 2000)
setTimeout('console.log(2)',1000);
setTimeout(function() {
  console.log('3')
}, 1500);
while((new Date() - date) < 3000) {}
```

报错

***3秒以后同时输出2 3 1***

1秒后输出2，1.5秒后输出3，2秒后输出1

4秒后输出2，4.5秒后输出3，5秒后输出1

---

**21.执行以下程序，输出结果为？**

```javascript
class Phone{
  constructor(price){
    this.price = price;
  }
  get price(){
    return 999;
  }
}
var p = new Phone(888);
console.log(p.price);
```

999

undefined

***抛出异常***

888

---

**22.下面属于javascript基本数据类型的有？**

***字符串***

***数字***

***null***

***undefined***

---

**23.以下哪些选项可以获取ID为a的DOM元素？**

***document.getElementById('a')***

document.getElementById('#a')

document.querySelector('a')

***document.querySelector('#a')***

---

**24.下列关于闭包描述正确的是？**

***闭包内变量执行后不会被清除***

闭包不满足链式作用域结构

***(Function(){})()理论上是一个闭包***

闭包不耗内存，可以随意使用

---

**25.以下哪些Array对象的方法不会更改原有数组？**

***concat()***

splice()

***map()***

sort()

---

**26.存在变量 var a = 10.42; 取出 a 的整数部分，以下代码哪些是正确的？**

***parseInt(a);***

***Math.floor(a);***

Math.ceil(a);

a.split('.')[0];

---

**27.下面哪些属于JavaScript的typeof运算符的可能结果？**

***symbol***

int

***boolean***

null

array

***undefined***

***string***

---

**28.当用户打开一个网页时，想一直停留在当前打开的页面，禁止页面前进和后退，以下正确的是？**

***window.history.forward(1);***

window.history.back(1);

window.history.go(-1);

***window.history.forward(-1);***

---

**29.在一个表单中，如果想要给输入框添加一个输入验证，可以用下面的哪个事件实现？**

hover(over ,out)

keypress（fn）

***change()***

***change(fn)***

---

**30.以下哪些正则表达式满足regexp.test('abc') === true？**

***/^abc$/***

/...(?=.)/

***/[ab]{2}\[^defgh\]/***

***/[defgh]*/***
