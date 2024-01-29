The parallel  (s-step) CG  references:
1. A. T. Chronopoulos, A Class of Parallel Iterative Methods Implemented on Multiprocessors,  PhD. thesis,  University of Illinois, ProQuest Dissertations Publishing, 1987. 8711782. 
2. A. T. Chronopoulos, C. W. Gear, s-step iterative methods for symmetric linear systems, 
 Journal of Computational and Applied Mathematics, 25(2), 153-168, 1989.  
https://doi.org/10.1016/0377-0427(89)90045-9      
3. A. T. Chronopoulos, C. W. Gear, On the efficient implementation of preconditioned s-step conjugate gradient methods on multiprocessors  with memory hierarchy, Parallel Computing, 11(1),  37-53, 1989.  
https://doi.org/10.1016/0167-8191(89)90062-8       

Matlab Programs’ Authors: A. T. Chronopoulos and H. S. Kaveh                
 s-step CG to solve A x=b 
 
Functions called: mmread, sCGalg21vmm2s, sPrCGalg21vmm2s, pcg  
 
 Matrix Data-files from sparse matrices collection (MM-format) 
 https://www.cise.ufl.edu/research/sparse/matrices/list_by_id.html              
   mesh3e1.mtx 

The right-hand side b is created to have solution vector of all entries=1  

FORTRAN 77 program :Author:  A. T. Chronopoulos 

