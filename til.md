# Today I learn

## 2023-11-06

- `printf` – reusing argument
    ```C
    printf("%1$s %2$s %1$s %2$s %1$s\n", "ECHO", "ACHE"); // ECHO ACHE ECHO ACHE ECHO
    ```

- `sprintf` vs `printf`

## 2023-11-07

- Pointer arithmetic
    ```C
    char buffer[] = "Hello world!";
    int len = 0;
    for (char *p = &buffer[0]; *p; ++p, ++len)
        ;
    printf("%d\n", len); // 12
    ```

- Arithmetic sequence sum formula
    ```C
    int n = 6; // the number of terms
    int a = 2; // the first term
    int d = 2; // the common difference between the terms
    int sum = a * n + (n * (n - 1) * d) / 2;
    printf("%d\n", sum); // 2 + 4 + 6 + 8 + 10 + 12 = 42
    ```

## 2023-11-09

- Be cautious when working with arithmetic operator
    - Differentiate between `int` and `float` type
- Ad-hoc problem
    - Chess board
    - Dice