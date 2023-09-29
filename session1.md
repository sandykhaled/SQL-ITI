## DB Design

1-Analysis => system analyst <br/>
2-DB Design <br/>
ERD (non-constant) => DB Designer <br/>
Entity is an object Not table <br/>
3-Mapping DB => DB Designer <br/>
set of rules (constant) <br/>
4- DB implementation => DB Developer <br/>
RDBMS => tools (sql server, oracle, mysql ) <br/>
Laptop => DB Server <br/>
5- Applicaion = GUI = interface <br/>
6-client = End User (Application server)<br/>
user of DB = application programmer <br/>
## File Based System

1. delimited File (10,ali,24) seprate between items by ',' 
2. Fixed Width File (fixed bit) 

**DisAdvantages**  
1. diff Search 
2. low Performance
3. No relationship 
4. No DB Integrity
5. Separted Copies 
6. DB Duplication 
7. Long Develoment Time 
8. Security & Premissions 
9. Constraints & Rules 
10. No Data Quality 
11. Manual Backup & Store 
12. No Standard 
13. Diff Integration 
## DB System
**Tables & Relationship**
1. Meta Data (eg:foreign key) & Data (Values) 
2. Primary Key (Unique , Not null)
3. Colimn => DataType
4. One Standard
5. Centralized DB
## Basic Definitions
DataBase : collection of related data
DBMS : Software Package 
DB System : DB+DBMS
<br/> **NOTE** <br/>
property in relationship means property shared between 2 entities
<br/>
Relationship between 2 entites may be more than one relationship , but with different meaning
<br/>
Verb is Relationship , Noun may be entity or attribute
## ERD
**Entity**
1. Weak Entity : child will disappaer when a parent disappear
2. Strong Entity : Parent <br/>
**Note**  Weak Entity may be different from stsytem to other . Primary Key of Weak Entity is a partial key <br/>
**Attribute**
1. Simple Attribute
2. Composite Attribute (first name+last name)
3. Derived Attribute(DB,Age)
4. Multivalue (phone,Address)
5. Complex(MultiValue,Composite) Address(country,city,Street) <br/>
Eg: I have multi phone number . Each phone Number has (Zip code+Number).
**Relationship**
1. Degree of RelationShip (unary,binary,ternay)<br/>
 **NOTE** Rescursive (unary,Self) <br/>
2. Cardinality Constraint
   1. one to one
   2. many to one
   3. one to may
3. Participation Cardinality
   


