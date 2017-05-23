## .css()
.css(propertyName)  
.css(propertyName, value)  
.css(propertyName, function)  
.css(properties)  
</br>  

🌸 Description: Get the computed style properties for the first element in the set of matched elements.  
🌸 첫번째 element로 스타일 속성을 받고, 그 속성으로 elements에 매치시킨다.  
</br>  

#### propertyName  
- type: String
- CSS 속성   
#### value  
- type: String or Number
- propertyName 속성의 값  
</br>  

⚡️ 주의  
이렇게 사용하는 건 좋은 방법은 아님.  
하지만 사이트를 만들다 보면 필요할 때가 있음.  
실제로 현업에서 사용할 땐 jQuery 와 CSS 둘 중 하나를 선택해야함.  

🔹 Example 🔹  
```javascript
$( "div.example" ).css( "width", function( index ) {
  return index * 50;
});
```  

</br>  

```javascript
articleItems = $('.article-item');
articleItems.css('font-size', '20px');
```
</br>  

참조: http://api.jquery.com/css/
