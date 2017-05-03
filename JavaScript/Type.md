## Type  
</br>  

### 1. == 연산자  (Equality operator)
1. 두 값의 형이 같으면 단순히 비교만 함.  
2. 두 값의 형이 다르면 두 값을 **동일한 형** 으로 변환하고 비교함.  

  ##### [example]  
1. 99 == "바닐라"   
   99 == NaN  
   => **false**

2. 1 == true  
   1 == 1  
   => **true**

3. undefined == null (두 값 모두 '없는 값'을 비교)  
   => **true**  
   
### 2. === 연산자  (Strict Equality Operator)
  두 피연산자의 형과 값이 모두 같을 때에만 엄격하게 일치함.  
</br>  
  
### 3. JavaScript는 문자열에 있는 각각의 글자를 분석하고 각각을 숫자로 바꾸려고 함.  
  ##### [example]  
1.  var addi = 3 + "4";  
    **addi = 34**   
    
2. var multi = 3 * "4";  
   **multi = 12**  
  
3. var mini = "10" - 5;  
   **mini = 5**  
   
4. var order = 1 + 2 + "pizza";  
   **order= "3 pizza"**  
   (+ 연산자는 왼쪽에서부터 실행됨)  
</br>  
  
### 4. 문자열끼리 비교할 수도 있음.  
  ##### [example]  
1. "망고" < "바나나"  
  사전에서 ㅁ이 ㅂ 보다 앞에 나옴. 그래서 망고가 더 큼.  
  
2. "mango" < "Mango"  
   문자열의 순서는 유니코드 값을 사용함.  
   **true**
   
 
