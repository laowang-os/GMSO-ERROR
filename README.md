# GMSO-ERROR
Engine Incompatibility Error
I add several informations of torsional parameters as the format of xml file, then I apply the force field to the structure, but a error appeared. 
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
