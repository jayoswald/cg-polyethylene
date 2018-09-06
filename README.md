# Coarse-grained models for polyethylene

## all-atom:

The script in.lammps performs the all-atom simulation to generate
the trajectory sampled in the canonical ensemble. This trajectory
can further be used to compute the local structural distributions
of RDF, bond, angle and dihedral distributions shown in Figure 1.


## cg-HB:

The script in.lammps performs the CGMD simulation to ramp the
external temperature of CG-HB polyethylene melt from 480K to 40K
under constant external pressure 1atm independently on all three
directions. This simulation generates part of the raw data shown
in Figure 6(a,c).

## cg-NLB:

The script in.lammps performs the CGMD simulation to ramp the
external temperature of CG-NLB polyethylene melt from 480K to
40K under constant external pressure 1atm independently on all
three directions. This simulation generates part of the raw
data shown in Figure 6(b,c).

