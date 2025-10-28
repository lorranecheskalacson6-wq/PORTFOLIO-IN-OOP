Midterm Lab Task 2:

<img width="669" height="701" alt="image" src="https://github.com/user-attachments/assets/1761e7e1-4f3a-4e46-bf9c-e111ffd1a952" />

Source Code:

    def calculate_average_rating (quality_rating, price_rating, service_rating):
      return (quality_rating + price_rating + service_rating)/3
    
    def analyze_product_rating (prod_name, category, quality_rating, price_rating, service_rating):
       avg_rating = calculate_average_rating (quality_rating, price_rating, service_rating)
       print(f"Product Name: {prod_name} \nCategory: {category} \nQuality Rating: {quality_rating:0.2f} \nPrice Rating: {price_rating:0.2f} \nService Rating
    {service_rating:0.2f} \nOverall Average Rating: {avg_rating:0.2f}")
    
    prod_name = input("Enter Product Name: ")
    category = input("Enter Category: ")
    quality_rating = float(input("Enter Quality Rating: "))
    price_rating = float(input("Enter Price Rating: "))
    service_rating = float(input("Enter Service Rating: "))
    
    analyze_product_rating (prod_name, category, quality_rating, price_rating, service_rating)




Output:

Sample Output 1:

<img width="494" height="345" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/cb9ca0d4-19b6-4c66-b3ea-aa67170c7fcd" />

Sample Output 2:

<img width="629" height="436" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/77ba9ff3-e72c-4f2b-a045-bd09bb0fd1d6" />
