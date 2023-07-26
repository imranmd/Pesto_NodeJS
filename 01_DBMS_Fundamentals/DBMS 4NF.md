[next →](https://www.javatpoint.com/dbms-fifth-normal-form) [← prev](https://www.javatpoint.com/dbms-boyce-codd-normal-form)

## Fourth normal form (4NF)

-   A relation will be in 4NF if it is in Boyce Codd normal form and has no multi-valued dependency.
-   For a dependency A → B, if for a single value of A, multiple values of B exists, then the relation will be a multi-valued dependency.

### Example

**STUDENT**

| STU\_ID | COURSE | HOBBY |
| --- | --- | --- |
| 21 | Computer | Dancing |
| 21 | Math | Singing |
| 34 | Chemistry | Dancing |
| 74 | Biology | Cricket |
| 59 | Physics | Hockey |

The given STUDENT table is in 3NF, but the COURSE and HOBBY are two independent entity. Hence, there is no relationship between COURSE and HOBBY.

In the STUDENT relation, a student with STU\_ID, **21** contains two courses, **Computer** and **Math** and two hobbies, **Dancing** and **Singing**. So there is a Multi-valued dependency on STU\_ID, which leads to unnecessary repetition of data.

So to make the above table into 4NF, we can decompose it into two tables:

Video Player is loading.

Current TimeÂ 0:00

DurationÂ 0:00

Loaded: 0%

Stream TypeÂ LIVE

Remaining TimeÂ 0:00

Â 

**STUDENT\_COURSE**

| STU\_ID | COURSE |
| --- | --- |
| 21 | Computer |
| 21 | Math |
| 34 | Chemistry |
| 74 | Biology |
| 59 | Physics |

**STUDENT\_HOBBY**

| STU\_ID | HOBBY |
| --- | --- |
| 21 | Dancing |
| 21 | Singing |
| 34 | Dancing |
| 74 | Cricket |
| 59 | Hockey |

  

Next Topic[DBMS 5NF](https://www.javatpoint.com/dbms-fifth-normal-form)

[← prev](https://www.javatpoint.com/dbms-boyce-codd-normal-form) [next →](https://www.javatpoint.com/dbms-fifth-normal-form)

___

![Youtube](https://static.javatpoint.com/images/youtube-32.png) For Videos Join Our Youtube Channel: [Join Now](https://bit.ly/2FOeX6S)

___

### Feedback

-   Send your Feedback to feedback@javatpoint.com

___

## Help Others, Please Share

[![facebook](https://www.javatpoint.com/images/facebook32.png)](https://www.facebook.com/sharer.php?u=https://www.javatpoint.com/dbms-forth-normal-form "Facebook") [![twitter](https://www.javatpoint.com/images/twitter32.png)](https://twitter.com/share?url=https://www.javatpoint.com/dbms-forth-normal-form "Twitter") [![pinterest](https://www.javatpoint.com/images/pinterest32.png)](https://www.pinterest.com/pin/create/button/?url=https://www.javatpoint.com/dbms-forth-normal-form "Pinterest")

___

___

___

___