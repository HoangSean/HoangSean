a = float(input("a = "))
b = float(input("b = "))
c = float(input("c = "))
print(a, "x^2+", b, "x+",c)
delta = b*b - 4*a*c 
import math
if delta > 0 :
	print("Pt có nghiệm")
	x1 = (-b + (delta)**0.5)/2*a 
	x2 = (-b - (delta)**0.5)/2*a 
	print("Các nghiệm = ", x1, "và", x2)
elif delta == 0 :
	print("Nghiệm kép")
	x3 = -b/2*a
	print("Nghiệm kép = ", x3)
else:
	print("Vô nghiệm")

if a > 0 :
	x_min = -b/2*a 
	print("Hàm đồng biến trên (-vô cùng;", x_min, ") và nghịch biến trên (", x_min, ";+vô cùng)")
else:
	x_max = -b/2*a 
	print("Hàm nghịch biến trên (-vô cùng;", x_max, ") và đồng biến trên (", x_max, ";+vô cùng)")

