+ # labspy02
+ # Program cari bilangan terbesar

+ x= int(input("Masukkan bilangan ke-1: ")) 
+ y= int(input("Masukkan bilangan ke-2: "))
+ z= int(input("Masukkan bilangan ke-3: "))

+ if (x>y) and (x>z):
+ 	print("Bilangan terbesar diantara " ,x, ",",y ,", dan",z, "adalah " ,x,)
+ elif (y>x) and (y>z) :
+     print("Bilangan terbesar diantara " ,x ,",",y ,", dan",z ,"adalah " ,y,)
+ elif (z>x) and (z>y) :
+ 	print("Bilangan terbesar diantara " ,x ,",",y ,", dan" ,z,"adalah " ,z,)
