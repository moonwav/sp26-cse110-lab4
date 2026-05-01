# Part 2

1. Line 12 prints:
3  


---

2. Line 13 prints:
150  


---

3. Line 14 prints:
150  

---

4. The function returns:
[50, 100, 150]  

---

5. Line 12 causes an error:
`i` is declared with `let`, so it is block-scoped and not accessible outside the loop.

---

6. Line 13 causes an error:
`discountedPrice` is block-scoped (declared with `let`) and not accessible outside the loop.

---

7. Line 14 prints:
150  

---

8. The function returns:
[50, 100, 150]  

---

9. Line 11 causes an error:
`i` is block-scoped (`let`) inside the loop and cannot be accessed outside.

---

10.  Line 12 prints:
3  


---

11.  The function returns:
[50, 100, 150]  


---

12.
A. student.name  
B. student["Grad Year"]  
C. student.greeting()  
D. student["Favorite Teacher"].name  
E. student.courseLoad[0]

---

13.  Arithmetic

A. '3' + 2 → "32"  
Explanation: string concatenation  

B. '3' - 2 → 1  
Explanation: string converted to number  

C. 3 + null → 3  
Explanation: null is 0  

D. '3' + null → "3null"  
Explanation: string concatenation  

E. true + 3 → 4  
Explanation: true is 1  

F. false + null → 0  
Explanation: false → 0, null → 0  

G. '3' + undefined → "3undefined"  
Explanation: string concatenation  

H. '3' - undefined → NaN  
Explanation: undefined cannot convert to number  

---

14. Comparison

A. '2' > 1 → true  
Explanation: '2' → number  

B. '2' < '12' → false  
Explanation: string comparison (lexicographic)  

C. 2 == '2' → true  
Explanation: type coercion  

D. 2 === '2' → false  
Explanation: strict comparison  

E. true == 2 → false  
Explanation: true is 1  

F. true === Boolean(2) → true  
Explanation: any non-zero number is true 

---

15. Difference between == and ===  
`==` performs type coercion before comparison, while `===` checks both value and type without coercion.



---

17.  Result:
[2, 4, 6]  
Each element is passed to `doSomething`, which multiplies by 2.

---


19.  Output:
1  
4  
3  
2  
