# Modeling and Analysis of the Sodium Thiosulfate-Hydrogen Peroxide Reaction: A Comprehensive Study on Multiplicity, Stability, and Sensitivity Analysis
## 1) Background and rationale for analysis

The sodium thiosulfate-hydrogen peroxide reaction has been the subject of numerous studies due to its intriguing. This reaction involves the interaction between sodium thiosulfate (Na2S2O3) and hydrogen peroxide (H2O2). In this study, we investigate the reaction in a continuous stirred-tank reactor (CSTR) equipped with a cooling jacket. The cooling jacket is crucial in controlling the temperature of the reaction system, ensuring efficient heat removal, and preventing thermal instability. The CSTR consists of a well-mixed tank that receives a continuous inflow of reactants while simultaneously removing the products. The reactants, sodium thiosulfate and hydrogen peroxide, are introduced into the reactor at specified flow rates. The cooling jacket surrounding the reactor vessel facilitates heat transfer and maintains the reaction temperature within a desired range. 

![CSTR Schematic](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/6acbee4d-7e85-4654-9c6b-6915db9b06c8)


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




Many researchers have studied this reaction, but not all of them have conducted experimental data. However, Puigjaner et al. (2002) have carried out a comprehensive investigation, resulting in a highly professional piece of work.

Concentration profile

![Conc](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/c7da556f-326c-4a76-8598-cad07ea202a5)

Temperature profile

![297k](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/78c2d58a-691d-4caa-a9fb-7b610cef7996)


Parameters were used:

V = 100  # L

F =  0.1 # L/s

UA = 0.1  # J/sK

roh = 1000  # g/L

dH = 547100  # J/mol

CP = 4.2  # J/gK

ko = 685000000000  # L/(s mol)

E = 76534.704  # J/mol

R = 8.314  # J/(mol K)

Ti = 297  # K

Tj = 250  # K

Cai = 0.3 #mol/l

Cbi = 0.45

Cpi = 0

## 3) Parameter and data fitting

By carefully adjusting parameters such as the flow rate and volume, the data was effectively fitted. The paper acknowledges potential variations and time delays due to heat loss and the experimental setup. Puigjaner et al. (2002).

![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/ec069336-1a9f-4974-98c9-af653922cee6)


![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/f3c4fbd0-d52f-435e-ba78-ecd050335081)


## 4) Bifurcation analysis






![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/01b9ca1d-dc8c-4cb5-8d63-cf6c389b0df7)


at SS


![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/6047ccff-ae15-4bb8-83e2-3850a2018cf8)



![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/7e97044c-2f56-418f-80c3-0d9ac6bffb85)


![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/77e4cc33-d32c-4e9e-a89e-26b80001a8ea)



![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/f72f3e35-495e-43c9-a9e9-300cf198de0e)



![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/6ce14134-6f12-4acf-b746-dcb79d7b3687)


C. Kravaris et al. (2000)



![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/a4566fe9-6225-45e5-b54b-c17ff6a2ad5b)

![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/09cd93f4-db6e-4d87-b373-99ca8787caab)

![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/6519bc0d-65bb-41d4-ada8-5410f6d81e59)


![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/92c2762b-6675-41e6-a541-03b4ce0af3b8)

Also, the eigenvalues and eigenvectors were calculated, and it was found that the system at t = 308.25 K is not stable.

Eigenvalues: [18.17503513 -0.3947288 ]
Eigenvectors: [[0.00000000e+00 1.00000000e+00]
 [1.00000000e+00 1.88623717e-06]]


As we can see in this section, a bifurcation analysis was conducted, which aimed to investigate the dynamic behavior of a system. The results revealed the existence of three steady-state (SS) points. The first SS point was found to be stable (at t=271.43 K), indicating that the system would converge towards this point under certain conditions. The second SS point (208.25 K), however, was found to be unstable, suggesting that the system would not remain at this point and might exhibit unpredictable behavior. Finally, the third SS point (375.9 K) was identified as stable, indicating that the system would also converge towards this point under specific conditions. These findings provide valuable insights into the behavior and stability of the system studied. Vejtasa
and Schmitz, (1970), concluded to the same.

## 5) Sensitivity analysis 


![image](https://github.com/ABCO2/CHE2410-Project-2/assets/144171865/db6cd80a-9498-4805-89cc-22359ff8a0f7)



In this section, a sensitivity analysis was conducted by adjusting parameters such as flow rate, volume, reaction rate, initial temperature, and initial concentrations. From the generated plots, it can be observed that the temperature (T) of the reaction varies over time for different parameter combinations. The variations in flow rate, volume, reaction rate, initial temperature, initial concentrations, and other parameters influence the heat loss experienced by the system. It is important to note that the presence of variations and time delays caused by heat loss and the experimental setup can introduce uncertainties in the measurements.


## 6) Conclusions and implications


In summary, this study aimed to provide a comprehensive analysis of the sodium thiosulfate-hydrogen peroxide reaction. Through the development of mathematical models and the fitting of experimental data, we were able to gain a deeper understanding of the reaction dynamics. The bifurcation analysis revealed the existence of stable and unstable steady-state points, shedding light on the system's behavior and stability. Additionally, the sensitivity analysis highlighted the influence of various parameters on the reaction, emphasizing the importance of controlling these factors for accurate predictions and simulations. Overall, this study contributes to the foundational knowledge of the sodium thiosulfate-hydrogen peroxide reaction.
