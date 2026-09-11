# abcdparameters.p
abcd parameters calculation in python 
print("ABCD Parameter Calculation")

# I2 = 0
print("\nEnter V1, V2 and I1 when I2 = 0:")
V1_1 = float(input("V1 = "))
V2_1 = float(input("V2 = "))
I1_1 = float(input("I1 = "))

# V2 = 0
print("\nEnter V1 and I1, I2 when V2 = 0:")
V1_2 = float(input("V1 = "))
I1_2 = float(input("I1 = "))
I2_2 = float(input("I2 = "))

# Calculate ABCD parameters
A = V1_1 / V2_1
B = V1_2 / (-I2_2)
C = I1_1 / V2_1
D = I1_2 / (-I2_2)

print("\nABCD Parameters:")
print(f"A = {A:.2f}")
print(f"B = {B:.2f} Ohms")
print(f"C = {C:.2f} Siemens")
print(f"D = {D:.2f}")