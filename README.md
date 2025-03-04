# Calcpad Readme  
  
Project Website: [https://calcpad.eu](https://calcpad.eu)  
  
Calcpad is free software for mathematical and engineering calculations. It represents a flexible and modern programmable calculator with Html report generator. It is simple and easy to use, but it also includes many advanced features:  
  
* real and complex numbers;  
* units of measurement (SI, Imperial and USCS);  
* custom variables and units;  
* built-in library with common math functions;  
* custom functions of multiple parameters f(x; y; z; ...);  
* powerful numerical methods for root and extremum finding, numerical integration and differentiation;  
* finite sum, product and iteration procedures;  
* modules, macros and string variables;  
* program flow control with conditions and loops;  
* "titles" and 'text' comments in quotes;  
* support for Html and CSS in comments for rich formatting;  
* function plotting, images, tables, parametric SVG drawings, etc.;  
* automatic generation of Html forms for data input;  
* professional looking Html reports for viewing and printing;  
* export to Word documents (\*.docx) and PDF;  
* variable substitution and smart rounding of numbers;  
* output visibility control and content folding;  
* support for plain text (\*.txt, \*.cpd) and binary (\*.cpdz) file formats.  
  
This software is developed using the C# programming language and the latest computer technologies. It automatically parses the input, substitutes the variables, calculates the expressions and displays the output. All results are sent to a professional looking Html report for viewing and printing.
  
![Sample](https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/Sample.png?raw=true)  
  
## Fields of application  
This software is suitable for engineers and other professionals that need to perform repetitive calculations and present them in official documentation such as calculation notes. They can automate this task efficiently by creating powerful and reliable Calcpad worksheets. It can also help teachers to prepare calculation examples, papers, manuals, books etc. Students can use it to solve various problems, prepare homeworks, phd theses etc.  
  
## Installation  
The installation is performed by the automated setup program [calcpad-setup-en-x64.exe](https://github.com/Proektsoftbg/Calcpad/blob/main/Setup/calcpad-setup-en-x64.exe). Follow the instruction of the setup wizard. The software requires a 64 bit computer with Windows 10/11 and [Microsoft .NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0).  
You can also use Calcpad directly in the browser from our website: [https://calcpad.eu/Ide](https://calcpad.eu/Ide)  
  
## Licensing and terms of use  
This software is free for both commercial and non-commercial use. It is distributed under the MIT license:  
  
Copyright © 2024 PROEKTSOFT EOOD®  
  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  
  
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  
  
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.  
  
Any scripts, developed with Calcpad are property of the respective authors. They can be used without additional limitations except those appointed by the authors themselves.  

### Acknowledgments  
This project uses some additional third party components, software and design. They are re-distributed free of charge, under the license conditions, provided by the respective authors.  
1. The new and beautiful icons are created using [icons8.com](https://icons8.com/).  
2. The pdf export was made possible thanks to the [wkhtmltopdf.org](https://wkhtmltopdf.org/) project.  
3. Some symbols are displayed, using the Jost* font family by [indestructible type*](https://indestructibletype.com/), under the [SIL open font license](https://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web).
Square brackets are slightly modified to suit the application needs.  
  
## How it works  
The software is quick and easy to use. Just follow these simple steps:  
  
1. **Enter** text and formulas into the "**Code**" box on the left.  
2. Press **F5** or click <img alt="Play" height="24" src="https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/Play.png"> to calculate. Results will appear in the "**Output**" box on the right as a professionally formatted Html **report**.  
3. Click <img alt="PrintPreview" height="24" src="https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/PrintPreview.png"> to **print** or <img alt="Copy" height="24" src="https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/Copy.png"> to **copy** the output.  
You can also **export** it to **Html** <img alt="Html" height="24" src="https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/Save.png">, **PDF** <img alt="PDF" height="24" src="https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/Pdf.png"> or **MS Word** <img alt="Word" height="24" src="https://github.com/Proektsoftbg/Calcpad/blob/main/Help/Images/Word.png"> document.  
  
## The language  
  
Calcpad uses a simple programming language that includes the following elements:  
* Real numbers: digits 0 - 9 and decimal point ".";  
* Complex numbers: re ± imi (e.g. 3 - 2i);  
* Variables:  
&emsp;&emsp;- Latin letters: a - z, A - Z;  
&emsp;&emsp;- Greek letters: α - ω, Α - Ω;  
&emsp;&emsp;- digits: 0 - 9;  
&emsp;&emsp;- comma: " , ";  
&emsp;&emsp;- prime symbols: ′ , ″ , ‴ , ⁗ ;  
&emsp;&emsp;- superscripts: ⁰ , ¹ , ² , ³ , ⁴ , ⁵ , ⁶ , ⁷ , ⁸ , ⁹ , ⁿ , ⁺ , ⁻ ;  
&emsp;&emsp;- special symbols: ‾ , ø , Ø , ° , ∡ ;  
&emsp;&emsp;- " _ " for subscript;  
A variable name must start with a letter. Names are case sensitive.  
* Operators:  
&emsp;&emsp;"**!**" - factorial;  
&emsp;&emsp;"**^**" - exponent;  
&emsp;&emsp;"**/**" - division;  
&emsp;&emsp;"**÷**" - force division bar;  
&emsp;&emsp;"**\\**" - integer division;  
&emsp;&emsp;"**⦼**" - modulo (reminder);  
&emsp;&emsp;"**\***" - multiplication;  
&emsp;&emsp;"**-**" - minus;  
&emsp;&emsp;"**+**" - plus;  
&emsp;&emsp;"**≡**" - equal to;  
&emsp;&emsp;"**≠**" - not equal to;  
&emsp;&emsp;"**<**" - less than;  
&emsp;&emsp;"**>**" - greater than;  
&emsp;&emsp;"**≤**" - less or equal;  
&emsp;&emsp;"**≥**" - greater or equal;  
&emsp;&emsp;"**∧**" - logical "AND";   
&emsp;&emsp;"**∨**" - logical "OR";   
&emsp;&emsp;"**⊕**" - logical "XOR";   
&emsp;&emsp;"**=**" - assignment;  
* Custom functions of type f (x; y; z; ... );  
* Built-in functions:  
&emsp;&emsp;Trigonometric:  
&emsp;&emsp;&emsp;&emsp;**sin**(x)  - sine;  
&emsp;&emsp;&emsp;&emsp;**cos**(x)  - cosine;  
&emsp;&emsp;&emsp;&emsp;**tan**(x)  - tangent;  
&emsp;&emsp;&emsp;&emsp;**csc**(x)  - cosecant;  
&emsp;&emsp;&emsp;&emsp;**sec**(x)  - secant;  
&emsp;&emsp;&emsp;&emsp;**cot**(x)  - cotangent;  
&emsp;&emsp;Hyperbolic:  
&emsp;&emsp;&emsp;&emsp;**sinh**(x) - hyperbolic sine;  
&emsp;&emsp;&emsp;&emsp;**cosh**(x) - hyperbolic cosine;  
&emsp;&emsp;&emsp;&emsp;**tanh**(x) - hyperbolic tangent;  
&emsp;&emsp;&emsp;&emsp;**csch**(x) - hyperbolic cosecant;  
&emsp;&emsp;&emsp;&emsp;**sech**(x) - hyperbolic secant;  
&emsp;&emsp;&emsp;&emsp;**coth**(x) - hyperbolic cotangent;  
&emsp;&emsp;Inverse trigonometric:  
&emsp;&emsp;&emsp;&emsp;**asin**(x) - inverse sine;  
&emsp;&emsp;&emsp;&emsp;**acos**(x) - inverse cosine;  
&emsp;&emsp;&emsp;&emsp;**atan**(x) - inverse tangent;  
&emsp;&emsp;&emsp;&emsp;**atan2**(x; y) - the angle whose tangent is the quotient of y and x;  
&emsp;&emsp;&emsp;&emsp;**acsc**(x) - inverse cosecant;  
&emsp;&emsp;&emsp;&emsp;**asec**(x) - inverse secant;  
&emsp;&emsp;&emsp;&emsp;**acot**(x) - inverse cotangent;  
&emsp;&emsp;Inverse hyperbolic:  
&emsp;&emsp;&emsp;&emsp;**asinh**(x) - inverse hyperbolic sine;  
&emsp;&emsp;&emsp;&emsp;**acosh**(x) - inverse hyperbolic cosine;  
&emsp;&emsp;&emsp;&emsp;**atanh**(x) - inverse hyperbolic tangent;  
&emsp;&emsp;&emsp;&emsp;**acsch**(x) - inverse hyperbolic cosecant;  
&emsp;&emsp;&emsp;&emsp;**asech**(x) - inverse hyperbolic secant;  
&emsp;&emsp;&emsp;&emsp;**acoth**(x) - inverse hyperbolic cotangent;  
&emsp;&emsp;Logarithmic, exponential and roots:  
&emsp;&emsp;&emsp;&emsp;**log**(x)   - decimal logarithm;  
&emsp;&emsp;&emsp;&emsp;**ln**(x)    - natural logarithm;  
&emsp;&emsp;&emsp;&emsp;**log_2**(x) - binary logarithm;  
&emsp;&emsp;&emsp;&emsp;**exp**(x)   - natural exponent;  
&emsp;&emsp;&emsp;&emsp;**sqr**(x) / sqrt(x) - square root;  
&emsp;&emsp;&emsp;&emsp;**cbrt**(x) - cubic root;  
&emsp;&emsp;&emsp;&emsp;**root**(x; n) - n-th root;  
&emsp;&emsp;Rounding:  
&emsp;&emsp;&emsp;&emsp;**round**(x) - round to the nearest integer;  
&emsp;&emsp;&emsp;&emsp;**floor**(x) - round to the smaller integer (towards -∞);  
&emsp;&emsp;&emsp;&emsp;**ceiling**(x) - round to the greater integer (towards +∞);  
&emsp;&emsp;&emsp;&emsp;**trunc**(x) - round to the smaller integer (towards zero);  
&emsp;&emsp;Integer:  
&emsp;&emsp;&emsp;&emsp;**mod**(x; y) - the reminder of an integer division;  
&emsp;&emsp;&emsp;&emsp;**gcd**(x; y) - the greatest common divisor of two integers;  
&emsp;&emsp;&emsp;&emsp;**lcm**(x; y) - the least common multiple of two integers;  
&emsp;&emsp;Complex:  
&emsp;&emsp;&emsp;&emsp;**abs**(x)  - absolute value/magnitude;  
&emsp;&emsp;&emsp;&emsp;**re**(x)    - the real part of a complex number;  
&emsp;&emsp;&emsp;&emsp;**im**(x)    - the imaginary part of a complex number;  
&emsp;&emsp;&emsp;&emsp;**phase**(x) - the phase of a complex number;  
&emsp;&emsp;Aggregate and interpolation:  
&emsp;&emsp;&emsp;&emsp;**min**(x; y; z...) - minimum of multiple values;  
&emsp;&emsp;&emsp;&emsp;**max**(x; y; z...) - maximum of multiple values;  
&emsp;&emsp;&emsp;&emsp;**sum**(x; y; z...) - sum of multiple values = x + y + z...;  
&emsp;&emsp;&emsp;&emsp;**sumsq**(x; y; z...) - sum of squares = x² + y² + z²...;  
&emsp;&emsp;&emsp;&emsp;**srss**(x; y; z...) - square root of sum of squares = sqrt(x² + y² + z²...);  
&emsp;&emsp;&emsp;&emsp;**average**(x; y; z...) - average of multiple values = (x + y + z...)/n;  
&emsp;&emsp;&emsp;&emsp;**product**(x; y; z...) - product of multiple values = x·y·z...;  
&emsp;&emsp;&emsp;&emsp;**mean**(x; y; z...) - geometric mean = n-th root(x·y·z...);  
&emsp;&emsp;&emsp;&emsp;**take**(n; a; b; c...) - returns the n-th element from the list;  
&emsp;&emsp;&emsp;&emsp;**line**(x; a; b; c...) - linear interpolation;  
&emsp;&emsp;&emsp;&emsp;**spline**(x; a; b; c...) - Hermite spline interpolation;  
&emsp;&emsp;Conditional and logical:  
&emsp;&emsp;&emsp;&emsp;**if**(*cond*; *value-if-true*; *value-if-false*) - conditional evaluation;  
&emsp;&emsp;&emsp;&emsp;**switch**(*cond1*; *value1*; *cond2*; *value2*; … ; *default*) - selective evaluation;  
&emsp;&emsp;&emsp;&emsp;**not**(x) - logical "NOT";  
&emsp;&emsp;&emsp;&emsp;**and**(x; y; z...) - logical "AND";  
&emsp;&emsp;&emsp;&emsp;**or**(x; y; z...) - logical "OR";  
&emsp;&emsp;&emsp;&emsp;**xor**(x; y; z...) - logical "XOR";  
&emsp;&emsp;Other:  
&emsp;&emsp;&emsp;&emsp;**sign**(x) - the sign of a number;  
&emsp;&emsp;&emsp;&emsp;**random**(x) - random number between 0 and x;  
* Comments: "Title" or 'text' in double or single quotes, respectively. HTML, CSS, JS and SVG are allowed.  
* Graphing and plotting:  
&emsp;&emsp;$Plot { f(x) @ x = a : b } - simple plot;  
&emsp;&emsp;$Plot { x(t) | y(t) @ t = a : b } - parametric;  
&emsp;&emsp;$Plot { f1(x) & f2(x) & ... @ x = a : b } - multiple;  
&emsp;&emsp;$Plot { x1(t) | y1(t) & x2(t) | y2(t) & ... @ x = a : b } - multiple parametric;  
&emsp;&emsp;$Map { f(x; y) @ x = a : b & y = c : d }  - 2D color map of a 3D surface;  
&emsp;&emsp;PlotHeight - height of plot area in pixels;  
&emsp;&emsp;PlotWidth - width of plot area in pixels;  
* Iterative and numerical methods:  
&emsp;&emsp;$Root { f(x) = const @ x = a : b } - root finding for f(x) = const;  
&emsp;&emsp;$Root { f(x) @ x = a : b } - root finding for f(x) = 0;  
&emsp;&emsp;$Find { f(x) @ x = a : b } - similar to above, but x is not required to be a precise solution;  
&emsp;&emsp;$Sup { f(x) @ x = a : b } - local maximum of a function;  
&emsp;&emsp;$Inf { f(x) @ x = a : b } - local minimum of a function;  
&emsp;&emsp;$Area { f(x) @ x = a : b } - adaptive Gauss-Lobatto numerical integration;  
&emsp;&emsp;$Integral { f(x) @ x = a : b } - Tanh-Sinh numerical integration;  
&emsp;&emsp;$Slope { f(x) @ x = a } - numerical differentiation;  
&emsp;&emsp;$Sum { f(k) @ k = a : b } - iterative sum;  
&emsp;&emsp;$Product { f(k) @ k = a : b } - iterative product;  
&emsp;&emsp;$Repeat { f(k) @ k = a : b } - general inline iterative procedure;  
&emsp;&emsp;Precision - relative precision for numerical methods \[10<sup>-2</sup>; 10<sup>-16</sup>\] (default is 10<sup>-12</sup>)   
* Program flow control:  
&emsp;&emsp;Simple:  
&emsp;&emsp;&emsp;&emsp;#if *condition*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Your code goes here*  
&emsp;&emsp;&emsp;&emsp;#end if  
&emsp;&emsp;Alternative:  
&emsp;&emsp;&emsp;&emsp;#if *condition*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Your code goes here*  
&emsp;&emsp;&emsp;&emsp;#else  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Some other code*  
&emsp;&emsp;&emsp;&emsp;#end if  
&emsp;&emsp;Complete:  
&emsp;&emsp;&emsp;&emsp;#if *condition1*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Your code goes here*  
&emsp;&emsp;&emsp;&emsp;#else if *condition2*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Your code goes here*  
&emsp;&emsp;&emsp;&emsp;#else  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Some other code*  
&emsp;&emsp;&emsp;&emsp;#end if  
You can add or omit as many "#else if's" as needed. Only one "#else" is allowed. You can omit this too.  
* Iteration blocks:  
&emsp;&emsp;Simple:  
&emsp;&emsp;&emsp;&emsp;#repeat *number of repetitions*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Your code goes here*  
&emsp;&emsp;&emsp;&emsp;#loop  
&emsp;&emsp;With conditional break/coutinue:  
&emsp;&emsp;&emsp;&emsp;#repeat *number of repetitions*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Your code goes here*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;#if *condition*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;#break or #continue  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;#end if  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*Some more code*  
&emsp;&emsp;&emsp;&emsp;#loop  
* Modules and macros/string variables:  
&emsp;&emsp;Modules:  
&emsp;&emsp;&emsp;&emsp;#include *filename* - include external file (module);  
&emsp;&emsp;&emsp;&emsp;#local - start local section (not to be included);  
&emsp;&emsp;&emsp;&emsp;#global - start global section (to be included);  
&emsp;&emsp;Inline string variable:  
&emsp;&emsp;&emsp;&emsp;#def *variable_name$* = *content*  
&emsp;&emsp;Multiline string variable:  
&emsp;&emsp;&emsp;&emsp;#def *variable_name$*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*content line 1*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*content line 2*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;...  
&emsp;&emsp;&emsp;&emsp;#end def  
&emsp;&emsp;Inline string macro:  
&emsp;&emsp;&emsp;&emsp;#def *macro_name$*(*param1$*; *param2$*;...) = *content*  
&emsp;&emsp;Multiline string macro:  
&emsp;&emsp;&emsp;&emsp;#def *macro_name$*(*param1$*; *param2$*;...)  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*content line 1*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;*content line 2*  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;...  
&emsp;&emsp;&emsp;&emsp;#end def  
* Output control:  
&emsp;&emsp;#hide - hide the report contents;  
&emsp;&emsp;#show - always show the contents (default);  
&emsp;&emsp;#pre  - show the next contents only before calculations;  
&emsp;&emsp;#post - show the next contents only after calculations;  
&emsp;&emsp;#val  - show only the final result, without the equation;  
&emsp;&emsp;#equ  - show complete equations and results (default);  
&emsp;&emsp;#noc  - show only equations without results (no calculations);  
&emsp;&emsp;#nosub  - do not substitute variables (no substitution);  
&emsp;&emsp;#novar  - show equations only with substituted values (no variables);  
&emsp;&emsp;#varsub - show equations with variables and substituted values (default);  
&emsp;&emsp;#split - split equations that do not fit on a single line;  
&emsp;&emsp;#wrap - wrap equations that do not fit on a single line (default);  
&emsp;&emsp;#round n - rounds to n digits after the decimal point.  
&emsp;&emsp;Each of the above commands is effective after the current line until the end of the report or another command that overwrites it.
* Breakpoints for step-by-step execution:  
&emsp;&emsp;#pause - calculates to the current line and waits until resumed manually;  
&emsp;&emsp;#input - renders an input form to the current line and waits for user input.  
* Switches for trigonometric units: #deg - degrees, #rad - radians, #gra - gradians;  
* Separator for target units: |, for example:  `3ft + 12in|cm` will show 121.92 cm;  
* Dimensionless: %, ‰;
* Angle units: °, ′, ″, deg, rad, grad, rev;  
* Metric units (SI and compatible):  
&emsp;&emsp;Mass: g, hg, kg, t, kt, Mt, Gt, dg, cg, mg, μg, Da, u;  
&emsp;&emsp;Length: m, km, dm, cm, mm, μm, nm, pm, AU, ly;  
&emsp;&emsp;Time: s, ms, μs, ns, ps, min, h, d, w, y;  
&emsp;&emsp;Frequency: Hz, kHz, MHz, GHz, THz, mHz, μHz, nHz, pHz, rpm;  
&emsp;&emsp;Speed: kmh;  
&emsp;&emsp;Electric current: A, kA, MA, GA, TA, mA, μA, nA, pA;  
&emsp;&emsp;Temperature: °C, Δ°C, K;  
&emsp;&emsp;Amount of substance: mol;  
&emsp;&emsp;Luminous intensity: cd;  
&emsp;&emsp;Area: a, daa, ha;  
&emsp;&emsp;Volume: L, daL, hL, dL, cL, mL, μL, nL, pL;  
&emsp;&emsp;Force: dyn N, daN, hN, kN, MN, GN, TN, gf, kgf, tf;  
&emsp;&emsp;Moment: Nm, kNm;  
&emsp;&emsp;Pressure: Pa, daPa, hPa, kPa, MPa, GPa, TPa, dPa, cPa, mPa, μPa, nPa, pPa,  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; bar, mbar, μbar, atm, at, Torr, mmHg;  
&emsp;&emsp;Viscosity: P, cP, St, cSt;  
&emsp;&emsp;Energy work: J, kJ, MJ, GJ, TJ, mJ, μJ, nJ, pJ,  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Wh, kWh, MWh, GWh, TWh, mWh, μWh, nWh, pWh  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;eV, keV, MeV, GeV, TeV, PeV, EeV, cal, kcal, erg;  
&emsp;&emsp;Power: W, kW, MW, GW, TW, mW, μW, nW, pW, hpM, ks;  
&emsp;&emsp;&emsp;&emsp;&emsp; VA, kVA, MVA, GVA, TVA, mVA, μVA, nVA, pVA,  
&emsp;&emsp;&emsp;&emsp;&emsp; VAR, kVAR, MVAR, GVAR, TVAR, mVAR, μVAR, nVAR, pVAR, hpM, ks;  
&emsp;&emsp;Electric charge: C, kC, MC, GC, TC, mC, μC, nC, pC, Ah, mAh;  
&emsp;&emsp;Potential: V, kV, MV, GV, TV, mV, μV, nV, pV;  
&emsp;&emsp;Capacitance: F, kF, MF, GF, TF, mF, μF, nF, pF;  
&emsp;&emsp;Resistance: Ω, kΩ, MΩ, GΩ, TΩ, mΩ, μΩ, nΩ, pΩ;  
&emsp;&emsp;Conductance: S, kS, MS, GS, TS, mS, μS, nS, pS, ℧, k℧, M℧, G℧, T℧, m℧, μ℧, n℧, p℧;  
&emsp;&emsp;Magnetic flux: Wb , kWb, MWb, GWb, TWb, mWb, μWb, nWb, pWb;  
&emsp;&emsp;Magnetic flux density: T, kT, MT, GT, TT, mT, μT, nT, pT;  
&emsp;&emsp;Inductance: H, kH, MH, GH, TH, mH, μH, nH, pH;  
&emsp;&emsp;Luminous flux: lm;  
&emsp;&emsp;Illuminance: lx;  
&emsp;&emsp;Radioactivity: Bq, kBq, MBq, GBq, TBq, mBq, μBq, nBq, pBq, Ci, Rd;  
&emsp;&emsp;Absorbed dose: Gy, kGy, MGy, GGy, TGy, mGy, μGy, nGy, pGy;  
&emsp;&emsp;Equivalent dose: Sv, kSv, MSv, GSv, TSv, mSv, μSv, nSv, pSv;  
&emsp;&emsp;Catalytic activity: kat;  
* Non-metric units (Imperial/US):  
&emsp;&emsp;Mass: gr, dr, oz, lb (or lbm, lb_m), klb, kipm (or kip_m), st, qr,  
&emsp;&emsp;&emsp;&emsp;&ensp; cwt (or cwt_UK, cwt_US), ton (or ton_UK, ton_US), slug;  
&emsp;&emsp;Length: th, in, ft, yd, ch, fur, mi, ftm (or ftm_UK, ftm_US),  
&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; cable (or cable_UK, cable_US), nmi, li, rod, pole, perch, lea;  
&emsp;&emsp;Speed: mph, knot;  
&emsp;&emsp;Temperature: °F, Δ°F, °R;  
&emsp;&emsp;Area: rood, ac;  
&emsp;&emsp;Volume, fluid: fl_oz, gi, pt, qt, gal, bbl, or:  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;fl_oz_UK, gi_UK, pt_UK, qt_UK, gal_UK, bbl_UK,  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;fl_oz_US, gi_US, pt_US, qt_US, gal_US, bbl_US,  
&emsp;&emsp;Volume, dry: (US) pt_dry, (US) qt_dry, (US) gal_dry, (US) bbl_dry,  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;pk (or pk_UK, pk_US), bu (or bu_UK, bu_US);  
&emsp;&emsp;Force: ozf (or oz_f), lbf (or lb_f), kip (or kipf, kip_f), tonf (or ton_f), pdl;  
&emsp;&emsp;Pressure: osi, osf psi, psf, ksi, ksf, tsi, tsf, inHg;  
&emsp;&emsp;Energy/work: BTU, therm, (or therm_UK, therm_US), quad;  
&emsp;&emsp;Power: hp, hpE, hpS;  
* Custom units - .Name = expression.  
Names can include currency symbols: €, £, ₤, ¥, ¢, ₽, ₹, ₩, ₪.
