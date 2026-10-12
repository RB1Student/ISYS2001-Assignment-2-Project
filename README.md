# ISYS2001-Assignment-2-Project
This is a Repository for Curtin ISYS2001 Assessment 2 Project and contains code/ Colab Notebook, Read me, Develop Diary and Commit History

The Application Is called Smart Statement. It turns Bankstatements in CSV file format into an interactive visualised dashboard and also has the feature of being connected Google Gemeni AI chatbot, to ask Finanicial Questions. This is because for personal finance, bank statements can be hard to understand due to the amount of the data in a table format so making it into a dashbaord makes it easy to understand. This is ment for Personal Finance, and the datasets provided to the the Smart Statement Program, are not real statements bank statement is to due to the risk of privacy If I did provide real bank statements.

*Quick Notes*
- For the developer Diary it in a ipynb format this is because I started Makeing it in Colab, after I Finished I then realised it Needed to be in MarkDown format, I tryed to use VScode to convert it over with a nbcovert Tool, which could covert,however left the image out, so the Developer Diary you should use to mark should be (Developer_Diary4a.ipynb) Found in Section 2.3 of this Project

Doing Some reseach I found out you can't Manually adjust the order of the files in the repo, so I decided to add the work in a naming Convention/code.
- ReadMe(By it Self)
- RM(Are the Photo for ReadMe)
- Application (By It Self
- 1 is [Project/Application Work]
- 2 is [Data]
- 3 IS [Developer Diary)
- 4 is [Testing]
- 5 Is [Early Colab Six Steps and PsuedoCode]

  For all the Current Files i've left the code out, since the code is for past notebooks/projects etc. All the content should be at the bottom of the repo

  **Input/outputs**

Inputs
- Name in the Account Tab
- CSV Bankstatement Data
- Filters in the Dashboard for Month and Category
- Google Gemeni Finance Chatbot Query/Question.

Output
- Name on Dashboard
- CSV bankstatement data displayed on dashboard
- Google Gemeni Chatbot answer questions
  

## **1.Running The application**
(Before Running Program Download the CSV dataset found in **section 2.1** of read me to be used in the program)

1. To first run the application go into Github and click on "Smart Statement Program" in the repo or section 2.5 of the read me "Smart Statement Program"
2. Once on the "Smart Statement Program" Page open in Colab Which should be in the top of the page

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/c9f1ec4a83bb861f93498949f4287bd5b5632c1f/RM1.png)
_GitHub "Smart Statement Program" Page_

3. Once in the Colab Folder Make sure Outputs are Cleared, which can be access in the run button in the ribbon and the then press the run icon which looks like play button


![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM2.png)
_Where to Clear the output_

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM3.png)

_The program run button_

4. Once you have pressed the Run Button the program will be below the code, so scroll down to the bottom of the Colab Cell.

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM4.png)
_The Program looks like when frist ran_

5. Since you are in the Account Tab, Input your Name into the name box and upload one of the provided csv bankstatement files like down below:

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM5.png)

_First where to enter your name, Second Where to upload the File_

6. If you made a mistake and pick the wrong CSV you can press the "Orange Clear Button" otherwise once you pick the CSV you want to upload press Load my CSV. Which can be seen down below

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM7.png)

_Clear button_

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM6.png)

_Load my Statement Button_

7. Once you have pressed the load Statement Button, you would automatically be moved in the dashboard, where you can explore and analyse your data in the dash board.

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM8.png)

_Dashboard Screen_

8. If you want to filter your data you can use the drop down to filter by Month or By Category near the top of the dashbaord which is shown below, this changes the dashboard and show infomation related to the filters you have picked:

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM9.png)

_Filters for Month and Category_

9. You can then use the chatbot by selecting the "ChatBot" in the program which is show below:

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM10.png)

_Tab for the chat bot_

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM11.png)

_Chat bot screen_

10. Type a question relation to your financial statement in the chatbot box and send. for example:
- What was largest Expense in December 2026?
- What are 3 ways I could lower my expenses?
- What is my Main souce of income?

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM12.png)

_Typing a question for the Finance Chat bot_

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM13.png)

_The results, which the Ai Google Gemeni Chat bot gave some good recommendations_

11. Lastly to Log out Click on the Account Tab, And Press the Red Log off button

![image alt](https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM%2014.png)

_Where to find the Account Tab_

![image alt][(https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/main/RM16.png)

_Where to Log off the application, (you have to Log off to put in another CSV File)_





## **2. Here are the relevant Files**

**2.1 The Date Sets**

**3 Months**
3 months Sample Bank Statement.csv

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/3%20months%20Sample%20Bank%20Statement.csv

**6 Months**
6 months Sample Bank Statement .csv

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/6%20months%20Sample%20Bank%20Statement%20.csv

**12 Months**
12 months Sample Bank Statement.csv

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/12%20months%20Sample%20Bank%20Statement.csv

**2.2 PsuedoCode+PlanCode and Colab six Step Evidence(First 3 steps)**
(Looking at the PsuedoCode now, the application uses aspects however followed it loosely, this was due to couple of reason, but mainly that Tkinter wasn't support in Colab, meaning I had to Change Code as I more like agile code concept in a way)

PsuedoCode+PlanCode.ipynb

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/PsuedoCode%2BPlanCode.ipynb

Colab_Six_Step_Evidance2_.ipynb

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/Colab_Six_Step_Evidance2_.ipynb

**2.3 The Developer Diary**
Developer_Diary4a.ipynb

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/Developer_Diary4a.ipynb

**2.4 Testing**
Testing2b.ipynb

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/Testing2b.ipynb

**2.5 Smart Statement Program**
Smart Statement  Program.ipynb

https://github.com/RB1Student/ISYS2001-Assignment-2-Project/blob/8effc42ef66a13c1afc9f44bfa84ef9f243c6861/Smart%20Statement%20%20Program.ipynb








