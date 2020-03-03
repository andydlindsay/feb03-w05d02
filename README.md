# W5D2 - Database Design

### To Do
- [ ] Primary Keys/Foreign Keys
- [ ] Data Types
- [ ] Relationship Types
- [ ] Naming Conventions
- [ ] Normalization
- [ ] Design Concepts
- [ ] Entity Relationship Diagrams
- [ ] ERD #1: Convert 2 Spreadsheets
- [ ] ERD #2: Student Suggestion

### Primary Keys/Foreign Keys
- Primary Keys - uniquely identify a particular record
- Has to be unique within the table
- Integer, BigInteger for foreign keys
- Foreign key lives in the many table
- ~~strings as primary keys~~

### Data Types
- This used to be a BIG consideration
- Every field in a table NEEDS a data type
- Always store phone numbers as varchar
- 555-555-5555 5555555555 '(555)-'
- 90210-1000

### Relationship Types
- One-to-many
- One-to-one
- Many-to-many

### Naming Conventions
- table names are always plural and lowercase
- primary keys are always 'id'
- foreign keys are always table singular + `_id`
- multi-words are snake_case

### Normalization
- This is the process of cleaning up the data in a database
- Making sure that you are storing the data correctly with no redundancy
- Storing the same data twice or data that repeats
- `birth_date` and `age`
- 'Canada'
- `countries`
- pk id
- varchar country
- That you can take way too far

### Design Concepts
- Making fields required NOT NULL
- Think about the initial state of the record when it is first created
- Intelligent default values can be inserted for you
- `created_at` default NOW()
- `edited_at`
- Never delete anything DELETE
- `active` boolean false DEFAULT VALUE true
- Consider using a `type` field

### Entity Relationship Diagram
- ERD
- Shows all our entities (tables) and how they are related to one another





















### Useful Links
* [Database Normalization](https://en.wikipedia.org/wiki/Database_normalization)
* [Postgres Data Types](http://www.postgresqltutorial.com/postgresql-data-types/)
* [Relationship Types](http://etutorials.org/SQL/Database+design+for+mere+mortals/Part+II+The+Design+Process/Chapter+10.+Table+Relationships/Types+of+Relationships/)
* [draw.io (online ERD)](https://www.draw.io/)
