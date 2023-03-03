x = int(input("Add first number: "))
y = int(input("Add second number: "))
if x > 0:
  if y > 0:  # x > 0, y > 0
    print("1st Quater")
  else:  # x > 0, y < 0
    print("4th Quater")
else:  # x < 0
  if y > 0:  # x < 0, y > 0
    print("2nd Quater")
  else:  # x < 0, y < 0
    print("3rd Quater")
'''         Y
            ^
            |3
     II     |2     I
            |1 
(-3)(-2)(-1)---1-2-3-----> X
            |-1 
     III    |-2    IV
            |-3
'''
