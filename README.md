# Corrected QT Interval (QTc) Calculator

This repository provides a Python code for calculating the Corrected QT Interval (QTc) in an actual condition. The Corrected QT Interval is an important measurement used in cardiology to assess the risk of arrhythmias and cardiac events.

## What is the Corrected QT Interval (QTc)?

The QT interval is a segment on an electrocardiogram (ECG) that represents the time it takes for the ventricles the heart to depolarize and repolarize. It is an essential parameter for evaluating the electrical activity of the heart.

However, the interval can vary depending on the heart rate, making it challenging to compare values across different individuals or conditions. To account for this variability, the Corrected QT Interval (QTc) calculated by adjusting the QT interval based on the RR interval, which represents the time between consecutive R-peaks on the ECG.

## Bazett's Formula

Bazett's formula is one of several formulas used to calculate the Corrected QT Interval (QTc). It is widely used and defined as:

```
QTc = QT_interval / (√(RR_interval / 1000))
```

where:
- `QT_interval` is the measured QT interval in milliseconds.
- `RR_interval` the measured RR interval in milliseconds.

Bazett's formula adjusts the QT interval by dividing it by the square root of the RR interval, converted seconds.

## Usage

To use the provided code, follow these steps:

1. Set the values for `qt_interval` and `rr_interval` variables in the code to the measured QT interval and RR interval, respectively, in milliseconds.

2. Run the code.

3. The calculated Corrected QT Interval (QTc) will be displayed in the console.

## Example

Here's an example usage of the code:

```python
qt_interval = 400  # milliseconds
rr_interval = 800  # milliseconds

qtc = calculate_qtc(qt_interval, rr_interval)
print("Corrected QT Interval (QTc):", qtc)
```

In this example, the measured QT interval is 400 milliseconds, and the RR interval is 800 milliseconds. The code calculates the Corrected QT Interval (QTc) using Bazett's formula and displays the result the console.

## Important Considerations

- Bazett's formula is just one of several formulas used to calculate QTc. Depending on your specific scenario, you may need use a different formula or consider other factors. is essential to consult with medical professionals for accurate assessment and diagnosis.

- Interting QTc values requires clinical expertise. Different thresholds and guidelines exist for determining abnormal QTc values based on factors such as age, gender, and underlying medical conditions. Always consult with healthcare professionals for proper interpretation and evaluation.

- This code provides a basic implementation of the QTc calculation. It is intended for educational purposes and should not replace professional medical advice or specialized software used in clinical settings.

## Contributing

Contributions to this repository are welcome. If you have suggestions, improvements, bug fixes, please feel free to open an issue or submit a pull request.


---

By following the steps outlined above, you can use the provided code to calculate the Corrected QT Interval (QTc) using Bazett's formula. Remember to consult with medical professionals for accurate interpretation and diagnosis. Contributions to this repository are encouraged, and the project is available under the MIT License.
