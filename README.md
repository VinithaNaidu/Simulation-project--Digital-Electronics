# TITTLE

# THEORY
With the help of the K-map method, we can find the simplest POS and SOP expression, which is known as the minimum expression.
A visual way to simplify logic expressions.It gives the most simplified form of the expression.The K-map is a systematic way of simplifying Boolean expressions.
Simplification of logic expression using Boolean algebra is awkward because:
it lacks specific rules to predict the most suitable next step in the simplification process
it is difficult to determine whether the simplest form has been achieved.
A Karnaugh map is a graphical method used to obtained the most simplified form of an expression in a standard form (Sum-of-Products or Product-of-Sums).
The simplest form of an expression is the one that has the minimum number of terms with the least number of literals (variables) in each term.
By simplifying an expression to the one that uses the minimum number of terms, we ensure that the function will be implemented with the minimum number of gates.
By simplifying an expression to the one that uses the least number of literals for each terms, we ensure that the function will be implemented with gates that have the minimum number of inputs.


# LOGIC DIAGRAM
![image](https://github.com/VinithaNaidu/Simulation-project--Digital-Electronics/assets/121166004/a5586227-4ea3-4a4e-821a-1311272f68c5)


# NETLIST DIAGRAM

![image](https://github.com/VinithaNaidu/Simulation-project--Digital-Electronics/assets/121166004/87ae63aa-7a7f-4d9d-b342-56a4ae001136)

# TIMING DIAGRAM
![image](https://github.com/VinithaNaidu/Simulation-project--Digital-Electronics/assets/121166004/cc33480d-cc8f-47d6-902e-63c9cdedf409)


# PROGRAM
DEVELOPED BY D.VINITHA NAIDU
REG NO. : 212222230175
```
module sp(d,a,b);
input a,b;
output d;
wire f;
not(f,a);
or (d,f,b);
endmodule
```

# REFERENCE
