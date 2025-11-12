# Inside the URL
Exploring the hidden logic behind web addresses, data, and frameworks

Overview
This project began out of curiosity. I noticed long web addresses (like `https://www.seek.com.au/job/88251786/apply?...`) and wondered what each part of them meant, from the domain to the query parameters.

That question led me to explore:
- How URLs are structured and why query parameters exist.
- How backend frameworks (Django, Ruby on Rails, ASP.NET) use these parameters.
- How the data ultimately connects to a database using SQL.

Technologies Demonstrated
Python : URL parsing and explaining query parameters  
SQL : structuring and analyzing backend data  
Django ORM / Rails ActiveRecord / ASP.NET Entity Framework : to demonstrate how frameworks interact with data  
Markdown & Visualization : for explanation and storytelling

Project Flow
1. Parse a real URL → Break down protocol, domain, path, query string  
2. Store query data in a SQL table  
3. Access data via ORM examples in Django, Rails, and ASP.NET  
4. Visualize how web requests flow from browser → backend → database  

Key Learning Outcomes
- Understanding URL anatomy  
- Practical link between frontend requests and backend data logic  
- Confidence working across multiple web frameworks and SQL  

Example Files
- `url_anatomy/url_breakdown.py` → parses URLs  
- `data_layer/schema.sql` → defines SQL structure  
- `frameworks/django_example.py` → shows how Django ORM interacts with SQL  

Reflection
This project showcases my curiosity-driven approach to learning and my ability to connect different technologies (web, data, backend) into one coherent system.

