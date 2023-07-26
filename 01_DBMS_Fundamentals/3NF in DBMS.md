[next →](https://www.javatpoint.com/dbms-boyce-codd-normal-form) [← prev](https://www.javatpoint.com/dbms-second-normal-form)

-   A relation will be in 3NF if it is in 2NF and not contain any transitive partial dependency.
-   3NF is used to reduce the data duplication. It is also used to achieve the data integrity.
-   If there is no transitive dependency for non-prime attributes, then the relation must be in third normal form.

A relation is in third normal form if it holds atleast one of the following conditions for every non-trivial function dependency X → Y.

1.  X is a super key.
2.  Y is a prime attribute, i.e., each element of Y is part of some candidate key.

**Example:**

**EMPLOYEE\_DETAIL table:**

| EMP\_ID | EMP\_NAME | EMP\_ZIP | EMP\_STATE | EMP\_CITY |
| --- | --- | --- | --- | --- |
| 222 | Harry | 201010 | UP | Noida |
| 333 | Stephan | 02228 | US | Boston |
| 444 | Lan | 60007 | US | Chicago |
| 555 | Katharine | 06389 | UK | Norwich |
| 666 | John | 462007 | MP | Bhopal |

**Super key in the table above:**

1.  {EMP\_ID}, {EMP\_ID, EMP\_NAME}, {EMP\_ID, EMP\_NAME, EMP\_ZIP}....so on  

**Candidate key:** {EMP\_ID}

**Non-prime attributes:** In the given table, all attributes except EMP\_ID are non-prime.

Here, EMP\_STATE & EMP\_CITY dependent on EMP\_ZIP and EMP\_ZIP dependent on EMP\_ID. The non-prime attributes (EMP\_STATE, EMP\_CITY) transitively dependent on super key(EMP\_ID). It violates the rule of third normal form.

That's why we need to move the EMP\_CITY and EMP\_STATE to the new <EMPLOYEE\_ZIP> table, with EMP\_ZIP as a Primary key.

**EMPLOYEE table:**

| EMP\_ID | EMP\_NAME | EMP\_ZIP |
| --- | --- | --- |
| 222 | Harry | 201010 |
| 333 | Stephan | 02228 |
| 444 | Lan | 60007 |
| 555 | Katharine | 06389 |
| 666 | John | 462007 |

**EMPLOYEE\_ZIP table:**

| EMP\_ZIP | EMP\_STATE | EMP\_CITY |
| --- | --- | --- |
| 201010 | UP | Noida |
| 02228 | US | Boston |
| 60007 | US | Chicago |
| 06389 | UK | Norwich |
| 462007 | MP | Bhopal |

  

Next Topic[DBMS BCNF](https://www.javatpoint.com/dbms-boyce-codd-normal-form)

[← prev](https://www.javatpoint.com/dbms-second-normal-form) [next →](https://www.javatpoint.com/dbms-boyce-codd-normal-form)

___

![Youtube](https://static.javatpoint.com/images/youtube-32.png) For Videos Join Our Youtube Channel: [Join Now](https://bit.ly/2FOeX6S)

___

### Feedback

-   Send your Feedback to feedback@javatpoint.com

___

## Help Others, Please Share

[![facebook](https://www.javatpoint.com/images/facebook32.png)](https://www.facebook.com/sharer.php?u=https://www.javatpoint.com/dbms-third-normal-form "Facebook") [![twitter](https://www.javatpoint.com/images/twitter32.png)](https://twitter.com/share?url=https://www.javatpoint.com/dbms-third-normal-form "Twitter") [![pinterest](https://www.javatpoint.com/images/pinterest32.png)](https://www.pinterest.com/pin/create/button/?url=https://www.javatpoint.com/dbms-third-normal-form "Pinterest")

___

___

___

___