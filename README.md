def celsius_to_fahrenheit(celsius):
    fahrenheit = (celsius * 9/5) + 32
    return fahrenheit

celsius_temperatures = [22, 46, 51, 76]

for celsius in celsius_temperatures:
    fahrenheit = celsius_to_fahrenheit(celsius)
    print(f"{celsius}ºC is equal to {fahrenheit:.2f}ºF")
