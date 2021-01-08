

# Python Basics

## Strings

strings can be delimited by single or double quotation marks.

```
single_quoted_string = 'I love SG'
double_quoted_string = "I love SG"
```

You can create multi-line strings using three double quotes:
```
multi_line_string = """ I love SG.
I love food courts here.
I love always summer climate """
```

There are multiple ways to concatinate (combine) strings.
Let's say you have first_name and last_name strings. 

```
first_name="Santa"
last_name="Claus"
```
How to get "Santa Claus" together?

There are multiple ways.
1/ string addition

```
full_name= first_name + " " + last_name
```

" " in between first_name and last_name is to have a space between first name and last name.

2/string.format

```
full_name="{0} {1}".format(first_name, last_name)
```

3/f-string
A new feature in Python 3.6 is the f-string, which provides a simple ways to substitute values in to strings.

```
full_name=f"{first_name} {last_name}"

