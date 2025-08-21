# GMSO-ERROR
Engine Incompatibility Error
I add several informations of torsional parameters as the format of xml file, then I apply the force field to the structure, but a error appeared. 
Here are the informations I added.
  `<Proper class1="CM" class2="CT" class3="CT" class4="CM" c0="1.3598" c1="-0.523" c2="0.8368" c3="-1.6736" c4="0.0" c5="0.0"/>`
  `<Proper class1="CT" class2="CT" class3="CM" class4="HC" c0="0.6276" c1="1.8828" c2="0.0" c3="-2.5104" c4="0.0" c5="0.0"/>`
  `<Improper class1="CM" class2="CM" class3="CT" class4="CT" c0="0.527184" c1="-6.397336" c2="-1.69452" c3="7.564672" c4="0.0" c5="0.0" />`
  `<Improper class1="CM" class2="CT" class3="CM" class4="HC" c0="-33.472" c1="0.0" c2="33.472" c3="0.0" c4="0.0" c5="0.0" />`
  `<Improper class1="CT" class2="CM" class3="HC" class4="CT" c0="125.52" c1="0.0" c2="-125.52" c3="0.0" c4="0.0" c5="0.0" />`
  `<Improper class1="CT" class2="CM" class3="HC" class4="HC" c0="125.52" c1="0.0" c2="-125.52" c3="0.0" c4="0.0" c5="0.0" />`
  `<Improper class1="CT" class2="CT" class3="CM" class4="HC" c0="125.52" c1="0.0" c2="-125.52" c3="0.0" c4="0.0" c5="0.0" />`
  `<Improper class1="CT" class2="HC" class3="HC" class4="HC" c0="761.9064" c1="7.9496" c2="-753.12" c3="-16.736" c4="0.0" c5="0.0" />`
  `<Improper class1="CT" class2="CT" class3="HC" class4="HC" c0="761.9064" c1="7.9496" c2="-753.12" c3="-16.736" c4="0.0" c5="0.0" />`
Here is the error.
EngineIncompatibilityError: Potential <ImproperType RyckaertBellemansTorsionPotential, expression: c0 + c1*cos(phi) + c2*cos(phi)**2 + c3*cos(phi)**3 + c4*cos(phi)**4 + c5*cos(phi)**5, id: 2571962832912> is not in the list of accepted_potentials [<PotentialTemplate LennardJonesPotential,
 expression: 4*epsilon*(-sigma**6/r**6 + sigma**12/r**12),
 id: 2568898209552>, <PotentialTemplate LAMMPSHarmonicBondPotential,
 expression: k*(r - r_eq)**2,
 id: 2571655861888>, <PotentialTemplate LAMMPSHarmonicAnglePotential,
 expression: k*(theta - theta_eq)**2,
 id: 2571655864128>, <PotentialTemplate PeriodicTorsionPotential,
 expression: k*(cos(n*phi - phi_eq) + 1),
 id: 2571661603488>, <PotentialTemplate HarmonicImproperPotential,
 expression: 0.5*k*(phi - phi_eq)**2,
 id: 2571661602368>, <PotentialTemplate OPLSTorsionPotential,
 expression: 0.5*k1*(cos(phi) + 1) + 0.5*k2*(1 - cos(2*phi)) + 0.5*k3*(cos(3*phi) + 1) + 0.5*k4*(1 - cos(4*phi)),
 id: 2571457961552>]
