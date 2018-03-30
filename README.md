# s-autoComplete
### 使用方法
```bash 
new AutoComplete({
input:".input",
onComplete:function(data,result){
},
data:[
  {"content":"wee"},{"content":"we"},{"content":"w"},
  {"content":"qee"},{"content":"se"},{"content":"erw"}
 ]
})
```
### 参数说明
onComplete:function(){} //调用成功之后回调函数
data:填充的数据
