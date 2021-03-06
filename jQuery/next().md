## .next()
.next([selector])  
</br>  

🌸 Description: Get the immediately following sibling of each element in the set of matched elements. If a selector is provided, it retrieves the next sibling only if it matches that selector.  
🌸 현재 elements와 일치하는 각각의 elements들의 형제들을 가져온다. 만약 selector가 제공된다면, selector와 일치하는 요소의 형제 요소를 가져온다.
</br>   

#### selector
- type: Selector
- A string containing a selector expression to match elements against.  
</br></br>  

🔹 Example 🔹  
```javascript
<ul>
<li>list item 1</li>  
<li>list item 2</li>  
<li class="third-item">list item 3</li>  
<li>list item 4</li>  
<li>list item 5</li>  
</ul>
```  
```jQuery
$( "li.third-item" ).next().css( "background-color", "red" );  
```
</br>  

참조: https://api.jquery.com/next/
