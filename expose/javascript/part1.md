1. values added: 20
2. final result: 20
3. values added: 20
4. line 13 returns an error because result is delcared with the keyword let inside a block. Line 13 tries to use result outside of the scope so it returns an error.
5. The code returns an error because result is declared as a const, and we tried to reassign values to result in line 7, which is not allowed and causes an error.
6. The same reason as question 5, and also that consts is treated the same way as let, so line 13 also tries to access a variable outside of its scope, which also causes an error.