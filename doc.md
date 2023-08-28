# Dish class

The Dish class has two attributes and four methods.

### attributes

```
name: type string
hold the name of the dish
```

```
price: type int
hold the price of the dish
```

### methods

```
get_price: return the price of the dish
```

```
set_price: set the price of the dish, does not return anything
```

```
get_name: return the name of the dish
```

```
set_name: set the name of the dish, does not return anything
```

# Employee class

The Employee class has three attributes and six methods.

### attributes

```
hour: type int
record the number of hours the employee worked
```
name: type string
hold the name of the employee
```
wage: type int
```

### methods

```
get_hour: return the number of hours the employee worked
```

```
set_hour: set the number of hours the employee worked
```

```
get_name: return the name of the employee
```

```
set_name: set the name of the employee
```

```
get_wage: return the hourly wage of the employee
```

```
set_wage: set the hourly wage of the employee
```

# Restaurant Class

The Restaurant class has five attributes and thirteen methods.

### attributes

```
address: type string
hold the name of the restaurant
```

```
menu: type dictionary, {string:object of dish}
hold the name of the dish and the object of the dish
```

```
employees: type dictionary, {string:object of employee}
hold the name of the employee and the object of the employee
```

```
name: type string
hold the name of the restaurant
```

```
revenue: type int
hold the revenue of the restaurant
```

### methods

```
get_address: return the address of the restaurant
```

```
set_address: set the address of the restaurant
```

```
add_new_dish: add a new dish into the menu
this method takes two parameters:
name of a dish: type string
price of a dish: type int
```

```
remove_dish: remove a dish from the menu
this method takes one parameters:
name of a dish: type string
```

```
print_menu: print all dishes (with the price and name) on the menu
```

```
get_name: return the name of the restaurant
```

```
set_name: set the name of the restaurant
```

```
get_revenue: return the revenue of the restaurant
```

```
set_revenue: this method update the attribute [revenue]
this method is used by the sale method
this method takes one parameter:
amount earned: type int
```

```
sale: this method record the sale of a dish
this method calculates the income of the sale
this method takes two parameters:
quantity ordered: type int
name of a dish: type string
```

```
hire_employee: this method adds a new employee into the attribute [employees]
this method takes two parameters:
name of an employee: type string
wage of an employee: type int
```

```
retire_employee: this method removes an existing employee from the attribute [employees]
this method takes one parameter:
name of an employee: type string
```

```
list_employee: this method print all employees (with the wage and name) on the attribute [employees]
```