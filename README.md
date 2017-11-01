# Course material for M3M6 Methods of Mathematical Physics

## Reading list

1. M.J. Ablowitz & A.S. Fokas, Complex Variables: Introduction and Applications, Second Edition, Cambridge University Press, 2003
2. R. Earl, [Metric Spaces and Complex Analysis](https://courses.maths.ox.ac.uk/node/view_material/5392), 2015

## Problem sheets

1. [Problem sheet 1](https://github.com/dlfivefifty/M3M6LectureNotes/raw/master/Problem%20Sheet%201.pdf) [(Solutions)](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Solution%20Sheet%201.ipynb)


## Lecture notes

Each file is a Jupyter notebook, that can be viewed using the Jupyter Notebook viewer:

1. [Course overview](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%201.ipynb)
2. [Cauchy's theorem](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%202.ipynb)
3. [Cauchy's integral formula and Taylor series](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%203.ipynb)
4. [Trapezium rule, Fourier series and Laurent series](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%204.ipynb)
5. [Residue theorem](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%205.ipynb)
6. [Analyticity at infinity](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%206.ipynb)
7. [Integrals over the real line](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%207.ipynb)
8. [Algebraic powers and inferred analyticity](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%208.ipynb)
9. [Cauchy transforms](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%209.ipynb)
10. [Hilbert transforms](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%2010.ipynb)
11. [Riemann–Hilbert problems](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%2011.ipynb)
11. [Electric charges in a potential well (preliminary)](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%2012.ipynb)

To run the files on your own machine, use the following steps:

1. Download [Julia v0.6](https://julialang.org/downloads/)
2. In Julia, install the necessary packages:
```julia
Pkg.add("ApproxFun")
Pkg.add("Plots")
Pkg.add("GR")
Pkg.add("Plotly")
Pkg.add("PlotlyJS")
Pkg.add("Interact")
Pkg.add("IJulia")
Pkg.add("DifferentialEquations")
Pkg.clone("https://github.com/dlfivefifty/ComplexPhasePortrait.jl")
```
3. Boot-up Jupyter by running in Julia
```julia
using IJulia
@async notebook()
```
4. Download the files and drag and drop (or better yet, use `git` to clone the reposaitory and stay up-to-date).
