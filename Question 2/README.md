The previous code was using a variable, j, to perform the quadratic probing. However the variable had no link to the value being hashed, and its increment is linear instead of quadratic. 
The rectification performed was making the quadratic probe function, hv2, adds the square of j to the value being hashed and then modulo by the size of hash table.
