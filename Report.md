Name: Jason Math

EID: jm89538

Team Number: F4

## Questions

1. Why does your program need a setup and a loop?

    Setup is needed to initialize the program and set any initial values. The loops is needed to run repeatedly and change and respond to inputs.

2. What is the downside to putting all your code in a loop?

    Code readability is reduced and harder to debug when not modularized into functions.

3. Why does your code need to be compiled?

    To translate a high level language into machine code.

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    When lowering the frequency, the human eye is able to notice the light turning on and off. In the real word, dimmers operate at a high enough frequency that the oscillation between on and off is unnoticable.

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    The logic analyzer needs a reference voltage to compare its other input data with.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous is used everything operates at the same speed and controlled by a clock. Asynchrous is used for devices that operate at different speeds and controlled by an external interrupt "ready" signal to know when there is data to be read.

7. Profile of UART: Sent X bytes in Y time 

    Sent 20 bytes in 1.724ms

8. Profile of SPI: Sent X bytes in Y time

    Sent 9 bytes in .233 ms

9. Why is SPI so much faster than UART?

    SPI has no start/stop bits, unlike UART, meaning data can be transmitted continuously

10. list one pro and one con of UART

    Pro: Parity bit for error checking. Con: Low speed.

11. list one pro and one con of SPI

    Pro: No start and stop bits for higher speed. Con: No form of error checking.

12. list one pro and one con of I2C

    Pro: Low pin/signal count even with numerous devices on bus. Con: Requires more space due to resistors.

13. Why does I2C need external resistors to work?

    To restore the signal to high when the bus is idle.

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](img/timed_blink.png)

Procedure A, step 4:
![Put path to your image here ->](img/dimmer_img.png)

Procedure B, UART:
![Put path to your image here ->](img/uart_message.png)

Procedure B, SPI:
![Put path to your image here ->](img/spi_message.png)
