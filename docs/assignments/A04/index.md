# A4 – Motor Mount

## Objective

For this assignment the objective is to design a motor mount for a Brushed 24V DC Gear Motor 3.6Kg*cm/46RPM w/ 99.5:1 Planetary Gearbox, using symbolic followed by numerical calculations in the design which can then be applied in 3D modeling software for a parametrically designed model.

The motor mount consists of two necessary features:

Feature 1 – The Motor Support: designed to attach to the motor face while allowing access to the motor shaft.

Feature 2 – The Wall Mount: designed to allow attachment of the motor mount to a rigid surface.

Both features are to be designed to minimize deflection and stress while satisfying the required constraints.

<img src="figure1.png" alt="Figure 1" width="250">

## Analyze

Design Requirements:

Load P = 300 N.

Motor Weight = impact assumed to be negligible.

Safter Factor SF = 3.

Maximum Deflection = 0.30 mm.

Material(Choose) = ABS, PETG, or PLA.


Motor Dimensions:

<img src="MotorDimensions.png" alt="Motor Dimensions" width="600">

Motor Diameter = 27.7 mm.

Motor Face Mounting Holes = four M3 holes centered 11 mm away from shaft center at every 90 degrees.

Motor Length = 74.6 mm (excl. Shaft and centering lip)


Material Properties:

Selected Material = ABS

Yield Strength = 29.6 - 48 MPa, 29.6 selected for Calculations.

Youngs Modulus = 1.79 - 3.2 GPa, 1.79 selected for Calculations.

# Feature 1 – Motor Support

Given Variables

<img src="Feature1Knowns.png" alt="Givens" width="600">

Unknown Variables

<img src="Feature1Unknowns.png" alt="Find" width="600">

Assumptions

Free-Body Diagram / Sketch1

<img src="Feature1Sketch.png" alt="Sketch 1" width="600">

Calculations

<img src="Feature1Calculation.png" alt="Calculations" width="600">


# Feature 2 – Wall Mount

Given Variables

<img src="Feature2Knowns.png" alt="Givens 2" width="600">

Unknown Variables

<img src="Feature2Unknowns.png" alt="Find 2" width="600">

Assumptions

Free-Body Diagram / Sketch1

<img src="Feature2Sketch.png" alt="Sketch 2" width="600">

Calculations

<img src="Feature2Calculation.png" alt="Calculations 2" width="600">

# Sketch

<img src="IsometricSketchA4.png" alt="Isometric Sketch" width="600">

# Cad Model

After having completed the design calculations I began to design the motor mount in solid works, beginning with the parametric equations and needed variables. Once all necessary values were input, I created a sketch for Feature 1 with length and width equal to their corresponding variables.

<img src="ParametricEquationsA4.png" alt="CAD Equations and Variables" width="600">

<img src="CadSketch1A4.png" alt="CAD Sketch" width="600">

I then turned this sketch into an extruded feature and set the thickness equal to the parametric equation i set up in the equations section.

<img src="Feature1ExtrudeA4.png" alt="CAD Extrude 1" width="600">

With the main dimensions of feature 1 complete i could move on to feature 2, which follows the same basic steps.

Sketch the feature with defined parametric variables.

<img src="CadSketch2A4.png" alt="CAD Sketch 2" width="600">

Extrude the shape with defined parametric equation.

<img src="Feature2ExtrudeA4.png" alt="CAD Extrude 2" width="600">

With The basic Geometry done I could then add additional features.

Motor Shaft Hole

<img src="MotorShaftHole.png" alt="Motor Shaft Hole" width="600">

Motor Face Mounting Holes

<img src="MotorFaceHoles.png" alt="Motor Face Mounting Holes" width="600">

Motor Outer Diameter Ridge for Further Allignment.

<img src="MotorOuterRidge.png" alt="Outer Diameter Ridge" width="600">

Wall Mounting Holes

<img src="WallMountHoles.png" alt="Wall Mounting Holes" width="600">

## Decide


## Communicate

