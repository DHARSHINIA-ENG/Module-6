# Exp.No:6a
## Abstraction

---

### AIM  
To write a Python program to import the abc module to create the abstract base class. Create the Car class that inherit the ABC class and define an abstract method named mileage(). then inherit the base class from the three different subclasses and implement the abstract method differently. Create the objects to call the abstract method.


### ALGORITHM

1. Start the Program.
2. Import ABC and abstractmethod from abc module.
3. Define abstract class Car with an abstract method mileage().
4. Create subclasses Tesla, Suzuki, Duster, and Renault inheriting from Car.
5. Implement the mileage() method in each subclass with a specific print statement.
6. Create instances of each subclass.
7. Call the mileage() method on each instance to display mileage.
8. End the Program.

---

### PROGRAM
```
from abc import ABC, abstractmethod   
class Car(ABC):   
    #Add your code here
    def mileage(self):
        pass
  
class Tesla(Car):   
    def mileage(self):   
        print("The mileage is 30kmph")   
class Suzuki(Car):   
    def mileage(self):   
        print("The mileage is 25kmph ")   
class Duster(Car):   
     def mileage(self):   
          print("The mileage is 24kmph ")   
  
class Renault(Car):   
    def mileage(self):   
        print("The mileage is 27kmph ")   
          
# Driver code   
#Add your code here
t=Tesla()
t.mileage()
r=Renault()
r.mileage()
s = Suzuki()   
s.mileage()   
d = Duster()   
d.mileage()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/44c106bb-e892-41c7-b9c7-e0bdf74d23c0)


### RESULT
Thus a Python program to define the abstract base class and the abstract method is implemented successfully.
