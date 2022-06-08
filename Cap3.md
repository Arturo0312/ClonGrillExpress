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

![](https://www.mouser.hn/blog/Portals/11/MikeParksPhotos/Screen%20Shot%202014-04-08%20at%209.33.35%20AM.png)

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





## Parallel circuits
The following schematic diagram shows a parallel circuit:

![](https://t.pimg.jp/022/313/726/1/22313726.jpg)

The preceding diagram shows a parallel circuit where the current has multiple paths to the
return. The current can either flow through the branch with the 220-ohm resistor, the
branch with the 330-ohm resistor or both branches.

In this sample circuit, as with the series circuit, the load consists of two resistors with values
of 330 ohms and 220 ohms, however, this time the resistors are connected in parallel rather
than series. The properties of a parallel circuit are very different than the properties of a
series circuit. Let's look at these properties.

## Resistance

The total resistance of a parallel circuit will always be less than the total resistance of any
branch within the circuit and adding additional branches will always decrease the total
resistance of the circuit.

To calculate the total resistance of a parallel circuit, take the sum of the reciprocal of the
resistance for each component in the circuit and that equals the reciprocal of the total
resistance. Sounds confusing? It really isn't. Here is the formula:

![](https://unicrom.com/wp-content/uploads/resistencias-en-paralelo.png).

This formula will go out to however many resistance values are needed. In the example
circuit, there are two resistors with values to 220 ohms and 330 ohms. Therefore, to
calculate the resistance of the circuit we would take the reciprocal of 1/220 + 1/330, which
would equal 132 ohms.

Rather than trying to calculate the resistance of a parallel circuit by hand, there are plenty
of online calculators that you can use.

## Voltage
Each branch of a parallel circuit will have the same voltage. If we measured the voltage
across either branch of the sample circuit it would show a voltage of 9 volts.

## Current
In a parallel circuit, current will be different in each branch. The total current of the circuit
(the current coming out of the power source) will be equal to the sum of the current in each
branch. This means that current coming out of the power source will equal the sum of the
current running through the 220-ohm resistor branch and the 330-ohm resistor branch.

Let's look at this with Ohm's law to see how this works. To calculate current with Ohm's
law we use the formula I=V/R, which means the current equals the voltage divided by the
resistance. Earlier, in the resistance section, we calculated that the resistance in the circuit
was 132 ohms and we know that the voltage is 9 volts, therefore, the total current will equal
9 volts/132 ohms or 0.0682 amps (68.2 milliamps).

We can also use Ohm's law to calculate the current in each branch knowing that the voltage
for each branch will be the same 9 volts. The current in the branch that contains the 220-
ohm resistor would be 9 volts/220 ohms or 0.0409 amps (40.9 milliamps). The current in the
branch with the 330-ohm resistor would be 9 volts/330 ohms or 0.0273 amps (27.3
milliamps).

We can now add the current from the branch that contains the 220-ohm resistor to the
current from the branch that contains the 330-ohm resistor to get the total current of 40.9
milliamps + 27.3 milliamps, which equals the same 68.2 milliamps coming out of the power
source.

Now that we understand the difference between parallel and series circuits, there is one
more concept we need to understand before we can get started building things. This
concept is a voltage drop.

## Series circuits
The following schematic diagram shows a series circuit:

![Link](https://github.com/Saul-Sanchez-de-la-Fuente/aaaa/blob/main/Series%20circuits/img/img1.png)

The preceding diagram shows a series circuit where the current only has
one path from the source to the return. In this circuit, the load consists of
two resistors. One resistor has a value of 330 ohms and the other has a
value 220 ohms. Now let's look at several properties of a series circuit.


## Resistance

The total resistance of a series circuit is the sum of the resistance of each
component of the load. In the example circuit, the load consists of two
resistors with values of 220 ohms and 330 ohms. If we add these two values
together we get a total resistance of 550 ohms.


## Voltage
The total voltage of a series circuit is the sum of the voltage of each power
source connected in series. In the example circuit, there is only one power
source, which is a 9V battery, therefore, the total voltage is 9 volts. If we
used 4 AA batteries (1.5 volts each) in series, rather than the 9-volt battery,
we would have a total voltage of 6 volts because 1.5V + 1.5V + 1.5V +
1.5V would equal 6 volts.


## Current
In a series circuit, the same current flows through each part of the circuit.
This means that we can measure the current at any point within the circuit
and it will be the same as any other point in the circuit.
In the example circuit, we know the total voltage (9 volts) and we know the
total resistance (550 ohms) therefore we can calculate the current of the
circuit using Ohm's law, where I=V/R. This formula would give us a current
of 9 volts/550 ohms or 0.0164 amps (16.4 milliamps).

## Voltage drop

Voltage drop is defined as the amount of voltage lost through each component in the circuit
due to impedance. Impedance is the amount of opposition that the circuit and component
present to the current flow. We will see why voltage drop is important in the next section
where we light up a LED.





