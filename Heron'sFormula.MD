The code below shows you how to create a program that finds the area of a triangle just by knowing the sides you input:
```java
Disp "INPUT A" //(This asks the user to input the length of side A)
Input A //(This inputs the length of side A)
Disp "INPUT B" //(This aks the user to input the length of side B)
Input B //(This inputs the length of side B)
Disp "INPUT C" //(This asks the user to input the length of side C)
Input C //(This inputs the length of side C)
(A+B+C)/2->S //(This finds the value of S by dividing the perimeter by 2; the arrow stores this value as S)
√(S(S-A)(S-B)(S-C))->D //(This performs Heron's formula and stores the answer as D)
Disp "AREA IS:" //(This displays the AREA IS:)
Disp D //(This displays D which contains the area of the triangle)
```
