# Breaks and Continues
BREAKS provide an early exit from FOR, WHILE, and DO WHILE

* Causes the innermost enclosing loop or switch to be exited immediately.

* Useful to stop looping when a condition is met.

* CONTINUES will cause a loop to go the top of the loop.

* Useful to skip input.
```c
int i = 0;               //iterating variable
int firstNumber = 0;    //numerator
int secondNumber = 0;   //denominator

for(i = 0; i < 10; i++) //loops 10 times
{
    printf("x %% y \n");    //prints necessary format
    _flushall();            //clears all open streams
    scanf("%d %% %d", &frstNumber, &secondNumber);
    if (secondNumber == 0)  //checks for "divide by 0"
    {
        continue;           //skips "divide by 0"
    }
    printf("result: %2f \n", (float)firstNumber / secondNumber);
}
```

## DEMO LAB 6
## PERFORMANCE LAB H
