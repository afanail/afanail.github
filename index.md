#Afanail web之路
##1.数组常见的方法
    ###//1.创建数组
    var myArray1 = [1,2,3,354,5,20];
    var myArray2 = [2,3,5,123,6,21];
     ###//2数组的连接方法:concat
     var myArray3 = myArray1.concat(myArray2);
      console.log(myArray3);
     ###//3.给数组的尾部添加一个元素
     var length1 = myArray1.push('20');
    console.log(myArray1);
    console.log(length1)
    ###//4.给数组同步添加一个元素
    var length2 =  myArray2.unshift(20);
    console.log(myArray2);
    console.log(length2);
    //凡是数组中添加元素都是返回数组的长度

    ###//5.删除尾部的元素
    var delSym1 = myArray1.pop();
    console.log(myArray1);
    console.log(delSym1);
    ###//6.删除头部元素
    var delSym2 = myArray2.shift();
    console.log(myArray2);
    console.log(delSym2);
    //凡是删除元素都是返回删除的元素
    ###//7.删除某一个位置的元素
    myArray1.splice(2,4);
    console.log(myArray1);
    ###//一般这个方法有两个参数，第一个表示从某一个位置开始删除，第二个表示删除元素的个数
    //8.可以使用传入的参数来连接每一个数组中的元素，形成一个字符串
    var lastString = myArray2.join('-');
    console.log(typeof lastString);
    console.log(lastString);
    ###//9.将有规律的字符转化成数组,使用参数中传入的值进行分割
    var lastArray = lastString.split('-');
    console.log(lastArray);
