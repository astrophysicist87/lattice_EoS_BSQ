#BASEJNHDIRECTORY=/projects/jnorhos
BASEJNHDIRECTORY=/projects/illinois/eng/physics/jnorhos
FLAGS_NEEDED_FOR_GCC_10_3_0 = -fcommon

EoS_BQS:
	#gcc -o EoS_BQS *.c -lm
	#h5cc $(FLAGS_NEEDED_FOR_GCC_10_3_0) -o EoS_BQS *.c -I${BASEJNHDIRECTORY}/local/include -L${BASEJNHDIRECTORY}/local/lib -lm -lgsl -lgslcblas -lblas
	h5cc $(FLAGS_NEEDED_FOR_GCC_10_3_0) -o EoS_BQS *.c -lgsl -lgslcblas -lm

install:
	cp EoS_BQS ../
	
clean:
	rm -f EoS_BQS *.o
