Install MSMPI (runtime)
    https://docs.microsoft.com/en-us/message-passing-interface/microsoft-mpi

For serial running:
    put lcode.exe in working directory with your lcode.cfg and run it with double-click

For parallel running:
    put lcode.exe in working directory with your lcode.cfg
    and run 'mpiexec -n <cpu-number> lcode.exe' in command line 
