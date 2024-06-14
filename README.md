# incomplete-2
mehods
class numbers:
    def __init__(self, numlist):
        self.numlist = numlist
    def __getitem__(self, index):
        return self.numlist[index]
numlist = numbers([1,2,3,4,5,6,7,8,9])
print(numlist[5])
end
class numbers:
    def __init__(self,mylist):
        self.mylist = mylist
    def __getitem__(self, index):
        return self.mylist[index]    
mylist = [1,2,3,4,5,6,7,8,9]
mylist[5] = 1000
print(mylist)
print(mylist[5])
end
class circle:
    pi = 3.14159
    def __init__(self,radius):
        self.radius = radius
    def area(self):
        return circle.pi*self.radius*self.radius
    def circumference(self):
        return 2*circle.pi*self.radius
c = circle(15)
print("area of circle",c.area())
print("cicumference of circle",c.circumference())
end
