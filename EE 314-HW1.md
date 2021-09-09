# EE 314 HW 1
## Haadi Majeed
### 30/8/2021
1. Research and find what SI Units are
   1. What is the SI Unit, provide a brief History and information of what it is
      1. The basis of SI rests on the 7 constant values of 
         1. c:&nbsp;&nbsp;&nbsp;Speed of light in a vacuum
         2. h:&nbsp;&nbsp;&nbsp;Planck Constant
         3. e:&nbsp;&nbsp;&nbsp;Elementary charge
         4. ΔV:&nbsp;Transition frequency of cesium-133
         5. l:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Boltzmann Constant
         6. N:&nbsp;&nbsp;&nbsp;Avogadro Constant
         7. K:&nbsp;&nbsp;&nbsp;&nbsp;Luminous efficacy
      2. The system (otherwise known as metric) was signed as the international standard for measurement on May 20th, 1875 by several countries including the US. The 7 base units (metres, seconds, mole, amphere, kelvin, candela, and kilogram) define 22 other units that can be derived from them.
   <br><br>
   2. How are they defined for each case?
      1. Metre
         * Defined by taking speed of light in a vacuum when expressed in m/s where second is ΔV
      2. Kilogram
         * Defined by Planck's constant when in units of J s which is equal to kg m^2/s where M and S are in terms of C and ΔV
      3. Second
         * Defubed by vakye if cesuium 133 frequency ΔV in Hz which is 1/s 
      4. Amphere
         * Defined by e which is equal to A s where s is ΔV
      5. Kelvin
         * Defined by Boltzmann Constant (k) whic his equal to kg m^2 s^-2 K^-1 where K, m, and s are in terms of h, c, and ΔV
      6. Mole
         * Defined by Avogadro's Number (N)
      7. Candela
         * Defined by the fixed value of the Luminious Efficacy of monochromatic radation of the frequenct 540x10^12Hz which is equal to cd sr kg^-1 m^-2 s^3, where k, m, and s are in terms of h, c, and ΔV
   <br><br>
   1. What are the units of the following
      1. Electric Charge: Q
         * Columb -> Ampheres per Second 
      2. Electric Field Intensity:  E
         *  Volts per Metre
      3. Electric Flux Density:     D
         *  Volt Metres
      4. Magnetic Field Intensity:  H
         *  Amphere per Metre
      5. Magnetic Flux Density:     B
         *  Kilograms/(Seconds^2 * Amphere)w
      6. Electric Potential:        V
         *  Kilograms * Metres^2 / (Seconds^3 * Amphere)
      7. Electric Current:          I
         * Amphere
  
    <br>
2. Use Lorentz force equation and identify how the units for E and B are related to Newton (the SI unit of force.) 
   - Units
     - E -> Volts / Meter 
     - B -> Kilograms / (Seconds^2 * Amphere)
   - Lorentz Equation
     - F = qE + qv x B
   - This equation explains how force is applied to a charged particle (q) as it moves through and Electric Field (E) and Magnetic Field (B). With this equation linking the two, we can next apply the value of q to both of them and the velocity to then determine the force (in newtons) that is exerted onto the system. E shows that there is a Newtons over time, while B shows that there is a Newtons over space as the units (once converted) go to N/C for E and N/(A*m) for B
<br><br>
1. We know that wavelength in meters x frequency in Hz equals speed in m/s
   1. Show this with unit analysis
      * The frequency of a wave is equal to 1/seconds (or the inverse of the period) and wavelength is the distance is the distance from peak to peak on a wave. The frequency is how many oscillations occur within a second and the period is the time it takes for one oscilation in seconds. With all of this we can forme: 
        *  m * 1/s = m/s
      * This is a scalar quantity, not a vector (no direction is implied//assigned) 
   2. Find the wavelengths for red and blue in the visible spectrum, which one has the shorter wavelength
      * Red-  650 nm
      * Blue- 450 nm
      * Blue has a shorter wavelength
   3. what about the lower frequencies? Which one has more energy?
      * Red- 4.62*10^14 Hz
      * Blue- 6.66*10^14 Hz
      * Blue has more energy than red light
   4. Repeat this for infrared and ultraviolet
      * Ultraviolet
        * 100-400nm Wavelength
        * 750THz - 30PHz Frequency
      * Infrared
        * 760-780nm - 1mm Wavelength
        * 300GHz - 430 THz Frequency
      * UV has more energy
   <br><br>
2. Research to find out and learn what an electromagnetic bomb is. Does it exist? What is it? How does it work? Reflect.<br>  
   According to [Air University](https://www.airuniversity.af.edu/Portals/10/ASPJ/journals/Chronicles/apjemp.pdf), an eletromagnetic bomb, or an E-Bomb, creates an electromagnetic shockwave over a very large area with the objective of disabling or inhibiting electronics. It works by sending out short but frequent electromagnetic pulses. As [How Stuff Works](https://science.howstuffworks.com/e-bomb.htm) explains it, the device is less of a bomb and more of a massive microwave that acts more as a beam than a bomb, however they explore the idea of a more bomb-like version:
   > Using an armature surronded by a coil of wire, filled with explosives, and surronded by a sturdy shell along with many capacitors, a bomb version could be created
   
   This could easily be launched, dropped, or remotely detonated and construction is fairly rudamentary which is a scary thought
   <br><br>
3. Read chapter 1 of the book.
   1. Summary
      - Many electronics interct with EM Fields and and high frequencies therefore understanding how and what interactions occur, and the why behind it is important, especially as things are becomming more and more sensitive to them. 
      - Analog Signals are continious and vary. They use set bandwidths 
      - Digital Signals are binary, such as 5V = 1 or 0V = 0
      - Microwave level frequencies are difficult to workwith due to how small the wavelength is
   2. List Major Definitions
      - Frequency- number of oscillations per second
      - Wavelength- distance between peaks of a wave
      - Time Period- time between peaks of a wave
      - Photon Energy- The minimum energy that can be transfered at this frequency
      - Electrical Length- Unitless, refers to length of device or wire at specific freqencies 
   3. What did you learn and find interesting?
      - Gamma Radiation needs 40km of copper sheets to be stopped and thats kinda scary
      - 10^12 Hz circuits exist and is very feasible to be in computers in the near future