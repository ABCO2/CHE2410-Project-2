# Modeling and Analysis of the Sodium Thiosulfate-Hydrogen Peroxide Reaction: A Comprehensive Study on Multiplicity, Stability, and Sensitivity Analysis
## 1) Background and rationale for analysis

The sodium thiosulfate-hydrogen peroxide reaction has been the subject of numerous studies due to its intriguing. This reaction involves the interaction between sodium thiosulfate (Na2S2O3) and hydrogen peroxide (H2O2). In this study, we investigate the reaction in a continuous stirred-tank reactor (CSTR) equipped with a cooling jacket. The cooling jacket is crucial in controlling the temperature of the reaction system, ensuring efficient heat removal, and preventing thermal instability. The CSTR consists of a well-mixed tank that receives a continuous inflow of reactants while simultaneously removing the products. The reactants, sodium thiosulfate and hydrogen peroxide, are introduced into the reactor at specified flow rates. The cooling jacket surrounding the reactor vessel facilitates heat transfer and maintains the reaction temperature within a desired range. 

### a) About the reaction 

The hydrogen peroxide sodium thiosulfate reaction is a chemical reaction between hydrogen peroxide (H2O2) and sodium thiosulfate (Na2S2O3). It is an exothermic reaction, meaning that it releases heat energy. Overall, the hydrogen peroxide sodium thiosulfate reaction is a fascinating display of chemical transformation, often used in experiments or demonstrations due to its visually captivating nature. 


<div align="center">
    <strong><font color="red">2Na<sub>2</sub>S<sub>2</sub>O<sub>3</sub> + 4H<sub>2</sub>O<sub>2</sub> → Na<sub>2</sub>S<sub>3</sub>O<sub>6</sub> + Na<sub>2</sub>SO<sub>4</sub> + 4H<sub>2</sub>O</font></strong>
</div>

### b) Objective of the study
In this study, we aim to provide a comprehensive analysis of this reaction by investigating its multiplicity, stability, and sensitivity. By employing modeling techniques and conducting in-depth analyses, this comprehensive study will contribute to our fundamental understanding of the sodium thiosulfate-hydrogen peroxide reaction. Specifically, we focus on:

1) Develop comprehensive mathematical models that capture the dynamics of the reaction, allowing for accurate prediction and simulation of the reaction behavior under diverse conditions.
2) Fit the experimental data of the reaction to the developed mathematical models.
3) Conduct a bifurcation analysis and investigate the multiplicity of the reaction.
4) Analyze the stability of the steady-state points of the reaction.
5) Conduct sensitivity analysis to determine the influence of different parameters on the reaction and identify key factors that significantly affect the reaction.

c) The mathmatical model


dCa/dt = (F/V) * (Cai - Ca) - k * Ca * Cb

dCb/dt = (F/V) * (Cbi - Cb) - 2 * k * Ca * Cb

dCp/dt = (F/V) * (Cpi - Cp) + 0.5 * k * Ca * Cb

dT/dt = [(F/V) * (Ti - T)] - [(UA * (T - Tj)) / (V * ρ * Cp)] + [ΔH * k * Ca * Cb/ (ρ * Cp)]

k = k₀ * exp(-E / (R * T))

a is Na2S2O3

b is H2O2

p is Na2S3O6




## 2) Explanation and presentation of problem and data

## 3) Parameter and data fitting
## 4) Bifurcation analysis
## 5) Sensitivity analysis 
## 6) Conclusions and implications
