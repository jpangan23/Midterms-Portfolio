Midterm Lab Task 1

Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc)
for the problem below

<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/36ef41b0-8eb0-48a6-b989-7ca336cb4fe0" />

Source Code:

      name = "John Doe"
      email = "john.doe@example.com"
      university = "ABC University"
      
      print("Database Record ")
      print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\ ")
      print(f"Name:\t\t\t\t\t {first_name } {last_name }")
      print(f"Email: \t\t\t\t\t {email}" )
      print(f"University: \t\t {university}" )

Output:

<img width="654" height="322" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/e7af4578-f2be-433e-9f80-5954f8e0b205" />




Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f
etc… for this task

<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/938b8d73-0adf-44ed-bf8b-e8bedf73e16d" />

Source Code:
   
    sender = "Jane"
    subject = "Greetings"
    version = 1.2
    discount = "10.50%"
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    
    print("Dear John, I hope this email finds you well.")
    print("I wanted to reach out and say hello.")
    print("I hope you are doing well and enjoying your day.")
    print("It's been a while since we last spoke, and I wanted to catch up with you.")
    print("Let's plan to meet up soon and have a great time together!")
    print(f"Subject: %s" %subject)
    print(f"Sender: %s" %sender)
    print(f"Version: %.1f" %version)
    print(f"Discount: %s" %discount)
    print(f"Status: %s" %status)
    print(f"Code: %s")
    print(f"Location: %s" %location)
    print(f"Age: %d" %age)
    print(f"Company: %s" %company)
    print(f"Website: %s" %website)
    print(f"Phone: %s" %phone)
    print(f"Job Title: %s" %job_title)
    print(f"Department: %s" %department)


Output:

<img width="613" height="468" alt="Screenshot (84)" src="https://github.com/user-attachments/assets/8afc35a5-701b-4aa5-b82a-98edd6a387ae" />




Problem 3. Book Reservation; Accept User Input

<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/03c18810-af02-4d1d-aa3b-b0d9169f9948" />

Source Code:
   
    book_title = (input("Enter the book title:  ")
    book_author = input("Enter the book author:  ")
    year_of_publication =int(input("Enter the year of publication:  "))
    book_genre = input("Enter the book genre:  ")
    library = input("Enter the library:  ")
    member_id = input("Enter your member ID:  " )
    return_date = input("Enter the return date:  ")
    
    print(f"You have successfully reserved the book '{book_title}' by {book_author}.")
    print(f"Year of Publication: {year_of_publication}")
    print(f"Genre: {book_genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")




Output:

<img width="605" height="463" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/ddfbfb61-0571-421f-b32f-db4f41f6d466" />



Problem 4. Day Identifier

<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/10e36142-6c97-4fbc-8e53-4670d4b073b9" />


Source Code:
   
    day = int(input("Enter day:   "))
 
    if day == 1 :
    print("Monday")
    elif day == 2 :
    print("Tuesday")
    elif day == 3 :
    print("Wednesday")
    elif day == 4 :
    print("Thursday")
    elif day == 5 :
    print("Friday")
    elif day == 6 :
    print("Saturday")
    elif day == 7 :
    print("Sunday")
    else:
    print("Invalid input")





Output:

<img width="389" height="621" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/08062ef2-c423-4a25-9d7e-08b830ac4275" />
