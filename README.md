# JS_PRECISE_CALC
An implementation of precise calculation for FLOAT types in JavaScript

Calculating of FLOAT types in JavaScript sometimes results in incorrect results due to insufficient precision in mantissa representation. This makes use of JavaScript FLOAT type calculations insufficient, when it comes to calculation precision need for production environment.

This code helps to mitigate that. It can calculate precisely up to 15 decimal places.

To implement it in your solution, see function PreciseCalculation(NUM1, NUM2, TYPE) in the source code of PRECISE_CALCULATION.HTM, where NUM1 is source operand 1, NUM2 is source operand 2 and TYPE is operator type represented as string/char (possible values: '+', '-', '/' , '*'). Result returned is float in decimal base.

<img width="1920" height="1080" alt="P1" src="https://github.com/user-attachments/assets/4bc64251-30ad-479f-87f5-c63c9749a507" />
<img width="1920" height="1080" alt="P2" src="https://github.com/user-attachments/assets/70c73932-c0a5-4a77-a536-56d6c288ed27" />
