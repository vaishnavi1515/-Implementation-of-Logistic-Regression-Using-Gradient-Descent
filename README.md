# Implementation-of-Logistic-Regression-Using-Gradient-Descent

## AIM:
To write a program to implement the the Logistic Regression Using Gradient Descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import the required library and read the dataframe.
2.Write a function compute Cost to generate the cost function.
3.Perform iterations of gradient steps with learning rate.
4.Plot the Cost function using Gradient Descent and generate the required graph.

## Program:
```
/*
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

data=pd.read_csv("C:/Users/acer/Downloads/50_Startups.csv")
x=data["R&D Spend"].values
y=data["Profit"].values


x_mean=np.mean(x)
x_std=np.std(x)
x=(x-x_mean)/x_std


w=0.0
b=0.0
alpha=0.01
epochs=100
n=len(x)

losses=[]


for i in range(epochs):
    y_hat=w*x+b
    loss=np.mean((y_hat-y)**2)
    losses.append(loss)
    
    dw=(2/n)*np.sum((y_hat-y)*x)
    db=(2/n)*np.sum(y_hat-y)
    
    w-=alpha*dw
    b-=alpha*db


plt.figure(figsize=(12,5))

plt.subplot(1,2,1)
plt.plot(losses)
plt.xlabel("Iterations")
plt.ylabel("Loss(MSE)")
plt.title("Loss vs Iterations")

plt.subplot(1,2,2)
plt.scatter(x,y)
x_sorted=np.argsort(x)
plt.plot(x[x_sorted],(w*x+b)[x_sorted],color="red")
plt.xlabel("R&D Spend (scaled)")
plt.ylabel("Profit")
plt.title("Linear Regression Fit")

plt.tight_layout()
plt.show()

print(f"Final weight (w): {w}")
print(f"Final bias (b): {b}")

*/
```

## Output:

<img width="1278" height="588" alt="image" src="https://github.com/user-attachments/assets/56cda89b-130b-42ff-8d17-3f233c8eb0cb" />

## Result:
Thus the program to implement the the Logistic Regression Using Gradient Descent is written and verified using python programming.

