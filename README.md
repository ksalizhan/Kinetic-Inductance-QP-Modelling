# MKIDs
Here, MKID detectors based on superconducting JJs are stored (codes, literature, paper review and etc.) 
Inductance definition: Phi = L*I = B*A
Induced back emf: V = -d(Phi)/dt = -L*dI/dt
So any relation V = -dI/dt, the proportionality factor means inductance. This is a complete definition of inductance. The coil-wrapping geometric picture is just a classical depiction, but any relation of V prop to -dI/dt leads to inductance as a proportionality factor.
Reason it has a geometric factor: V = -d(Phi)/dt = -A*dB/dt = -L*dI/dt, so inductance depends on geometry. It is just hard to picturize this geometric always, especially in 2D material case where geometry is quite subtle.

0. Kinetic Inductance relation to kinetic energy of Cooper pairs: Tunable Superconducting nanoinductors
https://iopscience.iop.org/article/10.1088/0957-4484/21/44/445202/pdf
![image](https://github.com/ksalizhan/MKIDs/assets/66937199/614515e8-7cc6-48d2-b2e4-94939c60d43a)

Kinetic inductance of electrons when driven by AC-Voltage (E(t)), Drude model conductivity has an imaginary factor. For normal metals, omega*tau is small (scattering time is small), so in normal metals, kinetic inductance effect is minimal. However, in superconductors, scattering time tau = infinitely large, therefore the kinetic inductance is gigantic compared to normal electron's one.
https://en.wikipedia.org/wiki/Drude_model
![image](https://github.com/ksalizhan/MKIDs/assets/66937199/b924b7e3-ca8a-448e-9908-1a130f538f80)

"The imaginary part indicates that the current lags behind the electrical field. This happens because the electrons need roughly a time τ to accelerate in response to a change in the electrical field. Here the Drude model is applied to electrons; it can be applied both to electrons and holes; i.e., positive charge carriers in semiconductors."
2. Jiansong Gao's thesis, Caltech 2008 (Zmuidzinas group)
https://thesis.library.caltech.edu/2530/1/thesismain_0610.pdf
3. Paul Szypryt's thesis, UCSB 2017 (Benjamin Mazin group)
   https://web.physics.ucsb.edu/~bmazin/Papers/szypryt_dissertation.pdf
   Paul is now at NIST

Coupling efficiency of AC Josephson-based slot antenna:
1. Slot antenna has its own resonant frequency (with harmonic modes: hbar*omega, 2hbar*omega, 3hbar*omega,...)
2.  2.1 We engineer Rn (normal resistance of the JJ) through oxidation amount, area, and thickness --> Impedance matching for 1 specific frequency
    2.2 Josephson junction has its own oscillating frequency when driven with DC Voltage (const). f=2eV/h, I(t)=Ic sin{phi_0+(2eV/hbar)t}
     We also drive with only certain voltage to maximize the energy input (swinging, if you randomly push, energy transfer is not optimal, but if you push only at certain moments, all of the energy can be delivered to maximize the drive. Therefore, driving frequency should match the slot antenna frequency or should be integer multiple of that.


