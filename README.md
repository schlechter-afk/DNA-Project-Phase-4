# DNA-Project-Phase-4

```
Names : Rohan Kumar , Yash Kawade , Swayam Agrawal
Roll Nos: 2021101070 , 2021101032 , 2021101068
Branch : CSE
Course : Data And Applications , Monsoon'22
```
VIDEO DEMONSTRATING CLI : https://iiitaphyd-my.sharepoint.com/:v:/g/personal/swayam_agrawal_students_iiit_ac_in/EbDxTbtQ-SZNmGg2GrR0I6sBrXUJjbBNuciUbBplBx9mWQ?e=DC46i3

# **_List of Commands the command-line-interface can run_**

The commands have been divided intp two types: 

``` RETRIEVAL ```
```
which has been further divided into 5 different type of Queries:

1. SELECTION
2. PROJECTION
3. AGGREGATE
4. SEARCH
5. ANALYSIS
```

``` MODIFICATION ```
```
which has been divided into 3 type of Queries: 

1. INSERTION
2. UPDATION
3. DELETION 
```

# **High-Level Description of RETRIEVAL COMMANDS**

```
SELECTION: 

1. Extract List of All Flats:

   User can view all the attributes of each flat with this command.

2. Extract List of All Residents:

   User can view all the attributes of each resident residing in the Society.

```

```
PROJECTION: 

1. Show visitors of a particular flat:

   User can view all the visitors in the society at the present moment with all the details of the vistor along with the flat-number visiting.

2. Show complaints registered by a particular flat.:

   User can view all the complaints which were registered by a particular flat along with its resolve status - 1 if resolved else 0 if unresolved.

```

```
AGGREGATE: 

1. Total Number of Residents in a house:

   User can view all the number of residents residing in each flat of the society.

2. Total number of requests of a particular flat:

   User can view the number of requests made by each flat.

```

```
SEARCH: 

1. Search Residents by Aadhar ID:

   User can extract all the information about a resident with the input Aadhar_ID.

2. Search Requests by Flat_Number:

   User can view all the requests and their type made by the input flat number.

```

```
ANALYSIS: 

Analytical Queries have been supported so the user can get the following information also:

1. Getting a cummulative count of request and complaints lodged by flat
2. Getting the gender-ratio in the RWA
3. Getting the maximum number of visitors in flat

```

# **High-Level Description of MODIFICATION COMMANDS**

```
INSERTION: 

1. Add a new resident in a flat:

   Functionality has been added so that a new member can be added as a resident to a flat.

2. Adding new members to RWA:

   User can add new members to the RWA committee assigning responsibilty to them and getting all details of that member. 

```

```
UPDATION: 

1. Update Resolve Status of a Complaint:

   User can update the resolve status of a complaint lodged by a flat if it gets resolved.

2. Update Responsibility of a member in RWA:

   User can update the responsibilty of a existing member in RWA , for example changing the responsibility of a member from `SUPPLY` responsibilty to `REQUESTS` responsibility. 

```

```
DELETION: 

1. Delete Visitor for a Particular Flat:

   User can delete a vistor from the database if the visitor exits the society.

2. Delete member From RWA:

   User can delete a member from the RWA in-case a member has decided to quit the committee.

```
