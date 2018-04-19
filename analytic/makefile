FC=gfortran
FCFLAGS=
ROT=../field/rota ../field/didq ../field/coriolis
PES=../field/quadratic ../field/cubic ../field/quartic ../field/quintic ../field/sextic

$(info ***Compiling... This may take a while...***)

y: y.f90 $(ROT) $(PES) 
	$(FC) $(FCFLAGS) -o y y.f90 
