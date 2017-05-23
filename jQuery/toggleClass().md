## .toggleClass()
.toggleClass(className)  
</br>  

🌸 Description: Add or remove one or more classes from each element in the set of matched elements, depending on either the class's presence or the value of the state argument.  
🌸 className이 존재하면 element(className)와 일치하는 각각의 element, 혹은 그 이상의 class 를 추가하거나 삭제함. (일치하는 className이 없는 경우 삭제하고, 있는 경우 추가함.)  
</br>  

#### className
- type: String
- 한 개 혹은 여러개의 class naems (스페이스로 구분)을 일치하는 element로 바꿈.(matched set)
</br>   
#### state  
- type: boolean  
- boolean 값에 따라 삭제할지 추가할지 결정함.  
</br></br>  

🔹 Example 🔹  
```<div class="tumble">Some text.</div>```  
```$("div.tumble").toggleClass("bounce")```
</br>  
```featuredArticle = $('.article-item');```
```featuredArticle.toggleClass('featured');```  
</br>
참조: http://api.jquery.com/toggleclass/
