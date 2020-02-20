## Random
is a utility class for generating random numbers.

Here are the sample usage:

```java
Random random = new Random();

int randomInt = random.nextInt();
double randomDouble = random.nextDouble();
long randomLong = random.nextLong();
float randomFloat = random.nextFloat();
boolean randomBoolean = random.nextBoolean();
double randomGaussian = random.nextGaussian();
```

**Seeding**
You may initialize Random object with seed to enhance randomization
```java
Random(Long value) // will create a Random object with a given seed value

/* for example */
Random random = new Random(123L); // constructor accepts any Long value
```
Without a seed value, the Random object will be seeded by a value which is a multiple of the current nanotime based on epoch time

[Back to Home](README.md)