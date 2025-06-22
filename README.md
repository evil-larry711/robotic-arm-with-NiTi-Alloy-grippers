# robotic-arm-with-NiTi-Alloy-grippers
This is a CAD file for a 6-Axis industrial robot commonly used in manufacturing industries. The grippers can be modeled with Nitinol alloy for it's shape memory property. I am attaching the COMSOL file for the said material with all the uniaxial loading conditions tested using Souza Auricchio model.

Typical applications of this robotic arm include welding, painting, assembly, pick and place for printed circuit boards, packaging and labeling, palletizing, product inspection, and testing; all accomplished with high endurance, speed, and precision. They can help in material handling and provide interfaces. We can model an ROS system for this arm.

The main objective of this project is to implement SMA (Shape memory alloy) for the robotic arm grippers. 
Nitinol's unusual properties are derived from a reversible solid-state phase transformation known as a martensitic transformation, between two different martensite crystal phases, requiring 69–138 MPa (10,000–20,000 psi) of mechanical stress. At high temperatures, nitinol assumes an interpenetrating simple cubic structure referred to as austenite (also known as the parent phase). At low temperatures, nitinol spontaneously transforms to a more complicated monoclinic crystal structure known as martensite (daughter phase). There are four transition temperatures associated to the austenite-to-martensite and martensite-to-austenite transformations. Starting from full austenite, martensite begins to form as the alloy is cooled to the so-called martensite start temperature, or Ms, and the temperature at which the transformation is complete is called the martensite finish temperature, or Mf. When the alloy is fully martensite and is subjected to heating, austenite starts to form at the austenite start temperature, As, and finishes at the austenite finish temperature, Af.

 The example model I created on COMSOL shows the SMA behavior under uniaxial loading. Three studies are 
performed:
 • A boundary-load sweep shows the pseudoelasticity effect at different fixed temperatures
 • A prescribed-displacement sweep shows the pseudoelasticity effect with a partial 
unloading–partial loading loop
 • The shape memory effect is portrayed after increasing the temperature
 Souza–Auricchio  model assumes that the slope of limit curves to martensite and austenite domains are equal, that is, CM = CA. In this example, the slope of limit curve equals the 
slope of martensite limit curve CM.
