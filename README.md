# Author: Gabriel Giron plata
# GitHub username: gironplg
# Date: 04/08/2026
# Description: Asks the user for a temperature in celcius,
#              output the equivalent temperature in fahrenheit

celsius = float(input("Please enter a temperature in Celsius.\n"))

#convent Celsius to Fahrenheit using the formula F = (9/5)C + 32
fahrenheit = (9/5) * celsius + 32

print("Please enter a Celsius temperature.")
print("The equivalent Fahrenheit temperature is.")
print(f"{fahrenheit:.7f}"
