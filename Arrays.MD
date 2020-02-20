## Arrays
is a utility class for array manipulation.

Here are the sample methods included in Arrays:

**Print an array as a String**
```java
Arrays.toString(T[] array) // prints an array

/* for example */
int[] numbers = new int[] {1, 2, 3, 4, 5};
System.out.println(Arrays.toString(numbers)); // will print [1, 2, 3, 4, 5]
```

**Array to List**
```java
Arrays.asList(Object... objects) // creates a List out of an array

/* for example */
List<Integer> integerList = Arrays.asList(0, 1, 2, 3, 4); // will result to a List of Integer 0, 1, 2, 3, 4
```

**Sort an Array**
```java
Arrays.sort(T[] array) // sorts the contents of an array

/* for example */
Integer[] numbers = new Integer[] { 21, 7, 8, 1, 3 };
Arrays.sort(numbers); // will result to 1, 3, 7, 8, 21
```

**Determine whether two arrays are equal**
```java
Arrays.equals(T[] array1, T[] array2) // compares to array whether they are equal

/* for example */
Integer[] numbers = new Integer[] { 21, 7, 8, 1, 3 };
Arrays.sort(numbers);
boolean result = Arrays.equals(numbers, new Integer[] {1, 3, 7, 8, 21}); // will result to true
```

**Binary Search**
```java
Arrays.binarySearch(T[] array, T value)

/* for example */
Integer[] numbers = new Integer[] { 21, 7, 8, 1, 3 };
Integer index = Arrays.binarySearch(numbers, 8); // will result to 2
```

**Copy Array**
```java
Arrays.copyOf(T[] array, int length) // copies an array from the start up to a particular length

/* for example */
Integer[] numbers = new Integer[] { 21, 7, 8, 1, 3 };
Integer[] copied = Arrays.copyOf(number, 3); // will result to an array of 21, 7, 8
```

**Copy Array with specified range**
```java
Arrays.copyOfRange(T[] array, int start, int end) // copies an array from a specific index to another index

/* for example */
Integer[] numbers = new Integer[] { 21, 7, 8, 1, 3 };
Integer[] copied = Arrays.copyOfRange(number, 2, 5); // will result to an array of 8, 1, 3
```

**Fill Array with a value**
```java
Arrays.fill(T[] array, T value) // fills an array with a value

/* for example */
Double[] values = new Double[10];
Arrays.fill(values, 10.0); // will change the value of each element in the array to 10.0
```

[Back to Home](README.md)