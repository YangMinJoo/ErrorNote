## Function  

1. 브라우저는 페이지를 Parsing 후 함수 선언을 찾아내고, 발견한 후 함수를 생성하고 함수명과 동일한 변수에 이 함수에 대한 참조를 저장함.  
   (ex) ``` function apple(fruit) { console.log(fruit); } ```  
    
2. 브라우저가 코드를 실행함  


- 함수에 대한 참조를 변수가 저장할 수 있다.  
- 함수 표현식은 다른 표현식을 사용할 수 있는 모든 곳에 사용할 수 있다.  
- Function Reference
  =>함수 참조를 이용해 함수를 호출하거나, 변수에 할당하거나, 객체에 저장하거나, 함수에 전달하거나 함수에서 반환할 수 있음. 객체 참조와 비슷함  
- 함수도 숫자, 문자열, boolean, 객체와 같은 값으로 생각하기. (함수는 '호출할 수 있다'는 점에서 나머지 값들과 다름.  


- First Class (일급)값  
   => 프로그래밍에서 다른 값과 동일하게 처리되는 값. 변수에 할당할 수 있고, 함수에 인자로 전달하고, 함수에서 반환할 수 있다.  
- 