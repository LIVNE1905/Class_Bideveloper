# Class_Bideveloper

class Bi_developer:
    # Constructor method to initialize the object
    def __init__(self, name, age, department):
        self.name = name   # Dog's name
        self.age = age  # Dog's age
        self.department = department # Dog's breed


    # Method to simulate barking
    def shout(self):
        return f"{self.name} shout hello!"

    # Method to simulate the dog eating
    def eat(self, piza):
        return f"{self.name} is eating {piza}."

    # Method to show the dog's details
    def describe(self):
        return f"{self.name} is a {self.age}-year-old {self.department}."


# Creating instances of the Dog class
Bi_developer1 = Bi_developer("Livne", 37, "moked")
Bi_developer2 = Bi_developer("Liad", 43, "byd")
# Using the methods
print(Bi_developer1.describe())

C:\Program Files\Python313\python.exe" C:\PPPLX\workspace\BI\Python_Scripts\class_etl.py 
Livne is a 37-year-old moked.

Process finished with exit code 0
