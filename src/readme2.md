class Parent:
    def __init__(self,name):
        self.name1 = name

class Child(Parent):
    def name(self):
        self.name2 = "Alice"
            return self.name2
temp = Child("Bob")
print ("%s %s"%(temp.name1,temp.name()))