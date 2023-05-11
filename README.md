# **Sprint Math Game**
### made in JavaScript

## **About the project**

The project involves:
1. **Timing events** (countdown),
2. **Random** correct and incorrect multiplication **equations**,
3. **Random ratio** of correct and incorrect answers,
4. **Three different views** within the game container: 
    - the splash page, 
    - the game page, 
    - the score page,
5. The best scores stored in **local storage**

 
## **How it works**

You start on a **splash screen** with few radio buttons. This allows you to select one type of round that you want to try. There is also a best score for each corresponding number of equations. If you select the button and click start, you will see a countdown that’s accomplished using some set timeouts.

On the **game page**, the first element is highlighted. This is the equation that you are going to evaluate. There’ll be random ratio of correct and incorrect equations that are generated. You have to evaluate whether this equation is correct or incorrect. As you do that, it scrolls down automatically to the next equation.

It starts a timer when you click the button for the first time, and it stops the timer when you reach the end. Then it transfers to the **score page**, where you can see your time, which contains the base time and penalties (0.5 sec for each mistake). Click „Play again" to return to the splash page.