# kelly-s-temperature-detector.

# Kelly's Thermometer - Digital Health Project
print("Welcome to Kelly's Thermometer")

while True:
    t = input("\nEnter temperature (q to quit): ")
    if t == 'q':
        print("Thanks for using Kelly's Thermometer. Bye!")
        break
    
    t = float(t)
    if t >= 37.5:
        print("High temperature! Get well soon.")
    elif t >= 36.0:
        print("Normal temperature.")
    else:
        print("Low temperature. Please warm up.")