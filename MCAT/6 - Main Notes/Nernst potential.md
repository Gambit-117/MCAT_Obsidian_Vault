
2025-02-05 12:01

Status:

Tags: [[Neuron]]

# Nernst potential

The Nernst potential, also called the equilibrium potential, is the voltage at which there is no net movement of a specific ion across a membrane. It is determined by the concentration gradient of an ion inside and outside of the cell. It is used to determine only the equilibrium potential of an ion; the GHK equation is used to find the RMB and the permeability of multiple ions at the same time.

The equation is as follows:

$$
 E_{ion} = \frac{RT}{zF}\ln \Bigg(\frac{[ion]_{outside}}{[ion]_{inside}} \Bigg)
$$
Where *R* is the universal gas constant (8.314 J/(mol * K)), *T* is temperature in Kelvin, *z* is the charge of the ion, *F* is Faraday's constant (96,485 C/mol), and the ion concentrations consider all ions inside and outside the cell. At physiological temperature, the RT / zF simplifies to about 58.

At equilibrium, potassium has the most weight, meaning at physiological temperature we have a calculation like this:

$$ 
E_{ion} = 58\log(\frac{[K^+]_{o}}{[K^+]_{i}})
$$

At normal physiological conditions:
- K+: -90 mV (wants to leave the cell)
- Na+: +60 mV (wants to enter the cell)
- Cl- :  -65 mV (depends on neuron type)
- Ca2+: +120 mV (strongly wants to enter the cell)

	The resting membrane potential (-70 mV) is closest to the Nernst potential of K+ because K+ is the most permeable ion in neurons. This is why K+ is the dominant ion in setting resting potential.

Think of it this way:
1. K+ wants to leave the cell because of the standard concentration gradient. It can do so because of the open leak channels.
2. Negative charges being to build as positively charged K+ leaves the cell. This negative charge attracts K+ back in because opposite charges attract.
3. Equilibrium would be reached at -90 mV where the electrical force pulling K+ back in exactly cancels out the concentration force pushing it out, but the Na+ and the Cl- bring it up slightly to -70 mV

Overall, the sodium potassium ATPase pump maintains balance, since eventually the resting potential would disappear if the K+ just kept leaving the cell from leak channels.
# References

[[Voltage]]

[[Sodium potassium pump]]

[[Potassium leak channels]]