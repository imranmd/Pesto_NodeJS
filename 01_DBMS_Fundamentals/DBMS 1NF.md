[next →](https://www.javatpoint.com/dbms-second-normal-form) [← prev](https://www.javatpoint.com/dbms-normalization)

## First Normal Form (1NF)

-   A relation will be 1NF if it contains an atomic value.
-   It states that an attribute of a table cannot hold multiple values. It must hold only single-valued attribute.
-   First normal form disallows the multi-valued attribute, composite attribute, and their combinations.

**Example:** Relation EMPLOYEE is not in 1NF because of multi-valued attribute EMP\_PHONE.

**EMPLOYEE table:**

| EMP\_ID | EMP\_NAME | EMP\_PHONE | EMP\_STATE |
| --- | --- | --- | --- |
| 14 | John | 7272826385,  
9064738238 | UP |
| 20 | Harry | 8574783832 | Bihar |
| 12 | Sam | 7390372389,  
8589830302 | Punjab |

The decomposition of the EMPLOYEE table into 1NF has been shown below:

| EMP\_ID | EMP\_NAME | EMP\_PHONE | EMP\_STATE |
| --- | --- | --- | --- |
| 14 | John | 7272826385 | UP |
| 14 | John | 9064738238 | UP |
| 20 | Harry | 8574783832 | Bihar |
| 12 | Sam | 7390372389 | Punjab |
| 12 | Sam | 8589830302 | Punjab |

  

Next Topic[DBMS 2NF](https://www.javatpoint.com/dbms-second-normal-form)

[← prev](https://www.javatpoint.com/dbms-normalization) [next →](https://www.javatpoint.com/dbms-second-normal-form)

___

![Youtube](https://static.javatpoint.com/images/youtube-32.png) For Videos Join Our Youtube Channel: [Join Now](https://bit.ly/2FOeX6S)

___

### Feedback

-   Send your Feedback to feedback@javatpoint.com

___

## Help Others, Please Share

[![facebook](https://www.javatpoint.com/images/facebook32.png)](https://www.facebook.com/sharer.php?u=https://www.javatpoint.com/dbms-first-normal-form "Facebook") [![twitter](https://www.javatpoint.com/images/twitter32.png)](https://twitter.com/share?url=https://www.javatpoint.com/dbms-first-normal-form "Twitter") [![pinterest](https://www.javatpoint.com/images/pinterest32.png)](https://www.pinterest.com/pin/create/button/?url=https://www.javatpoint.com/dbms-first-normal-form "Pinterest")

___

___

___

___