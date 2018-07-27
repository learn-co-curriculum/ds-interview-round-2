
# Jupyter notebooks

You can type text or code! These blocks execute things.


```python
# Press SHIFT + ENTER to run this cell!

print("It Worked!")
```

## Introduction to data structures

We want to figure out where we want to go for dinner tonight. And we are craving hamburgers :).

This leads us to a first data structure: a string

In the cell below, create and print a string called `"mcdonalds"`


```python
restaurant_1 = 
print(restaurant)
```

Use the `capitalize()` method to capitalize the contents of our `restaurant` variable.  Print the variable again to see our changes!


```python
restaurant_1 = 
print(restaurant)
```

### 1. Lists

We want to collect our data. A list is an ordered collection. You can use square brackets to create a list. You can use
- the original strings
- the stored variables


```python
restaurant_2 = 
restaurants = 
same_restaurants = 
```

Note that these two are exactly the same! You can test for this:


```python
restaurants == same_restaurants
```

What if we want to access information inside `restaurants` or `same_restaurants`?

What if you want to add a burger restaurant to your list? Append `'Shake Shack'` to `restaurants`


```python
# Append "Shake Shack" to restaurants!

print(restaurants)
```

### 2. Dictionaries

Maybe we want to save attributes for our restaurants? Lists are not very useful here.


```python
mcdonalds = {'name':'mcdonalds', 'address': "85 broad street"}
```

Why not a list? Dictionaries have `keys` and `values`. 


```python
mcdonalds.keys()
```


```python
mcdonalds.values()
```

You can wrap this into a list


```python
list(mcdonalds.values())
```

Create two more restaurant dictionaries for the following restaurants:

|  Restaurant |    Address    |
|:-----------:|:-------------:|
| Burger King | 1313 Broadway |
| Shake Shack |   691 8th Ave |

Now use the correct key to access the address for Shake Shack:

Now, we'll set up for the final programming challenge of this lesson.  

First, create a list containing the restaurant dictionaries we made above.


```python
list_of_dictionaries = 
```

### Challenge

In the cell below, iterate through our list of dictionaries, and print out "{Restuarant Name} is located at {Resturant Address}!" for each restaurant. 

Your output should be:

`"mcdonalds is located at 85 broad street!"`   
`"Burger King is located at 1313 broadway!"`   
`"Shake Shack is located at 691 8th Ave!"`   
