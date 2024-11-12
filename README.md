# Python-project-1

# calculator.py program

#h ere i am printing the title to create a visual effect
print('====================')
print('Area Calculator')
print('====================')

# assigning a value to each shape 
Triangle = 1
Rectangle = 2
Square = 3
Circle = 4
Quit = 5

# printing the users options before intake 
print("1) Triangle\n2) Rectangle\n3) Square\n4) Circle\n5) Quit")

#using an input function to request the user choose a shape 
shape = int(input("\nWhich shape: "))
print(f'\nWhich shape: {shape}')

# here i use conditional statements to calculae the are of the shape based on the value the user chooses - if none chosen, the program will quit
if shape == 1:
  height = int(input("Height: "))
  print(f"\nHeight: {height}")
  base = int(input("Base: "))
  print(f"Base: {base}")
  print(f'\nThe area is {height * base/2}')
if shape == 2:
  length = int(input("Length: "))
  print(f"\nLength: {length}")
  width = int(input("Width: "))
  print(f"Width: {width}")
  print(f'\nThe area is {length * width}')
if shape == 3:
  side = int(input("Side: "))
  print(f'\nSide: {side}')
  print(f'\nThe area is {side ** 2}')
if shape == 4:
  radius = int(input("Radius: "))
  print(f'\nRadius: {radius}')
  print(f'\nThe area is {3.14 * radius ** 2}')
else:
  print("\nQuit")
