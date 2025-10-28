Midterm Lab Task 1

Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc)
for the problem below

<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/36ef41b0-8eb0-48a6-b989-7ca336cb4fe0" />

Source Code:
     
      print("Database Record")
      print("\\\\\\\\\")
      print("Name:\t\tJohn Doe") print("Email:\t\tjohn.doe@example.com")
      print("University: \tABC University")

Output:

![20251026_145534](https://github.com/user-attachments/assets/a6cd39a6-1736-435a-858e-3163daebc483)



Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f
etc… for this task

<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/938b8d73-0adf-44ed-bf8b-e8bedf73e16d" />


Source Code:
   
    name = "John"
    sender = "Jane"
    version = 1.2
    discount = 10.5
    status = "A"
    code "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    print("""Dear %s, I hope this email finds you well.
    I wanted to reach out and say hello.
    I hope you are doing well and enjoying your day.
    It's been a while since we last spoke, and I wanted to catch up with you.
    Let's plan to meet up soon and have a great time together!
    Subject: Greetings
    Sender: %s
    Version: %.1f
    Discount: %.2f%%
    Status: %s
    Code: %5
    Location: %s
    Age: %d
    Company: %s
    Website: %s
    Phone: %s
    Job Title: %s
    Department: %s""" % (name, sender, version, discount, status, code, location, age,
    company, website, phone, job_title, department))

  
Output:

![20251026_145537](https://github.com/user-attachments/assets/2ae395c0-f853-493b-a9bf-a155b91f3be3)



Problem 3. Book Reservation; Accept User Input

<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/03c18810-af02-4d1d-aa3b-b0d9169f9948" />

Source Code:
   
    title = input("Enter the book title: ")
    author = input("Enter the author: ")
    year = int(input("Enter the year of publication : "))
    genre = input("Enter the genre: ")
    library = input("Enter the library: ")
    member_id = input("Enter your member ID: ")
    "return_date = input("Enter the return date: ")
    print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    print(f"Year of Publication: {year}"
    print(f"Genre: {genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")
Output:

![20251026_145545](https://github.com/user-attachments/assets/880fa4b7-8d12-4446-8da7-7a30d018a154)

![20251026_145546](https://github.com/user-attachments/assets/fee34a27-b94b-4372-a0f8-f6cb10caec0f)



Problem 4. Day Identifier

<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/10e36142-6c97-4fbc-8e53-4670d4b073b9" />


Source Code:
   
    day = int(input("Enter day: "))
    if day == 1: print("Monday")
    elif day == 2: print("Tuesday")
    elif day == 3: print("Wednesday")
    elif day == 4: print("Thursday")
    elif day == 5: print("Friday")
    elif day == 6: print("Saturday")
    elif day == 7: print("Sunday")
    else: print("Invalid input")

Output:

![20251026_145552](https://github.com/user-attachments/assets/d4419a89-0b1d-4ddd-94c7-afe57448a072)

![20251026_145554](https://github.com/user-attachments/assets/f683163f-aef9-4072-aa97-edf9d3e52429)

![20251026_145550](https://github.com/user-attachments/assets/e12b11ff-2ada-4fac-a13e-ec61427aa843)


