# General 

### Counter

    const items = ['a', 'b', 'c']
    let counter = 0

    // each time the counter should change

    counter = (counter + 1) % (items.length - 1)
