### Executive Summary
In this lab we will describe various database models and practice querying a database with SQL (structured query language.)  We will Recognize key ethical and legal implications of information systems. We alos get into privacy policies and the different types that apply to technology.  

### Data, Information and Knowledge
##### Rational Data
Data are the raw facts, and may be devoid of context or intent.  For example, a sales order of computers is a piece of data.  Data can be quantitative or qualitative. Quantitative data is numeric, the result of a measurement, count, or some other mathematical calculation. Qualitative data is descriptive. “Ruby Red,” the color of a 2013 Ford Focus, is an example of qualitative data. A number can be qualitative too: if I tell you my favorite number is 5, that is qualitative data because it is descriptive, not the result of a measurement or mathematical calculation.

Information is processed data that possess context, relevance, and purpose.  For example, monthly sales calculated from the collected daily sales data for the past year are information. Information typically involves the manipulation of raw data to obtain an indication of magnitude, trends, in patterns in the data for a purpose.
Knowledge in a certain area is human beliefs or perceptions about relationships among facts or concepts relevant to that area.  For example, the conceived relationship between the quality of goods and the sales is knowledge.  Knowledge can be viewed as information that facilitates action.
Customers and Orders give you information and data.

Primary key would be the customer number.

Customers and Orders would go together because Customers place orders.

I would say a good foreign key would be number of items ordered.

You need dates in a order table to help with breaking down what they order everyday.

##### Big Data
Volume: It represents the amount of data and is one of the main characteristics that makes data “big”. This refers to the mass quantity of data that organizations have been trying to harness and to improve decision making across the enterprise.

Velocity: This characteristic represents the motion of the data. It has changed the mindset of the past that the data of yesterday, past hour or minute is the recent data. The data movement is now almost real time and the update window has reduced to the fraction of a second. Because of this real-time nature of data creation, enterprises have invested a lot to develop Big Data solutions which could incorporate streaming data into business processes and decision making.

Variety: It defines different types of data and data resources. The world has moved beyond the traditional means of structured data like bank statement which included information like date, amount, and time. New categories have been added to the list of data types. Unstructured data i.e. the data that does not have a well-defined set of rules, for example, Twitter feeds, audio files, MRI images, web pages, web logs has contributed immensely to the rise of Big Data.

Veracity: It can be termed as the trustworthiness of the data i.e. calculation of the noises, biases and abnormality in the data. We may also define veracity as the level of reliability associated with certain types of data.

A common traditional approach is to use a sample of the large dataset which could fit in memory, But with the arrival of Big Data, processing tools like Hadoop can now be used to run many exploratory data analysis tasks on full datasets, without sampling. Just write a MapReduce job, PIG or HIVE script, launch it directly on Hadoop over the full dataset, and get the results right back to your laptop.

### Structured Query Language (SQL)
RDBMS is the basis for SQL, and for all modern database systems such as MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access.
SQL is a standard language for accessing and manipulating databases.
The two realted tables I am picking are the ORDERS and the CUSTOMERS the Priamary Key for ORDERS is ORDER ID and the Primary Key for CUSTOMERS is CUSTOMER ID and CUSTOMER ID is also a foreign key for CUSTOMERS. The relationship between both of them is that you need customers to place orders.

### SQL Injections
SQL injection usually occurs when you ask a user for input, like their username/userid, and instead of a name/id, the user gives you an SQL statement that you will unknowingly run on your database.
To protect a web site from SQL injection, you can use SQL parameters.
SQL parameters are values that are added to an SQL query at execution time, in a controlled manner.
### Ethical and Legal Implications
##### Code of Ethics
Code of ethics is a document that outlines a set of acceptable behaviors for a professional or social group; generally, it is agreed to by all members of the group. The document details different actions that are considered appropriate and inappropriate. code of ethics is a document that outlines a set of acceptable behaviors for a professional or social group; generally, it is agreed to by all members of the group. The document details different actions that are considered appropriate and inappropriate.
The ACM has a Code of Ethics because of the varied backgrounds and experiences of the members of a group lead to a variety of ideas regarding what is acceptable behavior. While to many the guidelines may seem obvious, having these items detailed provides clarity and consistency. Explicitly stating standards communicates the common guidelines to everyone in a clear manner.
The AUP is different from a code of Ethics varies but and example of AUP are the terms of service you accept before logging on to a WIFE say like the one at the Cleveland Clinic or TRI-C and Wthics is more based on you behaving yourself.
I chose ESPNs privacy policy and it directs me to Disneys because Disney owns ESPN. I noticed that their privacy policy was recently modified or updated. Which I thought was a great Idea and I see how this can help with updates to stick with social injustices or changes in our laws.
https://privacy.thewaltdisneycompany.com/en/current-privacy-policy/
##### Intellectual Property
WIPO is the global forum for intellectual property (IP) services, policy, information and cooperation. We are a self-funding agency of the United Nations, with 193 member states.
They lead the development of a balanced and effective international IP system that enables innovation and creativity for the benefit of all. Our mandate, governing bodies and procedures are set out in the WIPO Convention, which established WIPO in 1967.
They also make sure that every country has the resources to connect to an IP.
You can go to a copyright office or their website and as an office of record, a copyright registry can make available certificates of registration, certified copies of registry documents that provide, with varying legal effect, important information on a work or other subject matter, its author or, through a documented chain of transfer, its present ownership.  Registration can also help to delimit the public domain, and consequently facilitate access to creative content for which no authorization from the right owner is needed.  The information contained in national registries is not only valuable in legal and economic relations but may also serve the public interest by providing a source of national statistics on creativity and culture.
It is important to copyright your work so somebody doesnt steal it and make it their own. By doing so you can lose out on money and recognition.
The role of a Trademark is as follows: In principle, a trademark registration will confer an exclusive right to the use of the registered trademark. This implies that the trademark can be exclusively used by its owner, or licensed to another party for use in return for payment. Registration provides legal certainty and reinforces the position of the right holder, for example, in case of litigation.
##### Information Collection
These are all Privacy Protections acts that help protect Persons information and data from being shared over the internet by intituting policies that sto that sharing of private information. Starting Childrens Data under the age of 13 (Coppa) Educational right (FERPA) and the one most of us have heard of which is medical information and that is (HIPPA)
### Conclusion
Include your conclusion here...
