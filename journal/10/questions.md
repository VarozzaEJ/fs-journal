# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > namespaces add scope to files and prevent name collisions.

02. What is the difference between a `class` and an `interface`?

  > Interfaces don't implement the methods they specify inside them.

03. What is the method that returns an instance of a class, yet it has no return type?

  > Dependency, the method is 
  private readonly fileName _fileName;

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > "public"

06. In the Car example what is `string` an indication of?

  > the type of what will be returned as well as what is expected

07. In the Car example what is `abstract` preventing?

  > this requires the class to be inherited by another 'method?'. Abstract restricts object creations.

08. In a SQL table, what is the difference between information in a row and information in a column?

  > columns are the individual properties of a dataset, i.e bedrooms, bathrooms, squarefeet. Rows are the items that each have all of the properties.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE characters(
    id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    description VARCHAR(255) NOT NULL,
    age VARCHAR(255) NOT NULL,
  );

10. In SQL how can you query more than a single table? Provide an example.

  > SELECT * FROM table1, table2
  > JOIN table2 ON table1.id = table2.id
