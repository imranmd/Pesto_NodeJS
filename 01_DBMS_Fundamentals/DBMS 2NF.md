[next →](https://www.javatpoint.com/dbms-third-normal-form) [← prev](https://www.javatpoint.com/dbms-first-normal-form)

## Second Normal Form (2NF)

-   In the 2NF, relational must be in 1NF.
-   In the second normal form, all non-key attributes are fully functional dependent on the primary key

**Example:** Let's assume, a school can store the data of teachers and the subjects they teach. In a school, a teacher can teach more than one subject.

**TEACHER table**

| TEACHER\_ID | SUBJECT | TEACHER\_AGE |
| --- | --- | --- |
| 25 | Chemistry | 30 |
| 25 | Biology | 30 |
| 47 | English | 35 |
| 83 | Math | 38 |
| 83 | Computer | 38 |

In the given table, non-prime attribute TEACHER\_AGE is dependent on TEACHER\_ID which is a proper subset of a candidate key. That's why it violates the rule for 2NF.

To convert the given table into 2NF, we decompose it into two tables:

Video Player is loading.

Current TimeÂ 0:00

DurationÂ 0:00

Loaded: 0%

Stream TypeÂ LIVE

Remaining TimeÂ 0:00

Â 

**TEACHER\_DETAIL table:**

| TEACHER\_ID | TEACHER\_AGE |
| --- | --- |
| 25 | 30 |
| 47 | 35 |
| 83 | 38 |

**TEACHER\_SUBJECT table:**

| TEACHER\_ID | SUBJECT |
| --- | --- |
| 25 | Chemistry |
| 25 | Biology |
| 47 | English |
| 83 | Math |
| 83 | Computer |

  

Next Topic[DBMS 3NF](https://www.javatpoint.com/dbms-third-normal-form)

[← prev](https://www.javatpoint.com/dbms-first-normal-form) [next →](https://www.javatpoint.com/dbms-third-normal-form)

___

![Youtube](https://static.javatpoint.com/images/youtube-32.png) For Videos Join Our Youtube Channel: [Join Now](https://bit.ly/2FOeX6S)

___

### Feedback

-   Send your Feedback to feedback@javatpoint.com

___

## Help Others, Please Share

[![facebook](https://www.javatpoint.com/images/facebook32.png)](https://www.facebook.com/sharer.php?u=https://www.javatpoint.com/dbms-second-normal-form "Facebook") [![twitter](https://www.javatpoint.com/images/twitter32.png)](https://twitter.com/share?url=https://www.javatpoint.com/dbms-second-normal-form "Twitter") [![pinterest](https://www.javatpoint.com/images/pinterest32.png)](https://www.pinterest.com/pin/create/button/?url=https://www.javatpoint.com/dbms-second-normal-form "Pinterest")

___

___

___

___