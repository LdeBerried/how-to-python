# Capstone Project

# Modules

## User retrieval
Using [jsonplaceholder users API](https://jsonplaceholder.typicode.com/users), all Users must be retrieved and setting up onto a class.

## User operations

Each user must have several private and public methods to operate with each User's property. For every User you should be able to:
- Move out to another address
- Update contact information (email, phone and website)
- Hire and fire from a company

### Moving out

When a user moves out, the address must be updated and the user must be notified by email.
Previous data doesn't need to be stored.
Adress information doesn't have to be validated.
Adress information can be updated field by field. It doesn't have to be updated all at once.
Fields that can be updated are:
- Street
- Suite
- Postal code
- City

### Updating contact information

When a user updates their contact information, the user must be notified by email.
Previous data doesn't need to be stored.
Contact information has to be validated.
Contact information has to be updated all at once.
Fields that can be updated are:
- Email
- Phone
- Website

### Hiring and firing

When a user is hired or fired, the user must be notified by email.
When a user is hired you can chose from a list of companies already existing or create a new one.
When a user is fired, company data in the user's profile must be deleted.


## Filtering

For the whole set of users, filters should be set such that subsets of users that can be retrieved:

 - Their surname begins with the letter M
 - The company they work for is involved in something application related
 - Search by location and show the 2 closest users.
