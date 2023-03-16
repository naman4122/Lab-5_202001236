# Lab-5_202001236

## Name: Naman patel
## ID: 202001236

#### Tool: *Pylint*

* I used Pylint to find error of the code http://surl.li/fnbxk

* the error are shown below:

![image](https://user-images.githubusercontent.com/84762377/225582710-118bf5a0-dc60-4dc2-b42b-4b9cfe607c8d.png)

#### Analysis of error:


#### 1> error of new line
       calculator.py:93:0: C0304: Final newline missing (missing-final-newline)

 -> This error removed by giving extra line.
 
 #### 2> Error of variable does not confirm
        calculator.py:12:4: C0103: Variable name "n2" doesn't conform to snake_case naming style (invalid-name)
        calculator.py:11:4: C0103: Variable name "n1" doesn't conform to snake_case naming style (invalid-name)
        calculator.py:26:4: C0103: Variable name "n1" doesn't conform to snake_case naming style (invalid-name)
        calculator.py:27:4: C0103: Variable name "n2" doesn't conform to snake_case naming style (invalid-name)
        calculator.py:37:0: C0103: Constant name "c" doesn't conform to UPPER_CASE naming style (invalid-name)
        
 -> solve by moving the defination of my print to main() is one way to supress the message.
     
#### 3> Missing docstring function error
       calculator.py:17:0: C0116: Missing function or method docstring (missing-function-docstring)
       calculator.py:25:0: C0116: Missing function or method docstring (missing-function-docstring)
       calculator.py:32:0: C0116: Missing function or method docstring (missing-function-docstring)
       calculator.py:5:0: C0116: Missing function or method docstring (missing-function-docstring)
       calculator.py:10:0: C0116: Missing function or method docstring (missing-function-docstring)
       
 -> Implementing the function docstring in file

