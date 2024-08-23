# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Inheritance extends all of the properties from the class that you inherit from.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > Member inheritance is when a subclass adds all of the data from the main class. It inherits all members except for the main class's constructors.

3. How does ***accessibility*** affect inheritance?

  > if something is private, it can only be inherited by a method or class in the same class

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > Primary key is the main differentiating property on a row inside of a table. The foreign key is something that referenes a property from another table.

5. What is an ***alias***?

  > Aliases allow for unambiguous typing of classes to differentiate between two simalarly typed items. 

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > string sql =@"
  SELECT
  patient_doctors.*,
  doctors.*,
  
  FROM patient_doctors
  JOIN doctors ON doctors.id = patient_doctors.patientId
  WHERE doctors.id = 4 
  ;";
