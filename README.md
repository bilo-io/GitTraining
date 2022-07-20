This is a test to figure out GitBehavior

```js
export function someFunction () {
    const returnValue = ''
    const isEvenDay = (new Date()).getDay() % 2 === 0
    if(!isEvenDay) {
        console.log('it is an odd day')
        returnValue = 'ODD_DAY';
    } else {
        console.log('it is an even day')
        returnValue = 'EVEN_DAY';
    }

    return returnValue;
}
```

Once again, just to test all of the above.