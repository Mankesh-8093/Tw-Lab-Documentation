# LaTeX Documentation

## 1. Introduction

LaTeX is a document preparation system used to create professional documents, research papers, reports and presentations.

## 2. Basic Structure of LaTeX

Every LaTeX document follows a basic structure.

```latex
\documentclass[12pt]{article}

\begin{document}

Hello World!

\end{document}
```

## 3. Text Formatting

LaTeX provides different commands for text formatting.

```latex
\textbf{Bold Text}

\textit{Italic Text}

\underline{Underlined Text}
```

## 4. Headings

```latex
\section{Introduction}

\subsection{Overview}

\subsubsection{Details}
```

## 5. Lists

### Unordered List

```latex
\begin{itemize}
\item C++
\item Python
\item Java
\end{itemize}
```

### Ordered List

```latex
\begin{enumerate}
\item First
\item Second
\item Third
\end{enumerate}
```

## 6. Tables

The tabular environment is used to create tables.

```latex
\begin{tabular}{|c|c|}
\hline
Name & Marks \\
\hline
Aman & 90 \\
Rahul & 85 \\
\hline
\end{tabular}
```

## 7. Adding Images

The graphicx package is used to insert images.

```latex
\usepackage{graphicx}

\begin{document}

\includegraphics[width=5cm]{image.png}

\end{document}
```

## 8. Mathematical Equations

LaTeX is useful for writing mathematical equations.

```latex
\[
a^2+b^2=c^2
\]

\[
E=mc^2
\]
```

## 9. Important LaTeX Commands

| Command | Purpose |
|---|---|
| \documentclass | Defines document type |
| \begin | Starts an environment |
| \end | Ends an environment |
| \section | Creates a section |
| \textbf | Makes text bold |
| \textit | Makes text italic |
| \includegraphics | Inserts an image |
| \usepackage | Loads a package |

## 10. Advantages of LaTeX

- Professional document formatting.
- Easy mathematical equations.
- Automatic numbering.
- Useful for research papers.
- Supports tables and images.

## 11. Conclusion

LaTeX is a powerful document preparation system used for creating technical and academic documents.