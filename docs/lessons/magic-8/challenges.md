# magic 8 challenges

Coding challenges for the magic 8 tutorial

## Before we get started

Complete the following [guided tutorial](/lessons/magic-8/activity), and your code should look like this:

```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () =>  {
    basic.clearScreen()
    let randomNumber = randint(0, 2)
    if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    } else {
        basic.showString("I DON'T KNOW")

    }
    basic.showNumber(8)

})
```


## Challenge 1

Now let's increase the number of responses the magic 8 ball can give. How about 5 responses instead? Let's change the limit of `pick random` to  4.

```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () =>  {
    basic.clearScreen()
    let randomNumber = randint(0, 4)
    if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    } else {
        basic.showString("I DON'T KNOW")

    }
    basic.showNumber(8)

})
```

## Challenge 2

Now have the magic 8 ball respond "Try again" if **randomNumber** is 3.


```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () => {
    basic.clearScreen()
    let randomNumber = randint(0, 4)
    if (randomNumber == 3) {
        basic.showString("TRY AGAIN")
    } else if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    } else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})
```

## Challenge 3

Now what about if **randomNumber** is 4? Let's have the magic 8 ball respond "Definitely!".

```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () => {
    basic.clearScreen()
    let randomNumber = randint(0, 4)
    if (randomNumber == 4) {
        basic.showString("DEFINATELY")
    } else if (randomNumber == 3) {
        basic.showString("TRY AGAIN")
    } else if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    }
    else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})
```

**Challenge 4**

Add 3 more responses so your magic 8 ball has 8 possible responses. Be creative!
Here is the guided code!

basic.clearScreen()
    random_number = randint(0, 8)
    if (random_number == 8) {
        basic.showString("YES!")
    } else if (random_number == 7) {
        basic.showString("NO!")
    } else if (random_number == 6) {
        basic.showString("It Is Certain!")
    } else if (random_number == 5) {
        basic.showString("Beats Me!")
    } else if (random_number == 4) {
        basic.showString("Its Possible")
    } else if (random_number == 3) {
        basic.showString("Absolutely Not")
    } else if (random_number == 2) {
        basic.showString("I Wouldn't Try It")
    } else if (random_number == 1) {
        basic.showString("Try To Ask Later")
    } else {
        basic.showString("I DONT KNOW")
    }
    basic.showNumber(8)
})
let random_number = 0
basic.showString("Ask A Question!")
basic.showNumber(8)

 

