## Understanding Jest test coverage

```
-------------------|-----------|-----------|-----------|-----------|
File               |   % Stmts |% Branches |   % Funcs |   % Lines |
-------------------|-----------|-----------|-----------|-----------|
components/       |      88.1 |     77.78 |     78.57 |      88.1 |
  datepicker.js   |      88.1 |     77.78 |     78.57 |      88.1 |
-------------------|-----------|-----------|-----------|-----------|
All files          |      88.1 |     77.78 |     78.57 |      88.1 |
-------------------|-----------|-----------|-----------|-----------|
```

- Statement coverage: has each statement in the program been executed? (`z = x + y;`)
- Branch coverage: has each branch (also called DD-path) of each control structure (such as in if and case statements) been executed? (For example, given an if statement, have both the true and false branches been executed? Another way of saying this is, has every edge in the program been executed?)
- Function coverage: has each function (or subroutine) in the program been called?
- Line coverage: has each executable line in the source file been executed?

For each case, the percentage represents executed code vs not-executed code, which equals each fraction in percent format (e.g: 50% branches, 1/2).

sources: [Learn Istanbul](https://github.com/dwyl/learn-istanbul)
