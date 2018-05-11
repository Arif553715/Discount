



class Dis:
    def lol(self,x):
        if x == 1:
            self.y =int (input("takar poriman:"))
            self.a = self.y / 100
            self.b = self.a * 4
            self.c = self.b + self.y
            print(self.a)
            print(self.b)
            print(self.c)
            return self.lol1(0)


    
    def lol1(self,a):
        if a == 0:
            self.g = self.c / 100
            self.e = self.g * int(input("discount:"))
            self.f = self.c - self.e
            print(self.g)
            print(self.e)
            print(self.f)



d = Dis()
d.lol(1)
