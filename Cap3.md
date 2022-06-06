# Circuit Diagrams
## What is a circuit?

A circuit is a circular path in which electrical current flows. The point where the electrons enter the
circuit, and the current starts, is called the **source**. The point where the
electrons exit the circuit is called the **return**. Everything between the source
and the return, the components and wires that make up the remainder of the
circuit, is called the **load**.

In a closed circuit, the current has a complete path from the source to the
return allowing the current to flow through the circuit. The following
diagram shows a closed circuit where a switch is closed allowing the current
to flow through the circuit. In this circuit, we are powering a light bulb. This
makes the light bulb the load:

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUYK9PwhNB1PufaZkRff386_5vcjichjESwA&usqp=CAU)

An open circuit is one that has a break in the circuit that prevents the current
flow. The following diagram shows an open circuit where the switch is open,
thereby preventing the current flow:

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUYK9PwhNB1PufaZkRff386_5vcjichjESwA&usqp=CAU)

The last two examples show how a typical light switch works in your house.
When you turn the switch on, the circuit is closed, which turns the light on;
however, when you turn the switch off, the circuit is open, which turns the
light off.

If you set your multimeter to continuity mode and touch the two leads
together the meter will emit a tone. This tone lets you know that you have a
closed circuit. To test if your circuit is closed or open, put the multimeter
into continuity mode and place the two leads from the multimeter at different
points in your circuit, and if there is a connection between the two points the
meter will emit the tone.

![](http://i.imgur.com/GgKKjYC.jpg)

**The most dangerous circuit is a short circuit. A short circuit is one that
allows the current to flow through the circuit with little to no resistance. This
is usually a circuit with no load.**

## Fritzing

Fritzing is an open-source initiative to develop software to design electronic
hardware. This software is designed in the same spirit as the Arduino where
it abstracts away the complexity of diagramming the circuit, so the user can
focus on the design itself.

A Fritzing sketch is a
project within the Fritzing application that represents the circuit being
created. These projects can contain both circuit diagrams and code if the
project includes a microcontroller like the Arduino.

## Fritzing diagrams

A Fritzing diagram is a picture representation of what the circuit should
look like, similar to the open, closed and short circuit diagrams previously
shown in this chapter; however, the Fritzing diagram has standard symbols
to represent each part and a compact design making it easier to design more
complex circuits.

![](https://static.packt-cdn.com/products/9781788830584/graphics/assets/6b735ddb-6ffe-4c2e-a65a-742444130543.png)

The circuit in this diagram starts with the Arduino GND pin, which is
connected to the top rail of the breadboard. The cathode connector of the
LED is also connected to the top rail, which connects it to the common
ground from the Arduino. The anode connector of the LED is connected to
a 220 Ohm resistor, which is connected to the digital 12 pin of the Arduino.
This is a pretty easy diagram to understand because the diagrams look like
the components themselves.




