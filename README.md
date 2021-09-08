# assignment2-Gundla

# Prudvi Reddy Gundla

##### France
**France** is a country in western Europe, surrounded on the west by the North Atlantic Ocean.
**France offers its all stunning mountain ranges, breathtaking coastlines, and fashionable cities.**.

*****

# Directions travelling from Maryville to France
1. Book a cab from Maryville to Kansas airport
2. Finish the check-in process through online
   1. Take boarding pass from a self-service Kiosk
   2. Waiting for the flight
   3. Board your flight
3. Complete your check-out process in France

* Clothes
  * Sweater
  * Shoes
* Cosmetics
  * Lotions
* Money
* Snacks
  * Chocolates
  * Biscuits

[AboutMe](https://github.com/Prudvi97/assignment2-Gundla/blob/main/AboutMe.md)

# Table Section

Some of the best things I had in India are recommended in a table with three columns.

| FOOD/DRINK       |  LOCATION     |      COST      |
|     ---          |   ---         |     ---        |
|Spaghetti Pasta   |  Bukhara      |     $3.00      |
| Chicken Pizza    |  Domino's     |     $3.00      |
|Frappuccinos      |  Starbucks    |     $5.00      |
|Chicken wings     |  KFC          |     $4.00      |

# Authors Quotes

> "Be who you are and say what you feel, because those who mind don’t matter and those who matter don’t mind." - by
*Bernard M. Baruch* <br>
> "We must not allow other people’s limited perceptions to define us." - by
*Virginia Satir*

# Code Fencing (String Processing)
In computer programming, a string is traditionally a sequence of characters, either as a literal constant or as some kind of variable. The latter may allow its elements to be mutated and the length changed, or it may be fixed (after creation). A string is generally considered as a data type and is often implemented as an array data structure of bytes (or words) that stores a sequence of elements, typically characters, using some character encoding. String may also denote more general arrays or other sequence (or list) data types and structures.<https://en.wikipedia.org/wiki/String_(computer_science)>

```
long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}
```

<https://cp-algorithms.com/string/string-hashing.html>