#@classmethod is written before defining a function to ignore instance parameters and only show class attributes value, in a method defined by class method we use "cls" instead of selptf.
#class method
class ravi():
    salary= 12333
    @classmethod
    def change(cls):
        print(f"the class salary is {cls.salary}")
o1=ravi()
o1.salary=30000
#print(o1.salary)
o1.change() #call a specific method 
