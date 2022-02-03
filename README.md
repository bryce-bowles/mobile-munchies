# Mobile Munchies
Mobile Munchies is deciding how much of each type of juice to prepare for the week. Given the ingredients and cost, a python optimization model using Pyomo and GLPK determined the optimal amount of each type of lemonade to produce so the profits maximized subject to the constraints. 
([Report File](MobileMunchies-Report.pdf))


# Mobile Munchies Assignment
Bryce Bowles

January 27, 2020


### 1	Problem
Mobile Munchies is deciding how much of each type of juice to prepare for the week. They sell at most four gallons of peach lemonade and two gallons of raspberry lemonade each week. The amount of sugar available is 12 cups, and they can pack up to five pints of concentrated juice. A gallon of peach lemonade requires one pint of juice and four cups of sugar and a gallon of raspberry lemon- ade requires two pints of juice and three cups of sugar. Each gallon of peach lemonade sold produces a profit of $8 and each gallon of raspberry lemonade sold produces a profit of $12.

### 2	Data
Let
1. J ={peach, raspberry}be the set of lemonades
2. profiti =the profit in dollars from a cup of lemonade i, for i ∈ J
3. juiceReqi =pints of juice required for lemonade i, for i ∈ J 
4. sugarReqi =cups of sugar required for lemondade i, for i ∈ J
5. demandi =gallons demanded for lemonade i, for i ∈ J
6. juiceAvail =total pints of juice available
7. sugarAvail =total cups of sugar available
 

### 3	Objective in Words
Determine the amount of each type of lemonade to produce so that the profit is maximized subject to the following constraints:
*	No more than 12 cups of sugar are available.
*	No more than 5 pints of juice are available.
*	No more than 4 gallons of peach can be made.
*	No more than 2 gallons of raspberry can be made.

### 4	Algebraic Formulation
<img width="432" alt="image" src="https://user-images.githubusercontent.com/65502025/152344478-3cdca7b6-99f9-4546-b585-371ab8bf8a76.png">

### 5	Implementation
See attached Jupyter Notebook file, MobileMunchiesSolution.ipynb, for the im- plementation and solution of the model using Pyomo and GLPK.

### 6	Interpret the Results
The optimal solution is for Mobile Munchies to produce 1.8 gallons of raspberry lemonade and 1.6 gallons of peach lemonade and the optimal objective function value is $33.60.
