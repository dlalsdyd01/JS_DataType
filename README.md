# JS_DataType  

## String  
텍스트 데이터 이며 " " , ' ', ` `를 사용 가능하다.  

## Number  
정수, 실수, 음수를 표현 가능하다.  
소수점을 적을때 정수가 0아면 정수를 생략이 가능하다.  

## Bollean  
true 와 false를 사용하는 논리데이터이다. 

## Null  
"값이 없음"을 명시적으로 나타낸다. 여기에 아직 값이 없다라는 의미.  

## Undefined  
"값이 없음"을 암시적으로 나타낸다.  
변수는 선언되었지만 값을 할당하지 않으면 자동으로 undefined로 정해짐.  

## Array  
```
// 배열 리터럴 
const fruits = ['Apple', 'Banana', 'Cherry']
console.log(fruits)
// 배열 인덱싱(대괄호 표기법)
const fruits = ['Apple', 'Banana', 'Cherry']
console.log(fruits[1])
```
Apple, Banana, Cherry 는 배열의 아이템, 요소(Element)라고한다.  

## Object  
```
// 생성자 함수 방식
const user = new Object()
user.name = 'HEROPY'
user.age = 85

console.log(user)
```
key: value  
key 는 속성(Property), value 는 값 이라고 표현한다. 

리터럴 방식  
```
const user = {
    name: 'HEROPY',
    age: 85
}

console.log(user)
```
거의 리터럴 방식으로 사용된다.  
```

## 참/ 거짓
거짓: false, 0, null, undefined, Nan, ' ', 0n(정수데이터 + n)  
참: 그 외 쓸 수 있는 대부분의 값

## 데이터 타입 확인
```
// Typeof 사용
const a = 123
console.log(typeof a)
```
