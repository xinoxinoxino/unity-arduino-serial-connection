# Project: unity-arduino with serial connection #
This project uses Unity (which uses C# and JavaScript scripting), the Arduino (processing) and/or SerialProxy to connect the Arduino to Unity.
Thus allowing custom hardware to be linked to Unity (in real-time).

The link is established in Windows using the Mono implementation of System.IO.Ports.

For Mac/OSX users, I've made an implementation that uses SerialProxy because direct serial connection doesn't work on the mac.
The problem is, though, that the SerialProxy implementation doesn't seem to work either.

Check out the [Mac\_OSX\_problems](Mac_OSX_problems.md) Wiki for more documentation about this.

To sum it up, we have 2 kind of connections:
  * Windows/PC:
    * Arduino -> Unity.

  * Mac/OSX:
    * Arduino -> SerialProxy -> Unity. (doesn't work yet)

To get the connections working,
Use one of these guides:

English guide:
  * [English\_step\_by\_step\_guide](English_step_by_step_guide.md)

Dutch guide:
  * [Dutch\_step\_by\_step\_guide](Dutch_step_by_step_guide.md)


_Project established by: Tiuri de Jong._