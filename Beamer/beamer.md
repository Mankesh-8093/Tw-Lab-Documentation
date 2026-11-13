# Beamer Documentation

## 1. Introduction

Beamer is a LaTeX document class used to create presentations and slides.

It is useful for academic presentations, seminars and technical lectures.

## 2. Basic Beamer Structure

```latex
\documentclass{beamer}

\title{My First Presentation}
\author{Mankesh Meena}
\institute{MNIT Jaipur}
\date{\today}

\begin{document}

\begin{frame}
\titlepage
\end{frame}

\begin{frame}{Introduction}
Hello World!
\end{frame}

\end{document}
```

## 3. Creating Slides

The frame environment is used to create individual slides.

```latex
\begin{frame}{My First Slide}
This is my first slide.
\end{frame}
```

## 4. Adding Bullet Points

```latex
\begin{frame}{Programming Languages}

\begin{itemize}
\item C++
\item Python
\item Java
\end{itemize}

\end{frame}
```

## 5. Numbered Lists

```latex
\begin{enumerate}
\item Introduction
\item Main Topic
\item Conclusion
\end{enumerate}
```

## 6. Themes

Beamer provides different presentation themes.

```latex
\usetheme{Madrid}
```

Other themes include:
- Berlin
- CambridgeUS
- Warsaw
- AnnArbor

## 7. Adding Mathematics

```latex
\begin{frame}{Mathematics}

\[
E = mc^2
\]

\end{frame}
```

## 8. Adding Images

```latex
\usepackage{graphicx}

\begin{frame}{Image Slide}
\includegraphics[width=5cm]{image.png}
\end{frame}
```

## 9. Advantages of Beamer

- Creates professional presentations.
- Supports mathematical equations.
- Provides different themes.
- Supports images, tables and lists.
- Easy slide formatting.

## 10. Conclusion

Beamer is a useful LaTeX tool for creating professional academic and technical presentations.