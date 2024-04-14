**Our Problem**

Low Efficiency of current commerical solar cells - commerical maximum is usually 15-30%. The energies of light that most conventinal materials (e.g. silicon) can absorb does not match the energy of the solar radiation that falls upon it.

It is classically difficult - as you'll soon see - to calculate ground state + excited states for larger molecules. 

VQE is a combination of classical and quantum algorithms so that it is extremely accurate, and takes much less time when compared to a pure classical algorithm.

We set out to explore if we can we simulate more complex compounds and predict what wavelengths of solar radiation they can use?

**Our Solution** 

1) Build the atoms
2) Freeze the electrons
3) Use VQE to determine ground state, and deflation for higher excited states
4) Calculate energy deltas
5) Compare!!!

In order to build the atoms, we needed to determine bond length, which we sourced from scientific papers. We used our knowledge of chemistry in order to determine which orbitals were frozen.

**Results** 

For the purposes of the hackathon, we were implementing everything using quantum computer simulations on Sandbox. Take a look at the jupyter notebooks. Of these different molecules (that have uses in solar cells) we were only able to achieve information for Li2.

**Next Steps** 

Implement our code on a quantum computer (instead of the simulations that Sandbox uses), and see if we can get more excited states!
Applications: protein, drug, enzyme simulations
