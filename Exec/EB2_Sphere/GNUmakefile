PRECISION  = DOUBLE
PROFILE    = FALSE

DEBUG      = TRUE
DEBUG      = FALSE

#COMP       = Intel

#DIM        = 1
#DIM        = 2
DIM        = 3

USE_MPI    = TRUE
USE_OMP    = FALSE

USE_EB = TRUE
USE_REACT  = TRUE

HYP_TYPE = MOL
#TINY_PROFILE = TRUE
#PROFILE = TRUE

# define the location of the PELE top directory
PELE_HOME    := ../../..

# This sets the EOS directory in $(PELE_PHYSICS_HOME)/Eos
Eos_dir     := Fuego

# This sets the network directory in $(PELE_PHYSICS_HOME)/Reactions
Reactions_dir := Fuego

# This sets the model directory in $(PELE_PHYSICS_HOME)/Support/Fuego/Mechanism/Models
Chemistry_Model = air

# This sets the transport directory in $(PELE_PHYSICS_HOME)/Transport
Transport_dir := EGLib
#Transport_dir := Constant

Bpack   := ./Make.package
Blocs   := .


include ../Make.PeleC
