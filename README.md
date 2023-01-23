# devops-bootcamp-project-10
Demo for Module 13: Python

### Project 1: Countdown app
objective: code app that returns remaining days from now till date of goal defined

1. import built in module, datetime

2. create user input and save in variable

3. manipulate the user input data to return the correct data we want - goal as a string type + date as a date type

4. make use of in-built fn from datetime module to calculate the output 

5. print out the final output for the user

![Capture d’écran 2023-01-23 à 09 23 07](https://user-images.githubusercontent.com/62488871/213994233-a65c1248-49c5-4bac-bd91-ac7b5358df40.png)

-----

### Project 2: Automation w Python
objective: read spreadsheet file and automate tasks

1. import spreadsheet file by using imported package openpyxl - pip install openpyxl

![Capture d’écran 2023-01-23 à 22 02 02](https://user-images.githubusercontent.com/62488871/214157006-41bc41ea-9d79-42b8-99b5-cc59d0880607.png)

![Capture d’écran 2023-01-23 à 22 06 34](https://user-images.githubusercontent.com/62488871/214157046-2820f0cb-8deb-4948-a2d2-eeded507c046.png)

2. create dictionary with all suppliers and their respective number of products, from the spreadsheet data

![Capture d’écran 2023-01-23 à 22 20 50](https://user-images.githubusercontent.com/62488871/214157109-30fe9836-24a5-48f4-83dd-f68d5c4c4214.png)

3. create another dictionary with all suppliers and their respective total value of inventory (inv * price), from the spreadsheet data

![Capture d’écran 2023-01-23 à 22 37 03](https://user-images.githubusercontent.com/62488871/214157175-7cd0e0ef-26c7-4fd7-8de2-f6fc70e27719.png)

4. create another dictionary with all products with less than 10 inventory, from the spreadsheet data

![Capture d’écran 2023-01-23 à 22 37 07](https://user-images.githubusercontent.com/62488871/214157217-1764ca5d-e187-4b37-8627-c915706f691e.png)

5. write to spreadsheet by writing inv value for each product into spreadsheet

![Capture d’écran 2023-01-23 à 22 42 15](https://user-images.githubusercontent.com/62488871/214157259-e150e821-9e60-44fe-bbfb-149978ffd21a.png)
