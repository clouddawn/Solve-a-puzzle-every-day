# 一日一难点



## 2021年3月24日

```js
//冒泡排序
let array = [10, 9, 5, 3, 8, 4, 9, 5];
let len = array.length;
function sort(arry){
  for(let i=0; i<len; i++){
    for(let j=0; j<len-i-1; j++){
      if((array[j]>array[j+1])){
      let temp = array[j];
      array[j] = array[j+1];
      array[j+1] = temp;
    }
    }
  }
  console.log(array);
}
sort(array);
```

