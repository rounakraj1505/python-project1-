# python-project1-
stone ,paper,scissors gameplay
while True:
  products = ["pen", "notebook", "eraser", "pencil"]
  prices = [10, 50, 5, 7]
  stocks = [100, 50, 200, 150]
  product=input("What product you want?")
  if product in products:
    index=products.index(product)
    price=prices[index]
    stock=stocks[index]
    Total_cost=price*stocks
    print("Enter product is:",product.capitalize())
    print(f"product cost{price}is")
    print(f"product quantity:{stock}")
    break
  else:
    print("The entered product is not in stationary")

print(f"Total cost for required item={Total_cost}")
    
