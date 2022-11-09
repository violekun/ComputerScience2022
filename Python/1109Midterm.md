## ex 1:
```
f(n) = 1+2+3+....+(n-1)+n
     = f(n-1) + n
     
termination: f(1) = 1
recurrence  function : f(n) = f(n-1) + n


input: n
output: f(n) 
    print(f(10))
  
1.write a recursive function for f(n)
2.write a iterative function for f(n)
```
## ex 2:
```
f(n) = n!
     = 1*2*3*.....*n

input: n
output: f(n) 
    print(f(10))
  
1.write a recursive function for f(n)
2.write a iterative function for f(n)
```
## ex 3:
```
GCD:Greatest common divisor - Wikipedia
gcd(8,12)=4
https://en.wikipedia.org/wiki/Greatest_common_divisor

Euclidean algorithm
gcd(48,18)
= gcd(18,48%18)
= gcd(18,12)
= gcd(12,18%12)
= gcd(12,6)
= gcd(6,12%6)
= gcd(6,0)
= 6

output: gcd(n,m) 
print(gcd(48,18))

gcd(18,48)  ==> gcd(48,18)  
gcd(x,0) ==> return x
recurrence  function : 
  
1.write a recursive function for f(n,m)
2.write a iterative function for f(n,m)
```
