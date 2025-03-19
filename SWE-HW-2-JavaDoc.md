# Matching Javadoc strings
In the 2nd SWE homework, students are given a bunch of javadoc comments and asked to put them in the right places.
At the time of making this post, these are the given comments:

![Screenshot 2025-03-19 195500](https://github.com/user-attachments/assets/4f97033a-4820-4d42-9512-5a4a6137ca4e)


To make it easier to copy, here they are in plain text:
```java
/**
 * Associates a probability with a country of origin.
 *
 * @param countryId a two-letter country code
 * @param probability a probability, i.e., a number between 0 and 1
 */

/**
 * {@return the possible countries of origin for the last name specified}
 *
 * @param name a last name
 * @throws feign.FeignException if any error occurs
 */

/**
 * CLI for the {@code nationalize} package.
 */

/**
 * {@return an object implementing the {@code NationalizeClient} interface}
 */

/**
 * {@return an optional wrapping the most likely country of origin for the
 * name}
 */

/**
 * Client interface to query the possible countries of origin for a last name.
 * The {@link #newInstance()} method is provided to obtain a
 * {@code NationalizeClient} object.
 */

/**
 * Stores the possible countries of origin for a last name.
 *
 * @param count the number of rows examined
 * @param name a last name for which the possible countries of origin are
 *             predicted
 * @param countries a list of the most likely countries of origin
 */
```



Well, here are the right places:

***

### Comment 1
Comment 1 goes above the **Country** record nested inside the **Nationality** class

![image](https://github.com/user-attachments/assets/c5bc0329-62ed-4f0c-a04f-5bb3634a15df)

### Comment 2
Comment 2 goes above the **getNationality** method definition in the **NationalizeClient** interface 

![image](https://github.com/user-attachments/assets/933049c1-6266-403d-aab1-25c1593e95b8)

### Comment 3
Comment 3 goes above the **Main** class

![image](https://github.com/user-attachments/assets/5fcf7641-dcd6-4a99-9ac1-920e68f54c14)

### Comment 4
Comment 4 goes above the **newInstance** method in the **NationalizeClient** interface

![image](https://github.com/user-attachments/assets/ecfa7e65-d109-4588-a13c-585ac16761b0)


### Comment 5
Comment 5 goes above the **getMostLikelyCountry** method in the **Nationality** class

![image](https://github.com/user-attachments/assets/75f8101a-60a6-4ee8-911d-7e8e1b6e44cc)


### Comment 6
Comment 6 goes above the **NationalizeClient** interface

![image](https://github.com/user-attachments/assets/f5a2d571-9d28-48f2-8907-271467eca853)


### Comment 7
Comment 7 goes above the **Nationality** class

![image](https://github.com/user-attachments/assets/00a528a1-1a17-4bc8-94ec-52f2ce1cd26f)

