def celsius_to_fahrenheit(celsius):
    fahrenheit = (celsius * 9/5) + 32
    return fahrenheit
# Temperatures in Celsius to be converted
celsius_temperatures = [22, 46, 51, 76]

# Convert each temperature and print the result
for celsius in celsius_temperatures:
    fahrenheit = celsius_to_fahrenheit(celsius)
    print(f"{celsius}ºC is equal to {fahrenheit:.2f}ºF")
