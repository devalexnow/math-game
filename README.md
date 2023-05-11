## **Sprint Math Game**
#### made in JavaScript
<br>

***

### **About the project**

#### The project involves timing events as well as generating random correct and incorrect math equations. There are three different views within the game container: the splash page, the game page, and the score page. The best scores are stored in local storage, so if you refresh the page, the score will still be there.
<br>

*** 

### **How it works**
#### You start on a **splash screen** where you can see some radio buttons. This allows you to select one type of round that you want to try. There is also a best score for each corresponding number of equations. If you select the button and click start, you will see a countdown that’s accomplished using some set timeouts.
<br>

#### On the **game page**, the first element is highlighted. This is the equation that you are going to evaluate. You have a series of multiplication equations. There’ll be random number of correct and incorrect equations that are generated. You have to evaluate whether this equation is correct or incorrect. As you do that, it scrolls down automatically to the next equation.
<br>

#### It starts a timer when you click the button for the first time, and it stops the timer when you reach the end. Then it transfers to the **score page**, where you can see your time, which contains the base time and penalties (0.5 sec for each mistake). Click „Play again" to return to the splash page.
