
```latex
documentclass{article}

usepackage{tikz}
usepackage{pgfplots}
pgfplotsset{compat=1.16}

begin{document}

begin{tikzpicture}

begin{axis}[
xlabel={x},
ylabel={z},
xmin=-5,
xmax=5,
ymin=-5,
ymax=5,
grid=major,
]

addplot[domain=-5:5,smooth,blue] (x, {(-x + y) / A});

end{axis}

end{tikzpicture}

end{document}
```

> This code will create a plot of the equation `z = (-x + y) / A` . The value of `A`  can be changed to change the slope of the plane. For example, if `A = 1` , the plane will be a line.

To compile this code, you will need to have the `tikz`  and `pgfplots`  LaTeX packages installed. You can then compile the code using the following command:

```bash
pdflatex plot.tex
```

This will create a PDF file called `plot.pdf`  that contains the plot.
