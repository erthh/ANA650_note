# ANA650
*Focus on Relational Database

#### Type of data
**Unstructure data:** Notepad style 
**Structure data:** Data in Mark up language eg. XML and JSON etc. 

#### What's database 
Database for example like Facebook, Amazon, Ebay.
Vendors (Who create the software) like oracle and microsoft.


#### Entity Relationship Model (ERM)
- Entity Relationship Diagram (ERD)
##### Database's main components
- Entities: A box with some attributes in side example Entities name Student and contain name, major, age, etc. 
- Attributes
  - Required Attribute: Must have value 
  - Optional Attribute: Does not require
- Relationships:  


##### Example of Enrities

|Student|
| ----------- |
| name |
| age | 
| major |


##### Relationship (Strong/Weak) and Unary
- Strong: ถ้าสองตัวเชื่อมถึงกัน เวลาสร้างตัวแม่เเล้วต้องส้รางตัวลูกด้วย Primary key 
- Weak: สร้างอันไหนมาก่อนก็ได้ Foreige Key 
- Unary Relationship: Relationships of attribute in the same entity like employee and manages (Recursive relationships)

##### Compasite Entity or Brides (Many to Many relationship and 3 or more entities)
- Used to represent an M:N relationship between two or more entities
- Is in a 1:M relationship with the parent entities
  - Composed of the primary key attributes of each parent entity
- May also contain additional attributes that play no role in connective process
- เช่นถ้า นักเรียน -> คราส (M:N) ต้องมีตัวกลางมาบอกว่า นักเรียนคนไหนอยู่คราสไหน ถ้ามีแค่ 2 entity จะไม่รู้ (3 boxes)
- reduce redundancy 
- use a lot !! 


### Week2 Monday

#### 3 type of relationship
- One to Many 
- Many to Many 
- One to One 

#### The Relational Database Model 
- Database in 'table' form which has row(tuples) and col(attributes). This is easier to understand than bigdata or cloud database.
- offer logical view of data 
- 

#### Keys
PK(Primary Key): somethings uniquely indentify row.
FK(Foreign Key): key that link to other entity 
Composite key: key that compose more than one attribute (when no unique key and unique attribute)
Secondary Key: example I don't know "bank account number" but when I give "phone number(2nd key)" I can pull out the "bank account number"

#### way to handle null
- falgs: like dummy value to tell that null 
- Not Null constraint: to ensure the column has value in every row
- Unique contraint: Restriction to ensure no duplicate value in column 


#### Joins 
Inner join: returns only matched records from tables that are being joined - โชว์ตารางที่มีเหมือนกัน
Outer join: Matched pairs are retained and unmatched values in the other table are left null - โชว์ตารางทุก value แม้จะมีเหมือนกันหรือมีไม่เหมือนกัน(จะโชว์ null)

#### Many to Many relationship
- create bridge in the middle amd careate composite entity 
- transform to "1 to many"
- 

#### MySQL (On and Where systax)
- The ON clause defines the relationship between the tables.
- The WHERE clause describes which rows you are interested in.





