# Novigrad-Service
This application implements the basic functionality for services offered by an imaginary province called Novigrad to its residents. The services offered by Service Novigrad are similar to those provided by Service Ontario or Services Québec which allow citizens to obtain a driver’s license, photo ID, or health  card.

## Details
- I worked in a team of 4 to create a mobile project using Android Studio and Firebase as database. 
- This project's learning outcoms range from UML design and increased understanding of concepts relating to software engineering, to overall knowledge of programming for android, management and team-relation skills.
- The admin credentials are set by default to: [  username="admin"  &  password="123admin456"  ]

## Users
There is three types of users: Admin, Customers annd Employees.
- The administrator can:
  - Login to an administrator account - the developer should pre-create such an account (e.g. 
username: admin, password: 123admin456)
  - Create, edit, or delete services (at least 3 as elaborated below, but the more the better) that could
be offered by Service Novigrad branches, and specify the required information and documents that 
need to be supplied by a customer requiring a service:
    - Driver’s license: 
      1. Form: Including customer first name, last name, date of birth, address, license type (G1, G2, G) 
      2. Documents: Proof of residence (An image of a bank statement or hydro bill that shows the address)
    - Health card:
      1. Form: Including customer first name, last name, date of birth, address
      2. Documents: Proof of residence (An image of a bank statement or hydro bill that shows the address)
      3. Proof of status (An image of a Canadian permanent resident card or a Canadian passport)
    - Photo ID:
      1. Form: Including customer first name, last name, date of birth, address
      2. Documents: Proof of residence (An image of a bank statement or hydro bill that shows the address) – A photo of the customer
  - Delete accounts of branches and customers.

- The Service Novigrad branch employee can: 
  - Create an account for the branch and login to that account
  - Select services provided
  - Enter the working hours of the branch
  - View submitted service requests, and either approve or reject each request

- The customer can: 
  - Create an account and login to that account
  - Search for a Service Novigrad branch by address/type of service provided/working hours
  - Select a service they would like to purchase
  - Fill in the required information and documents, then submit the service request.
  - Rate their experience with the Service Novigrad branch
