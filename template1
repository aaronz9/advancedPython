# -*- coding: utf-8 -*-
"""
Spyder Editor

This is a temporary script file.
"""


from string import Template




def main():
    cart = [] #empty list
    cart.append(dict(item = "Coke", price = 8, qty = 2))
    cart.append (dict(item = "Cake", price = 12, qty = 1))
    cart.append (dict(item = "Fish", price = 32, qty = 4))
 

   
    
    
    t = Template("$qty x $item = $price")           #template object t
    total = 0
    print("Cart: ")
    
    
    
    for data in cart:
        print (t.substitute(data))
        
        total += data["price"]
        
    print("Total "+str(total))
    
    
if __name__ == '__main__':
    main()
        
        
        
    #so what we have done here is that 
    
