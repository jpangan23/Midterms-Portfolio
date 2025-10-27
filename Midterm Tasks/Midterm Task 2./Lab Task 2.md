MIDTERM LAB TASK 2

<img width="769" height="808" alt="image" src="https://github.com/user-attachments/assets/89d989ca-0ecd-4d78-91a6-64db77d4d30d" />

SOURCE CODE:

    product_name = str(input("Enter Product Name:"))
    category = str(input("Enter Category:"))
    quality = float(input("Enter Quality Rating:"))
    price = float(input("Enter Price Rating:"))
    service = float(input("Enter Service Rating:"))
    
    def calculate_average_rating(quality,price,service):
    total = quality + price + service
    avg = total / 3
    return avg
    
    def analyze_product():
    print("Product Name: %s " %product_name )
    print("Category: %s" % category )
    print("Quality Rating: %.2f" % quality)
    print("Price Rating: %.2f "% price)
    print("Service Rating: %.2f" % service)
    print("Overall Average Rating: %.2f" % calculate_average_rating(quality,
    price, service))
    analyze_product()


Sample Output 1:
<img width="436" height="257" alt="image" src="https://github.com/user-attachments/assets/84244e71-3040-444f-8ba0-51d8fa4df58a" />

Sample Output 2:

<img width="352" height="247" alt="image" src="https://github.com/user-attachments/assets/75a245e1-bd8d-4252-9642-48733415b41b" />
