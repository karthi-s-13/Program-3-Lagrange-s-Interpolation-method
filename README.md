# Program 3: Lagrange's Interpolation method

## Question:

Using Lagrange interpolation formula, find the value corresponding to 𝒙 = 𝟏𝟎 from the
following table 

| x   | 0  | 1  | 2  | 4  | 5  | 6  |
| --- | -- | -- | -- | -- | -- | -- |
| y   | 1  | 14 | 15 | 5  | 6  | 19 |

## Aim:

To find the interpolating functional value of y at x = 10 by using Lagrange's method.

## Algorithm:

Step 1: Get the value of x

Step 2: Get the value of y

Step 3: for i = 0 to 6

Step 4: for j = 0 to 6

$$
if i ! = j
$$

$$
prod = prod * ( S - n [j])/(x [i] - n[j])
$$

$$
Sum = sum + pred * y[i]
$$

Step 5: Print the value of y

## Program:
```
x= [0,1,2,4,5,6]
y= [1,14,15,5,6,19]
s=float (input ("Enter the value of x to be in: "))
sum=0
for i in range (0,6):
 prod=1
 for j in range (0,6):
 if i!=j:
 prod=prod*(s-x[j])/(x[i]-x[j])
 sum=sum+prod*y[i]
print ("The functional value is %.4f"%sum) 
```

## Output:
Enter the value of x to be in: 10
The functional value is 311.0000 

## Result:
the interpolated value of y is obtained
