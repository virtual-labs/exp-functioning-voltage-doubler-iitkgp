## Theory

The DC voltage produced by the half wave rectifier is less than the peak value of the Sine Wave. The size and ratings of the capacitors and transformers become very large if pure high voltage DC  is to be produced. Voltage Doublers are used  when higher DC voltages are needed. A typical voltagedoubler circuit due to Greinarcher is shown below:

<div>
<img  src="images/doubler.jpg" width=30% />
</div>

The capacitor C<sub>1</sub> is charged through rectifier D<sub>1</sub> to a voltage +V<sub>max</sub> with polarity as shown in the figure during the negative half cycle. During the positive half cycle as the voltage of the transformer rises to V<sub>hmax</sub>, the potential of the other terminal of C<sub>1</sub> rises to 2V<sub>hmax</sub>. The capacitor C<sub>2</sub> is in turn charged through the Rectifier D<sub>2</sub> to 2V<sub>hmax</sub>.  Depending on the time constant C<sub>2</sub>R<sub>L</sub> where R<sub>L</sub> is the Load Resistance, the output voltage will be less than 2V<sub>hmax</sub>. The rectifiers are rated to a Peak Inverse Voltage of 2V<sub>hmax</sub> and it is preferable that both C<sub>1</sub> & C<sub>2</sub> have the same rating to affect equal amount of charge transfer. The ripple content is straight away proportional to the load current.  

Ripple is Calculated using the formula <strong>I/2*f[(1/C<sub>2</sub>)+(2/C<sub>1</sub>)]