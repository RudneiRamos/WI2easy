# WI2easy

WI2easy v1.0 (2025) was written by Gabriel S. Rodrigues and Rudnei O. Ramos.

WI2easy is a versatile and accessible Wolfram Mathematica package that provides a comprehensive set of numerical tools for the analysis of perturbations in warm inflation. With this package, users can analyze any type of potential and dissipation mechanism through a simple and user-friendly interface. In addition to perturbations, users can also extract and study background quantities and observational parameters in an intuitive manner.

## Features

- It determines the appropriate initial conditions for running the background differential equations.
- It evolves the full set of perturbation equations in warm inflation coupled to the background equations and find the function G(Q) in the expression for the power spectrum in warm inflation.
- It normalizes the potential according to the CMB amplitude of the scalar power spectrum and determines the Hubble-exit point.
- It computes all the background quantities as well as perturbations quantities (the power spectrum, tensor-to-scalar ratio, spectral tilt, running) for a single value for the dissipation ratio Q at the Hubble-exit point.
- It gives all background and perturbation quantities as a function of Q at Hubble-exit.
- Obtain observational quantities as a function of the dissipation ratio Q.
- It makes plots for all relevant quantities and produces the relevant data files.


## Installation and usage

After downloading the package, the simplest way to use the code is to place the WI2easy.m package file in the same working directory as your Mathematica notebook. In your working notebook, use the command  
```SetDirectory[NotebookDirectory[]];```  
to set the working directory (if the package is in the same folder, the brackets ```[]``` should remain empty), and then use  
```<< WI2easy.m```  
to load and begin using the package. If everything is working properly, you should see the message  
```This is WI2easy v1.0```  
displayed in your notebook.

The attached file ```main.nb``` contain examples with all the steps necessary to utilize the features provided by our package. These steps are also thoroughly explained in our paper where the package is introduced. As the code runs, data files are generated to allow further analyses.

## Contact

For questions and suggestions, please contact: [rudnei.ramos@gmail.com](rudnei.ramos@gmail.com).

If you use WI2easy in your research, please cite our paper:  
[WI2easy: warm inflation dynamics made easy](link to the paper).
