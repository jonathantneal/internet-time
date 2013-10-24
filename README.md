# Internet Time

When my daughter turns 26, the [unix time](http://en.wikipedia.org/wiki/Unix_time) will be defunct, because it only spans from 1970 to 2038.

We should use a standard that acknowledges creation, humanity, and the internet.

We should share a timestamp to measure our past, our present, and our future.

Here is how we do it.

### Creation

The [age of the universe](http://en.wikipedia.org/wiki/Age_of_the_universe) is **13.798 billion years**.

### Humanity

The [tropical earth year](http://en.wikipedia.org/wiki/Tropical_year) is **365.242 days**.

### Internet

The [first internet log](http://en.wikipedia.org/wiki/ARPANET) occured at **10:30pm PST on October 29, 1969**.

## Together

All together, the calculated time from the birth of the universe to the first internet log is **435,422,227,622,400,000,000 milliseconds**.

```js
universeAgeInYears = 13798000000;
tropicalYear = 365.242;

hoursInDay = 24;
minutesInHour = 60;
secondsInMinute = 60;

ageAtInternetBirth = universeAgeInYears * tropicalYear * hoursInDay * minutesInHour * secondsInMinute * 1000;
```

### Ridiculous

Maybe. It is almost double (*a U.S sextillion 21-digit number*) the existing length of a unix timestamp.
