# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here
![image](https://user-images.githubusercontent.com/119405017/211244295-711be6ca-e432-4c37-bae5-fc0ef0908e8e.png)


## DESIGN STEPS

### STEP 1:
Clone repository. Make all changes for the app

### STEP 2:
Test server

### STEP 3:
Finish program and push inn github

Write your own steps

## PROGRAM
from django.contrib import admin from .models import Employee,EmployeeAdmin

##Register your models here.

admin.site.register(Employee,EmployeeAdmin)

from django.db import models from django.contrib import admin

class Employee(models.Model): emp_id=models.CharField(primary_key=True,max_length=4,help_text="Employee ID") ename=models.CharField(max_length=50) post=models.CharField(max_length=20) salary=models.IntegerField() email=models.EmailField()

class EmployeeAdmin(admin.ModelAdmin): list_display=('emp_id','ename','post','salary','email')

Include your code here

## OUTPUT

Include the screenshot of your admin page.
![image](https://user-images.githubusercontent.com/119405017/211244568-bc101928-0245-443b-826d-ce92b0c2d66c.png)
![image](https://user-images.githubusercontent.com/119405017/211244597-6ea785ed-984c-4b03-8958-732336fb7a15.png)



## RESULT
The programm is executed successfully
