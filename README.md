def Cylinder (r, h):
    return 3.14*r*r*h
result = Cylinder(2, 7)
print("the volume of a cylinder is:", result)
#--------------------------------------------------
def Miles(k):
    return k*0.621371
result = Miles(5)
print("kilometers to miles is:", result)
#--------------------------------------------------
def calculator(a):
    if a >= 90:
        print("A")
        
    elif a >= 80 and a >= 89:
       print("B")
    
    elif a >= 70 and a >= 79:
        print("C")
        
    elif a >= 60 and a >= 69:
       print("D")
       
    else:
        print("F")
       
    
calculator(99)
    
