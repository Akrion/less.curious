# LESS for loop with index support #

> Exposes the array index as the second argument in the for loop.<br/>
This comes in handly in quite a few situations where you have a relation between array indexes etc.<br/>
Please note that the index is not an optional and it is a required part of the ".-each()" section.

### Example

 .for(@yourArray);
  .-each(@arrayItem, @arrayIndex) {
  }
