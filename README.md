#psych403

Print exercises 

2. No variables show up in the variable editor

Variable exercises

2. yes all 6 variables show up in the variable editor 


3. python has no problems with two variables havin the same value
5. changing the value of letterX did not change the value on letter1
6. Changing the value of letter1 after setting letterx equal to letter1 did not change the value of letterx. letter x held the same value as letter1 when it was set equal prior to changeing the value of letter1

Boolean Exercises

1.Spyder indicates that the statement: print(1==1.0) is true, but the statement: print("1"=="1.0") is flase. It is possible that due to the addition of the quotation marks python specifies decimal spaces so even if the first decimal is zero it tells us the values are not the same.

2. Spyder indicates that both values are equivalent

3. 
a) print((1==1.0)or("1"=="1.0"))and(5==(3+2))

b) print(1==1.0)and(not"1"==1.0")and(5==(3+2))

c) print((1==1.0)or((5==(3+2))))or(not"1"=="1.0")

d)print(not"1"=="1.0")and(1==1.0)and(5==(3+2))

e)print(1==1.0)or("1"=="1.0")or(5==(2+3))

Operation Exercises
1. I am using python 3.8.10 and in this version both operations yeild the same answer of 2.5 not discriminating between decimal points
2. modulo is a remainder function so it returns the remainder of dividing two numbers
3. The double asterics function sets the second number has a exponent. The double forward slash function lets us know how many of the second number go into the first.
4. Python does follow order of operations

List Exercises
1. Oddlist=[1,3,5,7,9] did become a variable
2. no errors 
3. Python says that the list is 5 units 
4. the 'type' function says it is a class 'list'
5. inlist=list(range(1,100)) > print
6. yes all number between 0 and 100 appear in the list

Dictionary Exercises
1. about_me={"name":"yousif", "age":22, "year of study":4, "favfoods":["chicken", "steak", "bbq"]}
2. no errors after print and the type function ive the message <class 'dict'>
4. the len function says that the string is 4 units, python appers to count the number of variables rather than the value those varables are set to

Array exercises
1. The array printed as a list of floats rather than a mix of intigers and floats
2. The array is listed as containing only strings rather than strings and floats. It appears that python can only read arrays that consist of one type when using numpy
3. oddarray=np.array((list(range(1, 100, 2))))
4. logarray=(np.logspace(1, 5, 16))
