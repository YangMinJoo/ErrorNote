## .attr()
.attr(attributeName)  
.attr(attributeName, value)  
</br>  

🌸 Description: Get the value of an attribute for the first element in the set of matched elements.  
🌸 처음 일치하는 속성의 elements의 값을 value의 값으로 설정함.  
</br>  

#### attributeName  
- type: String
- 속성의 이름을 가져옴  
</br>  

#### value  
- type: String or Number or Null  
- attributeName의 속성을 value의 값으로 설정함. 만약 null일 경우, attributeName의 속성을 제거함.(as in .removeAttr())  
</br></br>  

🔹 Example 🔹  
```javascript
$( "#greatphoto" ).attr( "title", "Photo by Kelly Clark" );
```  
```javascript
navList = $('a');
navList.attr('href', '#1');
```
</br>  

참조: https://api.jquery.com/attr/
