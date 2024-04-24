Задача 1
x = int(input())
y = int(input())
print(x * y)
print(x + y)

Задача 2
x = int(input())
y = int(input())
a = x + y
b = x - y
c = x * y
d = x / y
e = x // y
if a > b and a > c and a > d and a > e:
    print(f"наибольшее число a")
elif b > a and b > c and b > d and b > e:
    print(f"наибольшее число b")
elif c > a and c > b and c > d and c > e:
    print(f"наибольшее число c")
elif d > a and d > b and d > c and d > e:
    print(f"наибольшее число d")
else:
    print(f"наибольшее число e")


Задача 3
x = int(input())
y = int(input())
a = x + y
b = x - y
c = x * y
d = x / y
e = x // y
if a > b and a > c and a > d and a < e or a > b and a > c and a < d and a > e or a > b and a < c and a > d and a > e or a < b and a > c and a > d and a > e:
    print(f"второе наибольшее число a")
elif b > a and b > c and b > d and b < e or b > a and b > c and b < d and b > e or b > a and b < c and b > d and b > e or b < a and b > c and b > d and b > e:
    print(f"второе наибольшее число b")
elif c > a and c > b and c > d and c < e or c > a and c > b and c < d and c > e or c > a and c < b and c > d and c > e or c < a and c > b and c > d and c > e:
    print(f"второе наибольшее число c")
elif d > a and d > b and d > c and d < e or d > a and d > b and d < c and d > e or d > a and d < b and d > c and d > e or d < a and d > b and d > c and d > e:
    print(f"второе наибольшее число d")
else:
    print(f"второе наибольшее число e")
