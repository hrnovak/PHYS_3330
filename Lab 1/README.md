## Pre-Lab Questions

### Question 6.1.1 

*What is the total resistance of two resistors in parallel that each have a resistance <b>R</b>?*

The total resistance of two resistors in parallel <b>R<sub>eff</b>, each with a resistance of <b>R</b>, is equal to one over the sum of the inverse of each resistors 

$$\frac{1}{R_{eff}} = \frac{1}{R} + \frac{1}{R}$$

so, 

$$R_{eff} = \frac{R}{2}$$



### Question 6.1.2

*Find the total resistance of the combination of resistors shown below.*

<p align="center">
  <img src="https://github.com/hrnovak/PHYS_3330/blob/main/pl1q2.jpg" height="300" />
</p>

The 75 $\mathrm{\Omega}$ resistor is in parallel with the 100 $\mathrm{\Omega}$ resistor so their equivalent resistance

$$\frac{1}{R_{eff,100,75}} = \frac{1}{75} + \frac{1}{100}$$

Therefore, 

$$R_{eff,100,75} = \frac{1}{\frac{1}{75} + \frac{1}{100}} = 42.9\mathrm{\Omega}$$

The 50 $\mathrm{\Omega}$ resistor is now in series with <b>R<sub>eff</b> of the other two resistors, so the respective resistances are added so that the total resistance <b>R<sub>T</b> is given by 

$$R_{T} = 42.9 + 50 = 92.9\mathrm{\Omega}$$



### Question 6.3.1

*Calculate the total capacitance of the combination of capacitors shown below.*

<p align="center">
  <img src="https://github.com/hrnovak/PHYS_3330/blob/main/pl1q2.jpg" height="300" />
</p>

The 75 nF and 100nF capacitors are in parallel, so their capacitances will add:

$$C_{parallel} = 75 + 100 = 175 nF$$

Now $$C_{parallel}$$ is in series with the 50 nF capacitor. Therefore, 

$$\frac{1}{C_{total}} = \frac{1}{175} + \frac{1}{50} = 0.026$$

and thus, 

$$C_{total} = \frac{1}{\frac{1}{175} + \frac{1}{50}} = 38.9 nF$$


### Question 6.4.1

#### SPICE diagram
<p align="center">
  <img src="https://github.com/hrnovak/PHYS_3330/blob/main/Lab%201/pl1q4.jpg" height="300" />
</p>



Using Ohm's law $$V = IR$$ , we can predict the current through the resistor.

The voltage across the circuit is 10 V and the total resistance is 1000 $$\mathrm{\Omega}$$.

$$10 V = I \times (1000 \mathrm{\Omega})$$

Solving for current we find, 

$$0.01 = I$$


The power dissipated due to heat is given by 

$$P = \frac{(\Delta V)^2}{R}$$

In this circuit $$\Delta V = 10$$ V and $$R = 1000\mathrm{\Omega}$$. By plugging these values into the equation above we get

$$P = \frac{10^2}{1000} = \frac{100}{1000} = 0.1 J$$



**Predicted current:** 0.01 A

**Predicted power dissipated:** 0.1 W

**Simulated current:** 10 mA or 0.01 A

**Simulated power dissipated:** 100 mW or 0.1 W

The simulation values matched the formulas' predictions!
