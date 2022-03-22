# NumericalErrorsAndPropagation
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

# Table of Contents
1. [Floating point representation](#id-section1)
2. [Machine epsilon and rounding error](#id-section2)
3. [Error propagation and estimation](#id-section3)
4. [Comparing two floats](#id-section4)
5. [Minimize the error](#id-section5)

## <div id='id-section1'/>
## Floating point representation 
 - In modern computer architectures like RISC-V, arm, a64 and x86, [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754) standard is used for floating point representation.
 - [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754) use the [scientific notation](https://en.wikipedia.org/wiki/Scientific_notation) where every number can be represented as (−1)^sign × mantissa × base^exponent where the mantissa is a number smaller than the exponent.

**Example** : ![Alt text](assets/scientific_notation_example.png?raw=true "Example")

 - For modern architectures the base is **2**. 
 - Based on the number of bits there are multiple floating point number(32, 64, 128, 80 also exists). 32bit floting point number is structured like this (sign 1 bit, mantissa 23 bits, exponent 8 bits) where the fact that the number is binary is used and the mantissa implicitly start with 1 (most of the time) which give the mantisa one extra bit of information (24)
 - The [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754) cannot represent every possible number. Like integer numbers, floats create grid on real axis but unlike integers this grid is not equidistant. Numers are denser around the zero and get sparse with rise of the exponent.
 - [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754) supports special cases like [signed zeroes](https://en.wikipedia.org/wiki/Signed_zero), **infinity**, **nans** and [Subnormal number](https://en.wikipedia.org/wiki/Subnormal_number)

## <div id='id-section2'/>
## Machine epsilon and rounding error

## <div id='id-section3'/>
## Error propagation and estimation

## <div id='id-section4'/>
## Comparing two floats

## <div id='id-section5'/>
## Minimize the error

