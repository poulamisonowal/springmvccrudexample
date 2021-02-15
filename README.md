# springmvccrudexample
This example demonstrates spring mvc integeration with Hibernate for CRUD operations

1) Create MYSQL Database Table
CREATE TABLE `java`.`customer` (
  `id` INT NOT NULL AUTO_INCREMENT,
  `first_name` VARCHAR(45) NULL,
  `last_name` VARCHAR(45) NULL,
  `email` VARCHAR(45) NULL,
  PRIMARY KEY (`id`));


Now we will create spring mvc which will have a form to add new customer, list all existing customers for which you can update and delete information
