# neural_slime_volley_py

## Partial port of otoro excellent javascript Neural Slime Volleyball app

Pygame and numpy port, or should I say inspired partial rewrite, of selected modules of
David Ha's brilliant Neural Slime Volley js application.
The original application builds a physics model of slimes
playing volley and then endows them with very simple brains
consisting of 12 inputs representing location and speed of ball
and 2 players, 3 outputs representing left, right or jump and
magical 7 hidden state neurons, with a whopping 149 real valued parameters.
Two brilliant implementation ideas make the backend unique, here a
recurrent neural network is simply implemented as a feed forward layer
with hard connection for next step, secondly, David Ha finds weights 
using neural evolution instead of RL.<br>
The results are amazing. Please see his page for details.<br>
http://blog.otoro.net/2015/03/28/neural-slime-volleyball/
This python port is <br>
   1. uncommented
   2. untested, initial sketch, so please do not expect too much.
   2. does not implement neuroevolution so it is not a learning
       ground, just a simulation, I trained a good brain in js and 
       uploaded into a long gene here :)
   3. nowhere close in elegance to otoro artistic beauty!
<br>
I am neither expert in python nor even newbie in js, simply used chrome js f12 to
study and port this. I learned a lot and I hope python will allow more guys
to appreciate and do a real good port. I am proud of some parts, e.g.
entire Feedforward RNN Brain is 16 lines of python code :)
I think that in many ways, this application is under recognized, (even though well
appreciated for its awesomeness, not many followups even by David Ha!) and 
study and adoption of the core ideas will lead to very good breakthroughs.

Ravi
12/20/2017
