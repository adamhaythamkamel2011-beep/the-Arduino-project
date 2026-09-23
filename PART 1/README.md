# The Coding Part:
##### this will be the area will you will first learn to code using: 
#### embedded c++
## first steps 
first you will see a consul like this when you first open 
#### make sure you have platform
```
#include <Arduino.h>

void setup (){

}

void loop (){

}
```
this is normal as it is in every Arduino program and is where everyone starts 

## Part Identification 
#### identification is used for every Arduino and board for identifying contents that you connect to the board.
examples: servo, motor, or led and many other uses. 

```
// vs code version

#include <arduio.h>
#include <servo.h>
```

#### this is how we identify the arduio board in vs code but in Arduinos software its not needed.
##### you will need to use the identification compounding to it to identify what pin to map it to.

# Pin Identification

#### In order for you start coding you will need to map your code to the pin you placed your components on.
##### variables:

"pinmode" function used for mapping pins pins 


```
// vs code version:
void setup() {
pinmode(12, output)
}
