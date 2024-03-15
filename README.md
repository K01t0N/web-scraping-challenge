# Assignment 11

These are the references for this assignment.

## References

### Part 1

**Code Cell 8**

Adding entries to a dictionary:

    for x in range(len(title_texts)):
        dict_list.append({'title': title_texts[x], 'preview': preview_texts[x]})

https://docs.python.org/3/library/stdtypes.html#dict


### Part 2

**Code Cell 5**

Checking if a key is in a dictionary:

    if x dict.keys():
https://stackoverflow.com/questions/1602934/check-if-a-given-key-already-exists-in-a-dictionary


Deleting a key from a dictionary:

    del dict[[key]]
https://careerkarma.com/blog/python-remove-key-from-a-dictionary/


**Code cells 12, 14, 16**

Parsing month and year from a datetime value:

    dt.year or dt.month
https://stackoverflow.com/questions/30405413/pandas-extract-year-from-datetime-dfyear-dfdate-year-is-not-working