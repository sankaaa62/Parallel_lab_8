Compill:
	mpicc ./cpi.c -o main.out

Start:
	mpirun -np 16 ./main.out
