
                                                                                              
  When using this tool, please cite: 
  
  J. R. M. Monteiro and Henrique Pecinatto. (2022). joziano/tools-for-quantum-espresso-pdos (v1.0). Zenodo. https://doi.org/10.5281/zenodo.5976058
                                                                                                                                                    
  1) The pdos-sum.sh program is an auxiliary tool for sumpdos.x from the                      
     open-source Quantum ESPRESSO suite for quantum simulation of materials;                  
                                                                                              
                                                                                              
  2) The current version does not treat spin-orbit interaction. Further implementation is     
     under development;                                                                       
                                                                                              
                                                                                              
  3) pdos-sum.sh must be executed inside the folder where the output files of the PDOS        
     calculation are present;                                                                 
                                                                                              
                                                                                              
  4) As a precaution, the program performs a backup of the original data before executing     
     the sum;                                                                                 
                                                                                              
                                                                                              
  5) The syntax for running the program is: bash pdos-sum.sh                                  
                                                                                              
                                                                                              
  6) At the end of the execution, two folders will be generated, namely:                                                                                                                    
     a) original_data                                                                         
     b) plot_data                                                                             
                                                                                              
       The plot_data folder contains all files of interest to plot the graphs.                
       The meaning of nomenclatures are the following:                                        
                                                                                              
       x) X_orb_k.dat, with k=s,p,d,f : Contribution of the k orbitals from X atom;           
       y) k_orb.dat, with k=s,p,d,f : Contribution of the k orbitals from all atoms;          
       z) X.dat: Contribuition of all orbitals from X atom                                    
                                                                                              
                                                                                              
  hope we have helped,                                                                        
  Joziano Rony de Miranda Monteiro | joziano@protonmail.com                                   
  Henrique Pecinatto | pecinatto@ufam.edu.br                                                  
  Manaus, Amazonas, Brasil.                                                                   

