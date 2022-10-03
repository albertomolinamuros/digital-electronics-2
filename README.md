# digital-electronics-2
## H2
### H3
#### H4
##### H5
###### H6

1. First list item
   - First nested list item
     - Second nested list item
     
[This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

# Lab 1: Alberto Molina Muros

### Morse code

1. Listing of C code which repeats one "dot" and one "comma" (BTW, in Morse code it is letter `A`) on a LED. Always use syntax highlighting, meaningful comments, and follow C guidelines:

```c
/* Defines -----------------------------------------------------------*/
#define LED_GREEN PB5   // PB5 is AVR pin where green on-board LED is connected
#define SHORT_DELAY 250 // Delay in milliseconds
#define LONG_DELAY 950
#ifndef F_CPU
# define F_CPU 16000000 // CPU frequency in Hz required for delay funcs
#endif

/* Includes ----------------------------------------------------------*/
#include <avr/io.h>     // AVR device-specific IO definitions
#include <util/delay.h> // Functions for busy-wait delay loops

int main(void)
{
    // Set pin where on-board LED is connected as output
    pinMode(LED_GREEN, OUTPUT);
     // Local variable to keep LED status
    // Infinite loop
    while (1)
    {
        // Generate a lettre `A` Morse code
    
        // WRITE YOUR CODE HERE
        digitalWrite(LED_GREEN, HIGH);
        _delay_ms(SHORT_DELAY);
        digitalWrite(LED_GREEN, LOW);
        _delay_ms(SHORT_DELAY);
        digitalWrite(LED_GREEN, HIGH);
        _delay_ms(lONG_DELAY);
        digitalWrite(LED_GREEN, LOW);
        _delay_ms(SHORT_DELAY);
    }

    // Will never reach this
    return 0;
}
```

2. Scheme of Morse code application, i.e. connection of AVR device, LED, resistor, and supply voltage. The image can be drawn on a computer or by hand. Always name all components and their values!

   ![your figure]()

![photo](https://user-images.githubusercontent.com/114478568/193682667-b5341765-a283-460d-9439-bf091080c1ed.png)
