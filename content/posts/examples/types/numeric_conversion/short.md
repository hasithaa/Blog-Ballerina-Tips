
Compile time error <i class="fas fa-times-circle icon fa-fw"></i> 

```ballerina
float num1 = 10.0;
decimal num2 = 10 + num1; // error
int num3 = 1.0; // error - floating point literal on the right-hand side.
```

With type conversion <i class="fas fa-check-circle icon fa-fw"></i> 

```ballerina
float num1 = 10.0;
decimal num2 = 10 + <decimal>num1;
int num3 = <int>num1;
int num4 = <int>1.0; // Literal
```