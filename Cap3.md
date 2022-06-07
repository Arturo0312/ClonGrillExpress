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

## Schematic diagrams
While the Fritzing diagrams used images to represent the circuit, schematic
diagrams use symbols. This allows for a more compact diagram, which
makes it easier to represent complex circuits. The following diagram shows
the symbols for some of the more common electronic components in a
schematic diagram:


what a schematic diagram would look like, let's create a simple circuit that
contained a battery, resistor and LED. The Fritzing diagram for this circuit
would look like this:

![](https://www.pinterest.com.mx/pin/147774431497450320/)

In this diagram, it is easy to see what components are needed and how they
are connected; however, in more complex circuits it can be harder to see
how everything is connected. The image from the Fritzing diagram also
doesn't show the value of the components. A schematic diagram offers a
much clearer view of the circuit and if the author of the diagram chooses to,
show the values of each component. The following diagram shows the same
circuit in a schematic diagram:






## Series circuits

The following schematic diagram shows a series circuit:

The preceding diagram shows a series circuit where the current only has
one path from the source to the return. In this circuit, the load consists of
two resistors. One resistor has a value of 330 ohms and the other has a
value 220 ohms. Now let's look at several properties of a series circuit.





## Parallel and series circuits

There are two types of circuits that we can create. These are parallel and
series circuits. A series circuit is a circuit where current only has one path to
flow from the source to the return. A parallel circuit is a circuit that has
multiple paths for the current flow. It is important to understand both types
of circuits because the properties are different between them. Let's see look
at the series circuit first.





