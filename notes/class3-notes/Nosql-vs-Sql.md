# Data Modeling

## Why this section matters?

Talking about the data and how it can be stored is crucial for any programmer, since all application are built over tranporting data from and to data bases, so knowing which type of data bases to use based on the requirement of your application, would help you manage and make cost effective applications with wider functionalities.

## NoSQL vs SQL

**What type of database is the best fit for the complex query intensive environment?**

>Sql databases are more effective handling complex queries environements.

**What type of database is the best fit for hierarchical data storage?**

> NoSQL databases are more fit handling teh heirarchial data since data is stored in a format similar to JSON.

**Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.**

> Talking about scalability, it means the effort needed when the data you want to store gets larger and larger with time. imagine you have a moneybox and you want to save money by adding a penny everyday, at the end that moneybox won't be able to handle more of the pennies so you have to buy or upgrade your moneybox to a larger one. that's the way how SQL deals with scaling data. this is called Vertical scaling.
On the other hand talking about NoSql since it's horizontally scaled, imagine you have a fish bowl and you put only a certain type of fishes that can live together in it, when want to add new types or species of fishes, you will keep in mind that the new fishes might eat the other ones, so you will bring another fish bowl and add your fishes to, and thats how NoSQL databases deals with data, since each data usually is unrelational, you will just need more data servers those would serve certain types of data at a certain site of your website. this is called horizontally scaling.

## SQL modeling techniques

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**

>in tables those have a relationship as one-to-many, it means that this table has data that will influence the change on other data tables, for example if we considered the hospital protocol  as a one table. and the departments of that hospital are in a different table, once the protocol of the hospital changes, all the departments processes will change responding to that change, they are "related" many will change based on a change of one!, we relate them using the primary key and foreign keys, which are like linking points to define the direction of change.

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

> Create a diagram.

**Explain the difference between a primary and foreign key.**

>Simply, a primary key is the unique key that points to the current table we are dealing with, it's pointing to the data of that table, each data entry has a key. while the foreign key is the key we use to refer to other tables primary keys. so we could say it's a secondary key that will link us to other tables values or data.

## SQL vs NoSQL (video content)

**How do we treat keywords and parameters differently in SQL syntax?**

>Key words are already declared variables or functions in the language itself, it can't be used as identifires for other functionalities. while parameters are those containers that considered as variables, usually accepting values passed by the user to make up dynamic operations.

**Define normalization within the context of schemas and data.**

> Normalization is putting the right content under the right headline or more specifically the correct table headling, it's a process that we distribute all data under the right section, so the data in that part will make sense to which it refers to. a schema will help us doing that because it is like the skeletal structure of that data form. it will specify where each data takes place and under which section it will be stored.

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

in a non-technical way it's like our relationships in our life

- > one to one, is like the relation between you and your close best friend, you deal with him only in situations you both have in common, you are both related in but seperately from the others around you. so gifting him a gift for example, will only make him happy. a single targeted influence.

- > one to many, is like the relationship between you and your class mates, when you post on the communication media between you and your mates, something let's say about the exam, they all will get informed and all will make an action as a response, so you affected all of them once you made a process.

- > Many to many relationships, it's like a programming company where there is those working on the front end side (the interface of the application you use) and those working on the back end (the data organizing team) where each department contains different teams, and each team influence other teams on the other department, for example one team in the back end had there error in the data responsible on showing you your facebook groups, the frontend team will be affected and the work they built to show you beautiful sections and posts from each group you are in will get broken, that's how they are related! many things could influence many changes on many sides. it's a bit complicated!

## Things I want to know more about

I want to learn more about NoSQL, and would like to know more about choosing between them. Would love to learn MongoDB too cause it's widely used.
