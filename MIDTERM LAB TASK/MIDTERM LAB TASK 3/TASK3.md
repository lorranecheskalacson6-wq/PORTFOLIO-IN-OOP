
Midterm Lab Task 3:

Modify the menuCart program and include the following requirements:

Problem 1: Validate user choice (If choice is not in the cart) - "display item is not in the cart"

Problem 2: Input Customer Name and Age if age is 60 and above provide 20% discount from the total purchased.

Source Code:

    menu = {"Burger": 35.00,
       "Tacos": 50.00,
       "Fries": 20.00,
       "Ice Coffee": 25.00}
       
    cart = []
    total = 0
    print("-------- M E N U --------")
    for key, value in menu.items():
         print(f"{key:15}:P{value:.2f}")
    print("-------------------------")
    
    customer_name = input("Enter Your Name: ")
    customer_age = int(input("Enter Your Age: "))
    
    while True:
      food = input("Select an item from the menu (q to quit): ")
      if food.lower() == 'q':
        break
      elif food not in menu:
        print("Item is not in the cart")
      elif menu.get(food) not in menu:
        cart.append(food)
       
    print("Your orders are.....")
    for food in cart:
      total = total + menu.get(food)
      print(food, end=" ")
    print()
    
    if 60 <= customer_age:
      discount = total * 0.20
      total -= discount
      print(f"\n20% discount!!: P{discount:.2f}")
      
      print(f"Customer Name: {customer_name}")
      print(f"Total Purchase: P{total:.2f}")

Output:

<img width="589" height="567" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/6a6e30bb-a07a-4f9f-9ee3-6af65b12328b" />
