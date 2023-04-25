# structures
Algorithm for the given C code:

1. Define a structure named "employee" with integer and character variables to hold employee details.
2. Declare a structure variable "a" of the "employee" structure type.
3. In the "main" function:
   a. Prompt the user to enter the employee details using "printf" statements.
   b. Read the employee details from the user using "scanf" statements.
   c. Print the employee details entered by the user using "printf" statements.

The detailed steps of the algorithm are as follows:

1. Define a structure named "employee" with the following integer and character variables:
   a. "e" to hold the employee ID.
   b. "name" to hold the name of the employee.
   c. "designation" to hold the designation of the employee.
   d. "dept" to hold the department of the employee.
   e. "sal" to hold the salary of the employee.
   
   The structure can be defined as follows:
   
   struct employee
   {
       int e;
       char name[50];
       char designation[20];
       char dept[20];
       int sal;
   };

2. Declare a structure variable "a" of the "employee" structure type. This can be done using the following statement:

   struct employee a;

3. In the "main" function:
   a. Prompt the user to enter the employee details using "printf" statements.
   
      printf("Enter Your Employee Details: \n");
      printf("-------------------------------\n");
      printf("Enter Your Employee-Id: ");
   
   b. Read the employee details from the user using "scanf" statements.
   
      scanf("%d", &a.e);
      scanf("%s", a.name);
      scanf("%s", a.designation);
      scanf("%s", a.dept);
      scanf("%d", &a.sal);
   
   c. Print the employee details entered by the user using "printf" statements.
   
      printf("-------------------------------\n");
      printf("Employee Details: ");
      printf("\n-------------------------------\n");
      printf("Employee-Id : %d\n", a.e);
      printf("Name : %s\n", a.name);
      printf("Designation : %s\n", a.designation);
      printf("Department : %s\n", a.dept);
      printf("Salary : %d\n", a.sal);

4. End of the algorithm.
