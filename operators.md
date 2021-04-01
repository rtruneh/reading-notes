- Evaluating Conditions: these characters compare two values and return either true or false.
    - '==' is equal to, if the two values are similar it will return true.
    - '!=' is NOT equal to, if the two values aren't similar it will return true.
    - '===' is a strict equal, which means the values need to be exactly alike to get a *true* return.
    - '!==' is a strict not equal, meaning they can be similar to return true. 

- Structuring Comparison Operators
    - Every condition is made up of one operator and two operands. The operands are placed on each side of the operator (see below for example).
    > '(score <= pass)'
    > Score and pass are the *operands* and the '<=' is the *operator*
###### pages 150-151

- Logical Operators allow you to compare the results of more than one comparison operator.
    >'(( 5 < 2 ) && (2 >= 3))'
    > The values within the parenthesis are *expressions*, the '&&' is the *logical operator*. 
    - '&&' means *logical and*, it tests more than one condition
    - '||' means *logical or*, it tests at least one condition
    - '!' means *logical not* and inverts a single boolean value
    ###### pages 156-157

- Loops: check a condition.
    - If the condition runs true the code block will run and it will be checked again until the condition returns false. 
    - There are three types: 
        - **FOR** when needing to run a code a specific number of times
        - **WHILE** if you don't know how many times to run the code
        - **DO WHILE** to run the condition at least once regardless of outcome
    - Loop counters is used by the **FOR** loop that instructs the code a certain number of times. 
        > 'var i = 0;' *initializes* a variable and sets it to zero
        > 'i < 10;' is the *condition* that tells it how many times to run
        > 'i++' is the *update* that adds one to the counter every run
###### pages 170-173
