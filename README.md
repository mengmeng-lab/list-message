# list-message
有关字符串的问题
1.subString(1,s.length-1)截取字符串，typeof判断字符类型
 s.splice(5, 0, "Z"); //添加数组的第5 个元素
 s.splice(0,1); //删除数组的第1 个元素

2.string中indexOf() 会将数值参数转换为字符再查询索引；
number类型没有IndexOf() 可以转换为字符再使用
array中indexOf() 是严格比较


3.toString() ->整型->字符型  parseInt()->字符型->整型
+进行拼接
push()向数组添加元素
for循环的使用
  for(var i in this.list){
    this.string=list[i].name
}
