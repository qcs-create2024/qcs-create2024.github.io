#Propagation and dispersion of waves in geophysical contexts

CREATE QCS module by Prof. David Straub (McGill University) with contributions from CREATE graduate students Akash Dutta and Meixin Zhou.

The module includes two pdfs worth of notes and exposition---one introducing wave kinematics in general, and the other developing the matter further 
in the context of the shallow water equations. It also includes 5 Jupyter notebooks in Python, labelled Exercises one, two, three, four and _six_; 
this last is not a typo, as exercise five is included in the second pdf.

The module makes heavy use of applied Fourier analysis, but does not demand much more than familiarity with trigonometric and exponential functions, 
calculus (linearising functions) and simple harmonic motion; in fact it introduces and builds up the requisite theory, as well as illustrates how to 
use scipy functions for Fourier analysis. The module does assume familiarity with the momentum and continuity equations, and thus with the notion of 
what a partial derivative is; as well as a solid grounding in concepts of linear algebra.

A basic conda environment should suffice to run the code. The `ipympl` library, required for animations of propagating waves, may need to be separately installed.
