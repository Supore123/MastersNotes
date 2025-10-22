
**Course:** [[ELEC0136 AI System Design]]
**Date:** 2025-10-22
**Source:** [Lecture Slides](url)

---
### Learning objectives
		 Data Storage
		 Object models
		 Data Formats
		 Databases
#### Data Storage
		Important factors for determining storage is: object model, the format and the database type
	-- i/e: What we store, how we transfer it and WHO stores it in the end.
**Data Storage**: Data storage is the retention of information using technology specifically developed to keep that data and have it as accessible as necessary

**Object Model**: A data model is the abstraction of a real world object or concept 

An object model is defined by the set 
-- How do we define which properties to store, how do you define a commit object, 

**Minimal Properties:**
	- Only useful properties
	- In the lowest scope possible
	- Orthogonal to each other

-- If both are being used as objects model -- would you use the Author object type. This means it's not

Less hierarchical since it is an object model. 
-- Goal of object
Still an open source 
email Professor about bhom building property


Review the use of vector embedding in the tasks

# Data Formats:
-- Serialisation is the process of converting one schema to another schema
	Databases: A database is an infrustructure to store a large amount of data fast, effciiently and securely. The software for this is called Database Management System. (DBMS)
	-- How many records and properties are utilised suffciently: 
	--> CRUD system:
	Create
	Read
	Update
	Delete

--> Types of databases { SQL, NOSQL, VECTOR}
Expensive computationally for storage structure

--> AI System Design overview of an interview 

# Interview Prep:
-- AI System Design Principles and interviews requirement

NUmber 1: We get a broad question, something incredibly vague

--> i.e: How would you reorganise instagram etc... --> All you require are the handling of the recipes.

Lets say the brief is to Server distribute IMAGENET:
-- Brief needs to be broken down into 2 things:
1) Functional Requirement
2) Non-functional requirements

**Functional Requirements:** Everything that is neccessary for the application to work, it just needs to work, doesn't matter anything else i.e: size, system requirements, user need.

So for our brief, our functional requirements are 
EndPoint for GET training data
EndPoint for VOlume of data
EP for remote data
EP for Updateing data

**Non-Functional Requirements**: all requirements that are non functional for what is needed, but has to do with the performance. I.e: Speed, how the data is handled in optimisation and for example stateless information

--> Stateless and efficient is useful in our example, it doesnt make the system work, but makes it useable for our purposes. This is what is meant by the non-functional requirements

So to make the state machine

**Brief --> Requirements --> Functional and Non-functional Requirements --> talks about the API's --> Then the Database for how this is going to be handled --> this goes into the Data Flow.** 

--> This is 80% of the system design interview 
--> More detailed analysis on each component might be required -- this will be reviewed in the above state machine. These are the deep dives as defined. 

--> Consider the options on the specifics at some point --> i.e: might talk about more in the data points or object models. Talk about them as the datapoint -- this is implementable in the python code at this point. Need to consider the entire pipeline here for the 

Use the interview as its own context -- this makes it easier and more functional. 

## 🧮 Math & Intuition
$$
y = f(x; \theta)
$$

## 🧠 Insights
- 

## 🔗 Related Topics
- [[Neural Networks]]
- [[Gradient Descent]]
