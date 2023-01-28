To prove by mathematical induction that a statement is true for all integers, we need to show two things:
```
    The statement is true for the base case (usually n = 0 or n = 1)
    If the statement is true for n = k, then it is also true for n = k+1
```
In this case, we want to prove that f(n) = 5^n + 8n + 3 is divisible by 4 for all integers n.
```
    Base case:
    For n = 0, f(0) = 5^0 + 8*0 + 3 = 3 which is divisible by 4.

    Inductive step:
    Assume that f(k) = 5^k + 8k + 3 is divisible by 4 for some integer k. We want to show that f(k+1) = 5^(k+1) + 8(k+1) + 3 is also divisible by 4.
    f(k+1) = 5^(k+1) + 8(k+1) + 3 = 5*(5^k) + 8k + 11 = 5(5^k + 4k + 3) + 11
    
    5*(5^k) + 8k + 11 you rewrite this 5(5^k + 4k + 3) + 11
Steps:
    Start with the original equation: f(k+1) = 5^(k+1) + 8(k+1) + 3
    Next, we can use the property of exponents that states (a^b) * (a^c) = a^(b+c) to simplify: f(k+1) = 5^(k+1) + 8(k+1) + 3 = 5^k * 5 + 8k + 11
    Now we can distribute the 5 on the right side of the equation: f(k+1) = 5^k * 5 + 8k + 11 = 5 * (5^k) + 8k + 11
    Now we can factor out the 5: f(k+1) = 5 * (5^k) + 8k + 11 = 5 * (5^k + 4k + 3) + 11
In this step by step explanation, we started with the original equation f(k+1) = 5^(k+1) + 8(k+1) + 3 , and then we used some mathematical properties such as the property of exponentiation (a^b) * (a^c) = a^(b+c) 
to simplify the equation and factor it out, and finally we get the equation f(k+1) = 5 * (5^k + 4k + 3) + 11
    
    
    
    
    Now we know that f(k) = 5^k + 8k + 3 is divisible by 4 so it means 5^k + 8k + 3 is divisible by 4 , and since 5 is divisible by 4 so 5*(5^k + 8k + 3) is divisible by 4 and we add 11 which is divisible by 4 so f(k+1) is also divisible by 4.
```
Therefore, by mathematical induction, we have shown that f(n) = 5^n + 8n + 3 is divisible by 4 for all n belongs to the set of all integers.
