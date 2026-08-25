# A1 – [Topic]

## Objective


## Analyze

#Task A:  Portfolio Analysis

For the first profile I chose to analyze, I used a random number generator to pick a student from the Spring 2026 2156 portfolio archives. The number generated was 118 which corresponded to the portfolio of Cael Brokaw.

Navigability:

Reproducibility:

Evidence of Reasoning:

Professional Tone:

[Cael Brokaw's Canvas Portfolio](https://uncc.instructure.com/eportfolios/5021/home)

For the second profile I chose to analyze, I searched for Github Portfolio pages of engineering students at NC State University. The first result was for the portfolio of Jesse Mayo.

Navigability:

Reproducibility:

Evidence of Reasoning:

Professional Tone:

[Jesse Mayo's Github Portfolio](https://jsmayo.github.io/)

#Task B:  Product Analysis

Primary Function:

The primary function of this "Snail" style tape dispenser is to dispense and cut adhesive tape from an inserted roll. Mechanically, two tasks are performed:

>Rotational support and guidance. The cylindrical clip acts as both a bearing and a stopper to ensure the tape roll will rotate smoothly and not come out of alignment.

>Stress concentration for material failure. The serrated metal blade focuses pressure to create small failure points which then expand due to the triangular teeth.

Governing Model:

The main behavior involves two phases: 

Manual unrolling of the tape for length selection and the cutting with the serrated blade when force is applied downward. The governing model of the cutting phase is outlined here:

i. Model and Variables

The cutting action is governed by stress concentration and tensile failure mechanics, modeled by the tensile stress equation using a stress concentration factor at the cutting teeth:

$$\sigma_{max} = K_t \cdot \frac{F}{A}$$

\sigma_{max}: The maximum local tensile stress experienced by the tape at the cutting edge (N/m^2 or Pa).

K_t: The geometric stress concentration factor determined by the sharpness and shape of the blade's teeth (dimensionless).

F: The tensile force applied by the user to the tape (N).

A: The cross section area of the tape (A = w \cdot t, where w is tape width and t is tape thickness) (m^2).

Failure happens when sigma_{max} \ge sigma_{ut} (the maximum tensile strength of the tape).

Assumption:

One key assumption that makes this model valid is that the tape acts in a brittle or almost brittle manner during the quick tear. While adhesive tape is polymer based and viscoelastic, the sudden force against the sharp, rigid teeth minimizes plastic deformation and focuses the stress to cause tensile failure along the cross section.

Component Geometry:

Patent Info:

Patent Number: USD116599S
Inventor: Jean Otis Reinecke

## Decide


## Communicate

