class Animal :
	def __init__(self, name, age):
		self.name=name
		self.age=age
	def sleep(self):
		print self.name , "of" , self.age , "years old is sleeping"
	def eat(self):
		print self.name , "is" , self.age , "years old and eats chocolate twice a day" 
 
class Bird (Animal) : 
   	def __init__(self,wings_color, name, age):
		Animal.__init__(self , name ,age )
		self.wings_color= wings_color
	def fly(self): 
		print self.name , "of" , self.age , "years old , has" , self.wings_color , "wings "

class Dog (Animal) :
	def __init__(self, num_of_legs , name , age):
		Animal.__init__(self , name , age )
		self.num_of_legs = num_of_legs
	def bark(self):
		print self.name , "of" , self.age , "years old" , "has" , self.num_of_legs , "legs" , "and enjoys barking"




a = Bird("green", "Leen" , "6") 
a.sleep() 
a.eat()
a.fly()
b = Dog("4" , "sub7iyye" , "1")
b.sleep()
b.eat()
b.bark()
