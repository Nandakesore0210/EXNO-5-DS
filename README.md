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
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![381031647-6301b182-4939-4c1a-9b7e-d650d0b2ea05](https://github.com/user-attachments/assets/1a398a6a-ea71-4d80-bd00-b4b150d3c7dc)
```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
![381031784-3b1eff1a-1cea-4d6f-9af5-d66d43283b44](https://github.com/user-attachments/assets/159770f7-b865-4df8-9869-4cdd2d996200)
```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![381031915-8a3d101a-1c8c-4ffe-8aec-dc567f471be4](https://github.com/user-attachments/assets/194902ee-3fb7-479d-a799-bd127467fa14)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```
![381032200-4be5f7df-0c90-4ebd-8dff-1db82e475545](https://github.com/user-attachments/assets/7e8014f7-6d89-4bf6-a463-7aaa1b94b5a5)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![381032301-5e32ce9f-b83f-40ca-9962-1c72cb435ce6](https://github.com/user-attachments/assets/95a628aa-aae4-408f-b31d-263ea07e5f1c)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![381032426-4169b2d1-0da2-485a-83c5-21e6e3fa95b2](https://github.com/user-attachments/assets/d69f19e7-e690-42dc-afeb-ce41f379a39d)
```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![381032531-f4c39f0a-e2ae-4c25-85ea-d8e11c7918d5](https://github.com/user-attachments/assets/108346a3-c0cb-4ef9-9234-70a68304395f)
```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![381032724-167a1202-a3a0-412b-98d2-39c9a78251c1](https://github.com/user-attachments/assets/fb266ece-c693-4a8e-b806-32aeecd4aab1)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![381032889-d5b2ec53-5109-463d-9da1-3ea19ff0543a](https://github.com/user-attachments/assets/27b69cb1-6de5-4232-81e6-4a8963c21fb7)
```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```
![381033159-115b409b-10e8-4c75-b5f9-4a79e3765237](https://github.com/user-attachments/assets/d47b5bcd-c913-4826-b080-38f63c5a6b08)
```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![381033673-8c48c3c1-0213-480b-b47a-8d086d67e107](https://github.com/user-attachments/assets/3fab8ac6-d0b2-4252-9f8f-4614ecf04472)
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![381033781-3aef0f88-87fb-4bbd-a3ae-26505e26963e](https://github.com/user-attachments/assets/02504f39-29e7-4072-83d2-58006d04bb22)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```
y
```
array([11, 12, 13, 14, 15, 16, 17, 18, 19, 20])
```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![381034161-4af1c98f-c96f-4c80-b605-471be5c3f83c](https://github.com/user-attachments/assets/4f277dfc-a0a2-4eca-8200-c782d9045f0b)
```
y=x*x
y
```
array([ 0, 1, 4, 9, 16, 25, 36, 49, 64, 81])
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![381034512-9402e3fc-42df-4c5c-9850-9fe5daeced0a](https://github.com/user-attachments/assets/b74f0900-bea0-4197-8cb2-de2ccd8a5200)
```
np.pi
```
3.141592653589793
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![381034979-abcc3fc3-8d4e-4c87-af15-764da148b6a8](https://github.com/user-attachments/assets/0d9b1b15-7139-4e21-a4fd-560cce627673)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
![381035083-cd98e492-a569-49a3-ab15-2fad3a339749](https://github.com/user-attachments/assets/54a84c92-7bf4-4ca2-a809-9c67c9e9106d)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![381035234-ca7d6cd4-5cf4-4ed7-a069-af7299953188](https://github.com/user-attachments/assets/2cee1afb-d996-4869-9b98-72225e597e06)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,11]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![381035325-80c0a35b-aa12-4857-8d75-bcee800ee2f9](https://github.com/user-attachments/assets/4b431112-e6a2-4030-bf00-561e77302981)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
![381035407-9082c808-5c38-40d6-a8c5-6c83a36c5f11](https://github.com/user-attachments/assets/28014bc2-c044-4552-843d-f31ca6523c96)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![381036310-da00f154-036c-4d1c-8a2f-b6007108e912](https://github.com/user-attachments/assets/ded20fb4-2b6e-490a-a294-a1dc0c916ab1)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot'
```
![381036416-2091ed67-1f4d-499a-92a2-bdd8fd58598e](https://github.com/user-attachments/assets/110f4c6f-3c74-419e-a3d3-bc6a50d01e07)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![381036520-2116c6ef-b2e6-408f-a71a-5100628ac188](https://github.com/user-attachments/assets/065f774c-b008-42be-9540-b7b804e36437)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![381036760-7fcad1f8-abb5-4bd6-a06b-ee0da425cc32](https://github.com/user-attachments/assets/b6cafba0-7b51-40b2-bd86-e1225cb97c99)


# Result:
To Perform Data Visualization using matplot python library for the given datas is successful.

