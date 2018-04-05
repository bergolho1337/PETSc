include ${PETSC_DIR}/lib/petsc/conf/variables
include ${PETSC_DIR}/lib/petsc/conf/rules

hello: hello.o  chkopts
	-${CLINKER} -o hello hello.o ${PETSC_VEC_LIB}
	${RM} -f hello.o
