# M3M6LectureNotes
Lecture notes for M3M6 Methods of Mathematical Physics

Each file is a Jupyter notebook, that can be viewed using the Jupyter Notebook viewer:

1. [Course overview](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%201.ipynb)
2. [Cauchy's theorem](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%202.ipynb)
3. [Cauchy's integral formula and Taylor series](http://nbviewer.jupyter.org/github/dlfivefifty/M3M6LectureNotes/blob/master/Lecture%203.ipynb)

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
Pkg.clone("https://github.com/dlfivefifty/ComplexPhasePortrait.jl")
```
3. Boot-up Jupyter by running in Julia
```julia
using IJulia
@async notebook()
```
4. Download the files and drag and drop (or better yet, use `git` to clone the reposaitory and stay up-to-date).
