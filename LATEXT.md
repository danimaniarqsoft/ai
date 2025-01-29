## Bold, italics and underlining

Next, we will now look at some text formatting commands:

- **Bold**: bold text in LaTeX is typeset using the `\textbf{...}` command.
- _Italics_: italicised text is produced using the `\textit{...}` command.
- Underline: to underline text use the `\underline{...}` command.
- Emphasized `\emph{_argument_}` command

## Adding images

Include the packages ones:
```
\usepackage{graphicx} %LaTeX package to import graphics
\graphicspath{{images/}} %configuring the graphicx package
```

Use in every place

```latex
% The \includegraphcs command is 
% provided (implemented) by the 
% graphicx package
\includegraphics{universe}
```

## Captions, labels and references

```latex
\begin{figure}[h]
    \centering
    \includegraphics[width=0.75\textwidth]{mesh}
    \caption{A nice plot.}
    \label{fig:mesh1}
\end{figure}
```

the image below can be referenced by:
```latex
As you can see in figure \ref{fig:mesh1}, the function grows near the origin. This example is on page \pageref{fig:mesh1}.
```