# The-Football-Project
In this visualization you are able to choose two players using drop-down options:

![Mercury (1)](https://user-images.githubusercontent.com/45957874/208013242-8b52a2c1-29d7-4e1e-ac52-e686e655088e.gif)

You may then pick up to 5 attributes to compare between the players:

![Mercury (2)](https://user-images.githubusercontent.com/45957874/208013268-b6912a16-7eeb-4307-ba1a-92682004328b.gif)

And then you can run the program to create 3 visualizations that compare the data of the two player:

![Mercury](https://user-images.githubusercontent.com/45957874/208012946-287f34ad-e8d5-4c73-a9ea-47bcd2525e39.gif)


These visualization may also be downloaded as PDF or HTML files. To clear the data, click "clear runs" on the bottom left and it will go back to default options.

In the FootballProjectFinalVerision.ipynb file please change the follwing line of code to file path where the FPL_DATA_ALL.csv file is stored.

![image](https://user-images.githubusercontent.com/45957874/208026958-46992ca4-a95e-4668-a44c-ee49359086cf.png)

![image](https://github.com/user-attachments/assets/09e03a63-5b83-439d-ab55-392a5bd8eb57)

![image](https://github.com/user-attachments/assets/1d03047f-e3bd-40ab-96c2-efda484caf34)

To run this project, open up a terminal or command prompt and type:
```
pip install -r requirements.txt
```
to install the required libraries. Then you can run the command:
```
mercury run
```
to run the application in your local machine. Finally, open a web browser and
go to  http://127.0.0.1:8000 where you'll be able to interact with and create the visualizations.

If there are any issues you can run:
```
mercury add <path_to_notebook>
```
where <path_to_notebook> should be replaced by the file path to FootballProjectFinalVerision.ipynb. Then run:
```
mercury runserver --runworker
```
and then once again open a web browser and go to  http://127.0.0.1:8000 If you continue to experience issues
reach out to me at ti60490@umbc.edu
