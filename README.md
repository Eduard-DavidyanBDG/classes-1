# classes-1
lesson-11 classes
class Car:
    Name = None
    Time = 1
    Speed = 100
    def speed(self):
        Speed = 100
        return Speed




class BMW(Car):
    Name = "BMW"
    Time = 5
    Speed = 100





class Mersedes(Car):
    Name = "Mercedes"
    Time = 3.7
    Speed = 100

B = BMW()
M = Mersedes()

print("which car you want " + str(B.Name) + " or " + str(M.Name) + "\n")
yntrutyun = str(input())
if yntrutyun == "Mercedes":
    print(str(M.Name) + "\t" + str(M.Speed) + "\t" + str(M.Time))
else:
    print(str(B.Name) + "\t" + str(B.Time) + "\t" + str(B.Speed))
