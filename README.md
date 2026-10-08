# short-circuit-and-open-circuit.py
short circuit and open circuit 

# Short Circuit Calculation

V = float(input("Enter voltage (V): "))

R = 0.01   # Very small resistance for short circuit

I = V / R

print("Short Circuit Current =", I, "A")
# Open Circuit Calculation

V = float(input("Enter voltage (V): "))

I = 0

print("Open Circuit Voltage =", V, "V")
print("Open Circuit Current =", I, "A")