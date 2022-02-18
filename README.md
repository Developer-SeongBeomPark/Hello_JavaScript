# Hello_JavaScript


## Object

#### Object
number, string, boolean의 단순 자료형보다 더 복잡한 자료를 표현할 때 사용

#### 객체를 만드는 법
중괄호 {} 를 사용해 정의 가능<br>
객체는 속성의 집합으로 이뤄짐<br>
각 속성은 이름과 값으로 이뤄짐<br>
객체 정의 시 속성이름:값의 형태로 속성 정의 가능<br>
속성의 값은 모든 자료형이 가능, object 포함<br>

#### 객체의 속성에 접근하는 법
객체 이름 뒤에 점(.)을 사용하고 속성 이름에 접근 할 수 있음<br>
객체 이름 뒤에 대괄호([]) 안에 속성 이름을 문자열로 접근할 수 있음<br>

#### 객체의 속성의 값을 변경하는 법
객체 속성에 접근해서 변수에 값을 저장하듯이 사용

## undefined와 null
#### undefined
시스템에서 어떤 변수나 속성이 정의되지 않은 경우를 표현하기 위해 사용<br>
선언만 하고 초기화가 되지 않는 변수의 타입이나 값<br>
객체의 정의되지 않은 속성의 타입이나 값<br>

#### null
개발자가 명시적으로 아무것도 없는 비어있는 상태를 나타낼 때 사용<br>
typeof의 결과는 object이며 값은 null<br>

## String 이어 붙이기
#### 문자열 길이 알아내기
문자열의 .length 속성을 이용<br>
str.length<br>

#### 문자열 붙이기
.concat 함수 사용<br>
str1.concat(str2)<br>
더하기(+) 연산자 사용<br>
str1+str2<br>


## String 다루기

#### 특정 위치의 문자열 알아내기
.charAt 함수 이용<br>
첫 문자 : str.charAt(0)<br>
마지막 문자 : str.charAt(str.length-1)<br>
대괄호([]) 사용<br>
첫 문자 : str[0]<br>
마지막 문자 : str[str.length-1]<br>
#### 부분문자열 구하기
문자열의 연속된 일부분을 구하는 함수<br>

.substring(pos1, pos2) : pos1 에서 pos2까지의 부분 문자열 반환<br>
pos2 생략시 pos1에서부터 마지막 까지의 문자열 반환<br>
substr(pos, length) : pos에서 length길이 만큼의 부분 문자열 반환<br>
length 생략시, pos에서 마지막까지의 문자열 반환<br>
pos 가 음수인 경우, str.length - pos 로 동작<br>

#### 문자열 검색하기
indexOf(str)<br>
lastIndexOf(str)<br>

