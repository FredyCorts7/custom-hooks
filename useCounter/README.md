# useCounter Hook

## use example

```
    const {counter, increment, decrement, reset} = useCounter(); // default value is 0
    const {counter, increment, decrement, reset} = useCounter(5); // value is 5
```

## increment function

```
    increment(); // default factor increment is 1
    increment(5); // factor increment is 5
```

## decrement function

```
    decrement(); // default factor decrement is 1
    decrement(5); // factor decrement is 5
```

## reset function

```
    reset(); // reset value of counter to initial value
```