# LESS for loop with index support #

> Based on [Max Mikhailov](https://github.com/seven-phases-max) "for" LESS loop this version simply exposes the array index as the second argument in the for loop. This comes in handly in quite a few situations where you have a relation between array indexes etc.<br/>

Please note that the index is not optional and it is a required part of the ".-each()" section now.

### Example

    .for(@yourArray);
    .-each(@arrayItem, @arrayIndex) {
    }
