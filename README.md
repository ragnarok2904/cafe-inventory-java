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
Why “One” wasn’t printed: switch doesn’t start at the top and go through every case. It <ins>**jumps straight to the case**</ins> that matches the value. day is 2, so execution starts at case 2:, and case 1: is skipped entirely.

Why “Three” was printed: there’s **no break** after case 2, so execution falls through into the next case untile the last case. This is called <ins>**fall-through**</ins>. It keeps going until it hits a break or the end of the switch.
