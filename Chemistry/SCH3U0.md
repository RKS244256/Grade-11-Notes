## Isotopes

**Isotopes** are atoms of the same element that have different masses due to having a different number of neutrons.

*Example: 
Carbon-12: 6 Protons, 6 Neutrons
Carbon-14 6 Protons, 8 Neutrons*

![Standard Notation | 500](Standard_Notation.png)

Isotopes have the same atomic number (Z) because they have the same amount of protons but different mass numbers (A) because they don't have the same amount of neutrons.

Isotopes have similar chemical properties because they still have the same amount of protons. They **don't** have the same physical properties because they have a different atomic mass.

### Atomic Mass

**Atomic Mass** is the weighted average mass of all naturally occurring isotopes of a specified element. Not to be confused with mass number.

#### Atomic Mass Unit (AMU)

**Atomic Mass Unit** or *AMU* is a unit used to compare the masses of atoms and uses the symbol `μ`. It's approximately equal to the mass of a single proton or neutron.
#### Calculating Atomic Mass

Elements can have many different isotopes so how do we get an average mass or atomic mass? We simply weigh the mass of every type of isotope and use a weighted average.

To calculate this, you need to know what the different isotopes' masses and abundances are.

We use a **mass spectrometer** which deflect atoms via magnetic fields inside the machine. 

Ions are deflected based on 2 things:
1) Lighter ions will deflect more whilst heavier ions will drop off quicker.
2) Ions with higher charges will be deflected more.

These 2 factors can be combined into the mass/charge ratio (m/z).

*Example:
Ion has a mass of 28 & +1 charge
28/1 = 28
Therefore, the mass/charge ratio is 28*

*Ion has a mass of 56 & +2 charge
56/2 = 28
Therefore, the mass/charge ratio is 28*

![Mass Spectrometer Diagram](Mass_Spectrometer_Diagram.png)

##### Equations

The base equation you'll probably need to remember is: 
```
atomic_mass = (isotope_mass_1*abundance_1) + (isotope_mass_2*abundance_2)...
```

You'll probably notice you the more isotopes you have, the more you'll just need to extend the equation.

This equation will essentially let you find atomic mass, abundance, and isotope masses given you know how to plug in numbers and basic algebra. If you don't, *why are you even here?*

**Note:** Make sure abundance is in decimal form (0.5). Not percentage (50%).
###### Finding Average Atomic Mass
*Example:
This requires you to know/have all isotopes' masses and relative abundance
Zirconium has 5 isotopes
Zr-90 has a mass of 90 amu & has an abundance of 51.5%
Zr-91 has a mass of 91 amu & has an abundance of 11.2%
Zr-92 has a mass of 92 amu & has an abundance of 17.1%
Zr-94 has a mass of 94 amu & has an abundance of 17.4%
Zr-96 has a mass of 96 amu & has an abundance of 2.8%*

*The equation would probably look like this:*

```
(90*0.515)+(91*0.112)+(92*0.171)+(94*0.174)+(96*0.028) = 91.3
```

*Answer has been rounded and accounting for uncertainty, if you look at your periodic table, it will be the same mass.*

###### Finding mass of a isotope

*Example:
This requires you know the other isotopes' masses and abundances as well as the atomic mass of the element
Bromine has 2 isotopes
Br-79 has a mass of 78.917 amu & an abundance of 50.69%
Br-81 has a mass of ? & has an abundance of 49.31%
Bromine's atomic mass is 79.90
We will be finding out the mass of Br-81*

*The equation will look like this:*
```
79.90 = (78.917 * 0.5069) + 0.4931m
```

*Simplify*
```
79.90 = 40.0030273 + 0.4931m
```

*Rearrange*
```
79.90 - 40.0030273 = 0.4931m
```

*Solve*
```
m = 80.91 amu
```

*Therefore, Br-81's mass is 80.91 amu*
###### Finding Relative Abundances

*Example:
This requires you know all isotope masses and element atomic mass
Ga-69 has a mass of 68.926
Ga-71 has a mass of 70.925
Gallium has an atomic mass of 69.72
Instead of having 2 unknown variables, let's try to have 1.*
```
69.72 = 68.926x + 70.925(1-x)
```
*Because relative abundance is a percentage, it's out of 100 or 1 if in decimal. Therefore, if we have 2 isotopes, we can simply have one variable and the other unknown be 1-x*

*Distribute*
```
69.72 = 68.926x + 70.925 - 70.925x
```

*Rearrange & Simplify*
```
-1.20500 = -1.99900x
```

*Solve*
```
x = 0.603 = 60.3%
```

*Now we can solve for the other by subtracting x from 1*
```
1 - 0.603 = 39.7%
```

*We now know the relative abundances and can present an answer:*
```
Ga-69: 60.3%
Ga-71: 39.7%
```

### Quick History Lesson - Marie Curie

Marie and Pierre Curie discovered and isolated radium and polonium in the early 1900's. We all now know those elements give off radiation. As radiation was released, atoms of the element were turned into atoms of different elements (this keeps up until non-radioactive elements are formed.) Marie Curie died due to aplastic pernicious anaemia caused by her research.

*Example:
Polonium Alpha Decay
Po-218 -> Pb-214 + He-4*

### Radioisotopes

Not all elements are stable. Radioisotopes decay and emit radiation (those being alpha and beta particles and gamma rays) due to nuclear changes. This obviously makes them radioactive.

#### Half-life

Half-life is a unique characteristic of radioisotopes. It's the time it takes for one half the nuclei in a radioactive sample to decay.

*Example
Carbon-14's half life is 5730 years (a.)*

#### Types of Decay

*Alpha decay* - Low energy radiation which can simply be stopped by paper or cloth.

*Beta decay* - Radiation which releases an election and can be stopped by aluminum foil or skin.

*Gamma decay* - Radiation which can mutate DNA and is just energy. It can penetrate skin and cells. (Very bad stuff)

