# Create-GCD
def binary_gcd(a, b):     # Якщо одне з чисел 0, повертаємо інше число     if a == 0:         return b     if b == 0:         return a      # Знаходимо степінь двійки, на яку діляться обидва числа     shift = 0     while ((a | b) &amp; 1) == 0:  # обидва парні         a >>= 1         b >>= 1         shift += 1
