# DOM
#### (Document Object Model)
</br></br>  

### 1. Define
- The DOM is a W3C (World Wide Web Consortium) standard.</br>
- When a web page is loaded, the browser creates a Document Object Model of the page.</br>
- "The W3C Document Object Model (DOM) is a platform and language-neutral interface</br>
that allows programs and scripts to dynamically access and update the content, structure, and style of a document." 
</br>  

- HTML= 태그를 가진 문서, JavaScript= 코드   
이 둘이 대화하는 방법(공통점) => DOM 으로 표현함으로써 가능함.   

- 화성에서 온 HTML5, 금성에서 온 JavaScript.

- HTML= 선언형 태그로 구성, web page를 구성하는 중첩된 요소들로 설명   
JavaScript= 계산을 설명하기 위한 알고리즘으로 만들어짐.  

- DOM= 웹 페이지를 브라우저 내부에서 표현하는 형태
</br></br>  

### 2. 
- DOM을 다룰 때에는 페이지가 완전히 로딩된 후에 코드를 실행해야 함.
그렇지 않으면 DOM이 완성되기 전에 코드가 실행될 가능성이 높다.

- web page를 완전히 로딩하고 DOM 을 생성한 후에 코드를 실행하기 !  

- JavaScript에서는 document 객체를 이용해 DOM에 접근함.  

- DOM 으로 할수 있는것! => 요소 가져오기, 생성해서 추가하기, 제거하기, 순회하기  

#### * onload  
###### Callback, Event Handler  
1. 이벤트에 대해 알고 있는 객체에 함수를 알려줌  
2. 이벤트가 생기면 객체가 함수를 호출함으로써 이벤트가 일어났다고 알려줌.  

</br></br> 
#### * setAttribute()  
##### 메서드를 호출하면, 요소에 이미 있는 속성은 변경하고 요소에 존재하지 않는 속성은 추가해줌.  


</br></br></br> 
#### < REFERENCE >
>https://www.w3schools.com/js/js_htmldom.asp  
>headfirst javascript programming book
 
