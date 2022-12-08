
# WS2812_Raspberry_Pi_Pico

Controlling NeoPixels with the Raspberry Pi Pico (Python).

## Authors

- [@OnlyCircuits](https://github.com/OnlyCircuits)

## Demo

[Video Demostration](https://www.instagram.com/reel/ClVSJyOLo4a/?utm_source=ig_web_copy_link)

## Lesson

- Install Thonny 
- Acknowledgements of Python Programming and Microcontrollers
- Build the circuit on the breadboard
- Upload the code 
- Enjoy the project

## Documentation

[Raspberry Pi Pico Datasheet](https://datasheets.raspberrypi.com/pico/raspberry-pi-pico-python-sdk.pdf)

[WS2812 Datasheet](https://cdn-shop.adafruit.com/datasheets/WS2812.pdf)


## Code Notes

Set the Pin and the number of the NeoPixel

```
pixels = neopixel.NeoPixel(machine.Pin(Pin), Number_Pixels)

```
Set the colour

```
pixels.fill()

```

Enable the NeoPixel

```
pixels.write()

```

## Materials

- Breadboard
- Jumpers
- Raspberry Pi Pico
- WS2812 8 strip
## Circuit Diagram
![WS2812_Raspberry_Pi_Pico](https://user-images.githubusercontent.com/105074465/206527173-0678b333-ea4c-4118-9096-c3313e805cb0.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Support

For support, email onlycircuits321@gmail.com or join my channel.
