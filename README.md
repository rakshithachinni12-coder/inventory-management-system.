choice = input("Enter your choice: ")

if choice == "1":
    pid = input("Product ID: ")
    name = input("Product Name: ")
    qty = int(input("Quantity: "))
    price = float(input("Price: "))
    ims.add_product(pid, name, qty, price)

elif choice == "2":
    ims.view_inventory()

elif choice == "3":
    pid = input("Product ID: ")
    qty = int(input("Quantity to Add/Remove (+/-): "))
    ims.update_stock(pid, qty)

elif choice == "4":
    pid = input("Product ID: ")
    ims.remove_product(pid)

elif choice == "5":
    print("Exiting...")
    break

else:
    print("Invalid choice!")# inventory-management-system.
inventory management system
