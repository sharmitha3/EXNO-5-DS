# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding:
~~~
import pandas as pd
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[0,1,4,9,16,25]
plt.plot(x,y)
import matplotlib.pyplot as plt
x=[1,2,3,4,5]
y=[5,6,7,8,9]
plt.plot(x,y)
plt.xlabel('x aixs')
plt.ylabel('y axis')
plt.title('simple line')
plt.show()
x1=[1,2,3,4]
y1=[4,3,2,1]
plt.plot(x1,y1,label="line 1")

x2=[5,6,7,8]
y2=[8,7,6,5]
plt.plot(x2,y2,label="line 2")

plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title("simple 2 line graph")
plt.legend()
plt.show()
x=[1,2,3,4,5,6]
y=[6,7,3,4,5,2]
plt.plot(x,y,color="green",linestyle="dashed",linewidth = 3,marker='o',markerfacecolor="blue",markersize=12)
plt.ylim(1,10)
plt.xlim(1,10)
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.title("customization")
plt.show()
import matplotlib.pyplot as plt
x_v=[0,1,2,3,4]
y_v=[2,3,4,5,6]
plt.scatter(x_v,y_v,s=30,color="green")
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title("scatter plot")
plt.show()
plt.savefig('Test.png')
plt.plot(x_v,y_v,"g*",linestyle="dashed",linewidth=3,markersize=10)
plt.title("2d diagram")
import numpy as np
np.pi
x=np.arange(0,4 * np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="red")
plt.legend(["y1","y2"])
plt.show()
x=[5,6,7,8]
y=["a","b","c","d"]
plt.bar(x,y,color="green")
plt.show()
x=[5,6,7,8]
y=["a","b","c","d"]
plt.barh(x,y,color="green")
plt.show()
x=[1,2,3,4,5]
y=[5,4,3,6,1]
c1=["red","green"]
c2=["blue","green"]
plt.bar(x,y,width=0.6,color=c2)
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.title("bar chart")
plt.show()
x=[1,2,3]
y=[5,6,7]
x2=[4,11,10]
y2=[8,9,12]
plt.bar(x,y,color="r")
plt.bar(x2,y2,color="b")
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.show()
a=[2,5,6,10,15,17,30,40,50,66,70,77,88,89]
range=(0,100)
bins=10
plt.hist(a,bins,range,color="g",histtype="bar",rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title("my histogram")
plt.show()
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins =10,color="blue",alpha=0.5)
plt.show()
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
a,b=plt.subplots()
b.boxplot(data)
b.set_title("box plot")
b.set_xlabel("data")
b.set_ylabel("values")
l=["python","C++","C","java"]
sizes=[215,130,244,222]
colors=["r","orange","yellow","b"]
explode=(0,0,0,0)
plt.pie(sizes,explode=explode,labels=l,colors=colors,
autopct="%1.1f%%",shadow=True)
plt.axis('equal')
plt.show()
~~~
# Output:
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/d9b8c0ff-c58b-4fd2-a5df-2891fd661ba3)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/a2dace33-d634-4af2-93b4-ba5f3be8e42c)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/24decf63-d356-4a26-84b9-8ca69881a488)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/a80c07d5-830c-42fd-9e42-54cb7753c243)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/b5586886-25e8-446e-84e9-772c5ce1e931)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/9f994cbd-ab39-40bb-ad4a-313add274291)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/fe931589-a814-4ac6-aa08-7af6db44235a)
![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/6f6deb40-eae7-4921-bcca-35803663a307)

![image](https://github.com/sharmitha3/EXNO-5-DS/assets/145974496/81550a4f-034d-4e23-8761-9cc78c77997f)

# Result:
The program to perform data visualization using the matplotlib Python library for the given data was successfully executed.
