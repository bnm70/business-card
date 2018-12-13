# business-card-parser
The BusinessCardParser class takes a text file with information from a business card and finds the name, email, and phone of the card's owner. BusinessCardParser relies on instances of the ContactInfo class to store the data from each business card.

## Introduction
### Prerequisites 
Both the BusinessCardParser class and the ContactInfo class were written in JavaSE- 1.6. 

### Implementation
The ContactInfo and BusinessCardParser must both be placed in the same package. In the main method in the BusinessCardParser class, replace the parameter "path" with a path(formatted as a string) linking to the text file of the business card. 

## Tests


### Limitations:
If two phone numbers are given (telephone and fax), the first phone seen on the card will be printed.
If there is no email found, a name will not be found.
To find the name, it is assumed that a business email has the first and last name included in one of the following formats:
firstlast
flast
firstl
Any 


