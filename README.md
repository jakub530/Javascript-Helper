# Javascript-Helper

## Maths and Types

### String to Int

```
const my_int = parseInt(my_string);
```

### Exponentiation 

```
const exponent = base ** power
```

## Arrays

### Add value to array

```
array.push(value);
```

### Check if array has duplicates

```
if ((new Set(array)).size !== array.length)
{
    const duplicates = true;
}
```

### Transpose an 2-D array

```
const transpose =  array[0].map((col, i) => array.map(row => row[i]));
```


### Find a section of an 2-D array (from s_x to e_x inclusive, from s_y to e_y inclusive)
```
const section = array.slice(s_x,e_x+1).map(i => i.slice(s_y, e_y+1));
```

### Filter out values from the array

``` 
const filtered_array = array.filter(elem => elem != ".");
```

### Flatten the 2-D array

```
const flat_array = array.flat()
```

## Maps

### Create a map

```
const map = new Map();
```

### Set value

```
map.set(key,val);
```

### Get value

```
const val = map.get(key);
```


## Sets

### Creating set

```
const mySet = new Set()
```

### Adding value to the set

```
mySet.add(1)
```

### Checking if value is in set

```
mySet.has(1)
```





## Strings

### Iterate over all lower case letters in alphabet

```
for(let n=0;n<26;n++)
{
    var chr = String.fromCharCode(97 + n);
} 
```


## Callbacks


## ES6





