# Code_Saturne
Massively Parallel Simulation of Complex Multi-physics in Two-phase Turbulence Combustion Chamber on Sunway New Generation Supercomputer with 10 Million Cores
%START_LATEX
We run Code\_Saturne on the new Sunway supercomputer. To verify the experiments in our paper, one need to do as follows:
\begin{enumerate}
	\item Download Code\_Saturne 4.0.3 on https://www.code-saturne.org/cms/web/.
	\item Download files from our github.
	\item Compile the Code\_Saturne on new Sunway supercomputer.
	\item Create a case from the user manual from https://www.code-saturne.org/cms/web/.
	\item Compile the files in directory \$SpMV and \$Stencil to generate a static link library libspmv.a and libstencil.a.
	\item Put the files from our directory \$SRC to the directory \$SRC in your case newly created.
	\item Verify the optimization method in the paper with mesh for two-phase turbulent combustion chamber.
\end{enumerate}
%STOP_LATEX
