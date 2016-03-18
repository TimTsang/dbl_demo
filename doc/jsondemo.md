## /jsondemo.json
#### Interface type
	GET
#### Interface request address
	/jsondemo.json
#### Return interface
```js
{
 "word": "xxxxxxx", //随机字符
 "number": 1, //1-10数字随机生成
 "array": [ //简单的数组
  "a",
  "b"
 ],
 "randomArray": "a", //a,b随机获取
 "object": { //对象
  "email": "xxxxxxx@mock2easy.com"
 },
 "objectArray": [ //数组重复生成两遍
  {
   "id": 1 //id数组叠加
  }
 ]
}
```