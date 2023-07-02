# Corrected-QT-Interval
Here's a complete Python code for calculating Corrected QT Interval (QTc) in an actual condition.
In this code, the calculate_qtc function takes two parameters: qt_interval and rr_interval. These parameters represent the QT interval and RR interval, respectively, measured in milliseconds.

The function calculates the Corrected QT Interval (QTc) using Bazett's formula: dividing the QT interval by the square root of the RR interval (in seconds). The RR interval is usually measured as the time between consecutive R-peaks on an electrocardiogram (ECG).

Finally, the code demonstrates an example usage by providing sample values for the variables and printing the calculated QTc.

Please note that Bazett's formula is just one of several formulas used to calculate QTc. Depending on your specific scenario, you may need to use a different formula or consider other factors. Also, keep in mind that interpreting QTc values requires clinical expertise, and it's important to consult with medical professionals for accurate assessment and diagnosis.
