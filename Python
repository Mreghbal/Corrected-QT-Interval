def calculate_qtc(qt_interval, rr_interval):
    # Bazett's formula
    qtc = qt_interval / ((rr_interval / 1000) ** 0.5)
    return qtc


# Example usage:
qt_interval = 400 # milliseconds
rr_interval = 800 # milliseconds

qtc = calculate_qtc(qt_interval, rr_interval)
print("Corrected QT Interval (QTc):", qtc)
