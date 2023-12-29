# JavaScript 기초

12/16 메모장

메소드명 : funtion(파라미터){

[](https://www.notion.so/fc45c11f588347e09a3576ac717894d8?pvs=21)

동작:

},  ← 쉼표 중요!  메소드 또한 *** property!!!!

*** 메소드에서 파라미터로 key값을 받아오면 대괄호( [ , ] ) 사용!!

for (변수 in 객체){

동작

};

주의사항 - 프로퍼티에 정수형을 부여하게되면 순서와 상관없이 번호순서대로 우선순위를 두고 오름차순으로 먼저 정렬하고 나머지 프로퍼티들이 정렬됨

Date 객체

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled.png)

getTime() 메소드  → 1970년 1월 1일부터 몇 밀리초가 지났는지 반환

Date 는 일자를 뜻하고 Day는 요일을 의미하며 0~6 일요일부터 시작

*배열*

let 변수 = [

요소,

요소,

]; 

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%201.png)

객체에서는 delete 객체명[’프로포티명’] or 객체명.프로포티명을 하면 지워짐

배열에서는 delete 배열명[index]를 하면 그자리에 empty가 되며 배열의 길이는 바뀌지 않는다!! 

그래서 배열명.splice(index); 를 사용하면 index번호 이후에 요소를 모두 삭제

배열. splice(startIndex,deleteCount);  시작인덱스부터 몇개 지울건지 

배열.splice(start , delete , item); 지운부분에 item 삽입!  item 이 몇개든지가능

members.shift( ); 첫 요소 삭제

members.pop( ); 마지막 요소 삭제

members.unshift(’ ㅁㅁ’); 첫요소로 값 추가

members.push(’ ㅁㅁ ‘); 마지막 요소 추가

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%202.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%203.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%204.png)

for (변수 of 배열) {

동작부분;

}

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%205.png)

다차원 배열

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%206.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%207.png)

숫자 표기법

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%208.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%209.png)

toFixed 메소드를 사용하면 값이 문자열이기때문에

Number메소드를 사용하거나, 앞에 +를 붙여 숫자로 바꾸어 준다

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2010.png)

toString( ) 메소드 문자열로 변환시켜줌

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2011.png)

math( )메소드

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2012.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2013.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2014.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2015.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2016.png)

문자열

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2017.png)

trim ()메소드 양쪽 공백 제거

slice ( ) 메소드 

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2018.png)

indexof (’[형돈]’ )은 [의 인덱스번호를 반환하는듯 보인다

  

객체(참조형)는 포인터처럼 동작(?)한다. 

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2019.png)

배열(참조형)도 동일하다 

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2020.png)

참조형 복사

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2021.png)

![Untitled](JavaScript%20%E1%84%80%E1%85%B5%E1%84%8E%E1%85%A9%201c15c32f5a6242f9a8fc04733ab8a1f7/Untitled%2022.png)