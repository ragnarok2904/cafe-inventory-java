## Warmup

### Predicted:

7 5.0 -126

One 

Two

Three


### Output:

7 5.0 -126

Two

Three

#### Explanation: 
- Why “One” wasn’t printed: switch doesn’t start at the top and go through every case. It <ins>**jumps straight to the case**</ins> that matches the value. day is 2, so execution starts at case 2:, and case 1: is skipped entirely.

- Why “Three” was printed: there’s **no break** after case 2, so execution falls through into the next case untile the last case. This is called <ins>**fall-through**</ins>. It keeps going until it hits a break or the end of the switch.

## Difference: the static variable totalProducts and the instance variable name

### static variable totalProducts: 
belongs to the Product class. There is only one copy of this variable and this is shared by every object. Updates made by each object reflects for everyone. 

### instance variable name:
As the name says - it is a variable for the instance(object). It varies from object to object. So each object has its own name.

## Copy Constructor

- The Copy Constructor created a copy of an existing object and stored it as a separate object.

- Changing p2.name doesn't p1.name because these are two different object with their own instance variables name. p1 object has its own name and p2 has its own so they don't affect each other.

## Casting (int)

- Converting a double to an int is a **Narrowing Conversion**.
- int can’t hold decimals, so information may be lost.
- Java doesn't do that automatically so we need to specify explicitly to perform this.
- The decimal part is simply **chopped off**.
- Converting int to double happens automatically.