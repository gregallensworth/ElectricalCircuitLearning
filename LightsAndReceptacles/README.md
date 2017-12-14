# Lights and Receptacles

Bringing together some of the simpler circuits I've done so far, this one simulates a bedroom or living room, albeit on a smaller scale.

A double-gang switch box controls both a single outlet on a duplex receptacle, and a light fixture. Code requires at least light fixture or a switch-controlled receptacle, but I'm feeling generous and gave them both.

Photos 3 and 2 show the circuit in operation.
* Receptacles are always hot, except the one switch-controlled half of the duplex receptacle.
* Light works as expected.
* Double-gang switch box.

Photo 1 shows a close-up of the switch box.
* The feed cable is the top-right, a 3-wire cable.
  * Black is hot feed; white is neutral return; red is back to the switch-controlled outlet.
* The center-left cable, is also a 3-wire cable.
  * Black hot feed to the always-hot switches; white neutral return; red to the switch-controlled light fixture.

This one presented a real-world mechanical question: how to secure 4 wires in one wire nut. The hot black feed wire needs to connect to:
  * The ongoing wire to the always-hot receptacles.
  * A switch for the switch-controlled outlet.
  * A switch for the light fixture.

The wire nut is rated for it, but just wasn't holding when I screwed the switches down.

So I had to come up with a workaround.
* Incoming feed (top-right, black) connects to a wire nut, connecting it to the "ongoing" black for the always-hot receptacles.
* That same wire nut uses a jumper to a second wire nut (left-center)
* And it is this second nut which connects the red (hot) to the two switches (black). The switches then go on to their respective fixtures and receptacles (red wires).

Is this typical or atypical? Good idea or bad?

Problems with this circuit:
* The red wires connecting the switches to their respective loads, should really be tagged with black tape. So should the other end of these red wires which are "honorary black" at their consumers.
* The red jumper from wire nut to wire nut, maybe a black tag there would be wise as well?
