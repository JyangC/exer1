
Instruction
============

Identify at least three problems in the code of `TseitinTransformer` that violate the 
clean code criteria. Show an example of the code that has the problem, and explain 
why it is a problem. Briefly discuss what kind of changes will improve the code.

Fill in the template below with the problems you find in the code. The following 
shows an example of how to describe a problem in the code: 

> Problem X
> __________
> 
> - Description: the method `foo` is too long and has too many arguments, 
>   and its name does not clearly describe what the method does. It is hard 
>   to read and understand the code. 
> 
> - Code example: SomeClass.java:12-123 
>   ```java
>   public void foo(int a, int b, int c, int d, int e, int f) {
>      // code here (not shown in this code example)
>   }
>   ```
> - Explanation: The method `foo` has six arguments, which is too many. This is 
>   because the method does three different things at once, which also makes the 
>   method have a bad name and be too long.
> 
> - Suggestion: Since the method does three different things, it can be split into 
>   three separate methods, each with two arguments. The method names can then be 
>   `goodName1`, `goodName2`, and `goodName3`.


Code Review: `TseitinTransformer`
============

Problem 1
_________

- Description: <DESCRIPTION_FOR_PROBLEM_1>
- Code example: <FILE_NAME.java>:<LINE_NUMBERS>
  ```java
  CODE_OF_PROBLEM_1
  ```
- Explanation: <EXPLANATION_FOR_PROBLEM_1>
- Suggestion: <SUGGESTION_FOR_PROBLEM_1>

Problem 2
_________

- Description: <DESCRIPTION_FOR_PROBLEM_2>
- Code example: <FILE_NAME.java>:<LINE_NUMBERS>
  ```java
  CODE_OF_PROBLEM_2
  ```
- Explanation: <EXPLANATION_FOR_PROBLEM_2>
- Suggestion: <SUGGESTION_FOR_PROBLEM_2>

Problem 3
_________

- Description: <DESCRIPTION_FOR_PROBLEM_3>
- Code example: <FILE_NAME.java>:<LINE_NUMBERS>
  ```java
  CODE_OF_PROBLEM_3
  ```
- Explanation: <EXPLANATION_FOR_PROBLEM_3>
- Suggestion: <SUGGESTION_FOR_PROBLEM_3>


**Write more problems if you find them.**