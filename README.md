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
LINE PLOT:
```
import matplotlib.pyplot as plt

marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
```

<img width="576" height="432" alt="image" src="https://github.com/user-attachments/assets/ee143638-a987-4c6d-89e7-749ce3389379" />

SCATTER PLOT:

```
import matplotlib.pyplot as plt
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
```

<img width="552" height="413" alt="image" src="https://github.com/user-attachments/assets/3f1ad590-22d1-408e-82aa-293a7d2a6817" />

PIE CHART:
```
import matplotlib.pyplot as plt
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="440" height="401" alt="image" src="https://github.com/user-attachments/assets/46c7e700-cb1b-4573-b2e9-6e3f6a6caf4d" />

AREA CHART:
```
import matplotlib.pyplot as plt
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
```
<img width="556" height="413" alt="image" src="https://github.com/user-attachments/assets/7d17829a-ba8c-45fe-85fb-a269e87d348c" />

BAR CHART:

```
import matplotlib.pyplot as plt
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/9f8c42e6-72cd-4af0-b022-6d1051c579a0" />

HISTOGRAM:

```
import matplotlib.pyplot as plt
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="534" height="413" alt="image" src="https://github.com/user-attachments/assets/81caa3e5-f9fe-4ea4-afa2-45a52ffce3f0" />

BOX PLOT:
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0, scale=0.5, size=100)
data
```
<img width="725" height="455" alt="image" src="https://github.com/user-attachments/assets/cbc220dc-5b07-4477-9e39-e6c1f65f375c" />

```
import matplotlib.pyplot as plt

plt.boxplot(data)
plt.xlabel('Data')
plt.ylabel('Values')
plt.title('Box Plot')
```
<img width="578" height="455" alt="image" src="https://github.com/user-attachments/assets/d055bdab-6585-4f91-91bc-e6a845eaa36a" />

# Result:
   Thus,all the visualization techniques of matplotlib has been implemented
