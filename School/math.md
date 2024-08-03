Delphi provides a variety of mathematical functions through the `Math` unit. Below is a list of some commonly used mathematical functions along with examples for each:

### Basic Mathematical Functions

1. **Abs**: Returns the absolute value of a number.
   ```delphi
   var
     num: Integer;
     absValue: Integer;
   begin
     num := -5;
     absValue := Abs(num); // absValue = 5
   end;
   ```

2. **Sqr**: Returns the square of a number.
   ```delphi
   var
     num, sqrValue: Integer;
   begin
     num := 4;
     sqrValue := Sqr(num); // sqrValue = 16
   end;
   ```

3. **Sqrt**: Returns the square root of a number.
   ```delphi
   var
     num, sqrtValue: Double;
   begin
     num := 16.0;
     sqrtValue := Sqrt(num); // sqrtValue = 4.0
   end;
   ```

4. **Exp**: Returns the exponential of a number.
   ```delphi
   var
     num, expValue: Double;
   begin
     num := 1.0;
     expValue := Exp(num); // expValue = 2.71828182845905
   end;
   ```

5. **Ln**: Returns the natural logarithm of a number.
   ```delphi
   var
     num, lnValue: Double;
   begin
     num := 2.71828182845905;
     lnValue := Ln(num); // lnValue = 1.0
   end;
   ```

6. **Power**: Returns a number raised to a specified power.
   ```delphi
   var
     base, exponent, result: Double;
   begin
     base := 2.0;
     exponent := 3.0;
     result := Power(base, exponent); // result = 8.0
   end;
   ```

7. **Log10**: Returns the base-10 logarithm of a number.
   ```delphi
   var
     num, log10Value: Double;
   begin
     num := 100.0;
     log10Value := Log10(num); // log10Value = 2.0
   end;
   ```

8. **Max**: Returns the larger of two values.
   ```delphi
   var
     a, b, maxValue: Integer;
   begin
     a := 5;
     b := 10;
     maxValue := Max(a, b); // maxValue = 10
   end;
   ```

9. **Min**: Returns the smaller of two values.
   ```delphi
   var
     a, b, minValue: Integer;
   begin
     a := 5;
     b := 10;
     minValue := Min(a, b); // minValue = 5
   end;
   ```

### Trigonometric Functions

1. **Sin**: Returns the sine of an angle (in radians).
   ```delphi
   var
     angle, sinValue: Double;
   begin
     angle := Pi / 2; // 90 degrees in radians
     sinValue := Sin(angle); // sinValue = 1.0
   end;
   ```

2. **Cos**: Returns the cosine of an angle (in radians).
   ```delphi
   var
     angle, cosValue: Double;
   begin
     angle := 0; // 0 degrees in radians
     cosValue := Cos(angle); // cosValue = 1.0
   end;
   ```

3. **Tan**: Returns the tangent of an angle (in radians).
   ```delphi
   var
     angle, tanValue: Double;
   begin
     angle := Pi / 4; // 45 degrees in radians
     tanValue := Tan(angle); // tanValue = 1.0
   end;
   ```

4. **ArcSin**: Returns the arc sine (inverse sine) of a number.
   ```delphi
   var
     num, arcSinValue: Double;
   begin
     num := 1.0;
     arcSinValue := ArcSin(num); // arcSinValue = Pi / 2
   end;
   ```

5. **ArcCos**: Returns the arc cosine (inverse cosine) of a number.
   ```delphi
   var
     num, arcCosValue: Double;
   begin
     num := 1.0;
     arcCosValue := ArcCos(num); // arcCosValue = 0
   end;
   ```

6. **ArcTan**: Returns the arc tangent (inverse tangent) of a number.
   ```delphi
   var
     num, arcTanValue: Double;
   begin
     num := 1.0;
     arcTanValue := ArcTan(num); // arcTanValue = Pi / 4
   end;
   ```

7. **ArcTan2**: Returns the arc tangent of Y/X.
   ```delphi
   var
     y, x, arcTan2Value: Double;
   begin
     y := 1.0;
     x := 1.0;
     arcTan2Value := ArcTan2(y, x); // arcTan2Value = Pi / 4
   end;
   ```

### Hyperbolic Functions

1. **Sinh**: Returns the hyperbolic sine of a number.
   ```delphi
   var
     num, sinhValue: Double;
   begin
     num := 1.0;
     sinhValue := Sinh(num); // sinhValue ≈ 1.1752011936438014
   end;
   ```

2. **Cosh**: Returns the hyperbolic cosine of a number.
   ```delphi
   var
     num, coshValue: Double;
   begin
     num := 1.0;
     coshValue := Cosh(num); // coshValue ≈ 1.5430806348152437
   end;
   ```

3. **Tanh**: Returns the hyperbolic tangent of a number.
   ```delphi
   var
     num, tanhValue: Double;
   begin
     num := 1.0;
     tanhValue := Tanh(num); // tanhValue ≈ 0.7615941559557649
   end;
   ```

### Other Functions

1. **Ceil**: Returns the smallest integer greater than or equal to a number.
   ```delphi
   var
     num: Double;
     ceilValue: Integer;
   begin
     num := 1.7;
     ceilValue := Ceil(num); // ceilValue = 2
   end;
   ```

2. **Floor**: Returns the largest integer less than or equal to a number.
   ```delphi
   var
     num: Double;
     floorValue: Integer;
   begin
     num := 1.7;
     floorValue := Floor(num); // floorValue = 1
   end;
   ```

3. **Round**: Rounds a number to the nearest integer.
   ```delphi
   var
     num: Double;
     roundValue: Integer;
   begin
     num := 1.5;
     roundValue := Round(num); // roundValue = 2
   end;
   ```

4. **Random**: Returns a random number between 0 and 1.
   ```delphi
   var
     randValue: Double;
   begin
     randValue := Random; // randValue is a random number between 0 and 1
   end;
   ```

5. **RandomRange**: Returns a random integer within a specified range.
   ```delphi
   uses
     System.Math;
   
   var
     randValue: Integer;
   begin
     randValue := RandomRange(1, 100); // randValue is a random integer between 1 and 99
   end;
   ```

### Using the `Math` Unit

To access these functions, ensure you include the `Math` unit in the `uses` clause of your Delphi program:

```delphi
uses
  System.SysUtils, System.Math;
```

These examples provide a solid foundation for utilizing Delphi's math functions in your applications.