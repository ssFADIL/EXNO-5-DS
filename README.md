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

# Coding and Output:
~~~
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
~~~
<img width="548" height="604" alt="image" src="https://github.com/user-attachments/assets/34abf7e1-283b-4d16-82fa-a697b39cac4e" />

~~~
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
~~~
<img width="585" height="607" alt="image" src="https://github.com/user-attachments/assets/7dcd8487-e07c-4ef8-9357-b1d72a4bd5cc" />

~~~
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
~~~
<img width="745" height="576" alt="image" src="https://github.com/user-attachments/assets/b6f4ab3b-6676-4442-be5b-a29322ecd289" />

~~~
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
~~~

<img width="532" height="281" alt="image" src="https://github.com/user-attachments/assets/17fb9936-19c0-4f1b-8de1-55c4c002325f" />

~~~
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
~~~

<img width="514" height="320" alt="image" src="https://github.com/user-attachments/assets/7b24ef3a-a3f3-41f3-bf7b-b0872ca5172a" />

~~~
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
~~~

<img width="472" height="285" alt="image" src="https://github.com/user-attachments/assets/96479360-21d6-47fc-a4fa-8ea28db6c959" />
~~~
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
~~~

<img width="511" height="241" alt="image" src="https://github.com/user-attachments/assets/6aa623f3-a982-4229-9c29-6e4aa3af2f3c" />

~~~
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
~~~

<img width="470" height="324" alt="image" src="https://github.com/user-attachments/assets/8d707b2f-514c-438e-bdb7-300a366bf033" />















# Result:
 The experiment has been verified successfully
