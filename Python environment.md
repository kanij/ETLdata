# Python Environment Setup Commands #
*To see list of environments:*
                    
                    conda env list 
*To activate a particular environment:*
                    
                    conda activate <envName>
*To create an environment:* 

                    conda create -n <envName> <PackageName>
*To remove and environment:*

                    conda remove --name envName --all
*To see list of installed packages:*

                    conda list or pip list 
*To upgrade a installed package ver.:*

                    pip install --upgrade <packagename>
*To upgrade a installed package to a certain ver.:*
                    
                    pip install --upgrade <packagename==12.3.0>                    
*To install a new package in the environment:* 
                                
                   pip install <packagename>
*To upgrade pip version to pip3 :* 
                   
                   pip install upgrade pip
*To uninstall a python package :* 
                    
                    pip uninstall <packagename> 
*To uninstall multiple pacgage :* 
                    
                    pip uninstall <packagename1> <packagename2> <packagename3>.....
*To the installed package dependencies :* 
                    
                    pip check
*To reinstall a package with ignoring warning :* 
                  
                  pip install --ignore-installed <packagename> 
*To install package with admininstration right :* 
                  
                  pip install <packagename> --user
