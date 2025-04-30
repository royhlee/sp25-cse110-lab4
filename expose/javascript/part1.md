1. values added:  20
2. final result:  20
3. var has no block scope so outside of the if statement the variable result is still visible, this can lead to bugs outside of it's block scope which will be difficult to find.
4. values added:  20
5. A reference error is given because result is not definied outside of the if block making let result = 0; only exist for the first console log.
6. The error is on the next line result = num1 + num2; since const result = 0; declares result as a constant it cannot be reassigned.
7. The code stops at the type error which doesn't allow line 13 to print anything.