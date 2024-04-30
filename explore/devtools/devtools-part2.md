1. The bus was that instead of treating the inputs num1 and num2 as numbers, they were treated as strings. Hence, when the input was 2+2, the answer was being given as '22' instead of 4.
2. I fixed it by prefixing Number - Number(num1) and Number(num2) to boht of them so that they are treated as numbers rather than strings.
