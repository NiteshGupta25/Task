# Task
class Vehicle:
    def __init__(self,Color, Price, Maximum_Speed):
       self.Color = Color
       self.Price = Price	
       self.Maximum_speed = Maximum_Speed
    def getinfo(self):
       print("color:{},Price:{},Maximum_Speed:{}".format(self.Color,self.Price,self.Maximum_speed))	   
class car:
    def __init__(self,Tires):
	   self.Tires = Tires
  	def carinfo(self):
	   print("Tires:",4)
	   self.Vehicle.getinfo()
v=Vehicle("Red","500000","220/km")  
c=car('Tires')
        c.carinfo() 
