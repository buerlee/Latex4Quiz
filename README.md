# Latex4Quiz
Latex template for quiz

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Welcome to writeLaTeX --- just edit your LaTeX on the left,
% and we'll compile it for you on the right. If you give
% someone the link to this page, they can edit at the same
% time. See the help menu above for more info. Enjoy!
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% --------------------------------------------------------------
% This is all preamble stuff that you don't have to worry about.
% Head down to where it says "Start here"
% --------------------------------------------------------------

\documentclass[12pt]{article}



\usepackage{graphicx}
\usepackage{bm}
\usepackage[margin=1in]{geometry}
\geometry{
 	letterpaper,
% 	total={170mm,257mm},
 	left=20mm,
 	top=15mm,
 }
\usepackage{amsmath,amsthm,amssymb}
\usepackage{datetime}


\begin{document}

\begin{titlepage}
\thispagestyle{empty}
\end{titlepage}
\newpage

\begin{flushleft}
\normalsize \texttt{\today}
\end{flushleft}


\begin{center}
 \huge \textbf{PH106 Quiz $\#$3}
\end{center}

\begin{flushright}
  \textbf{Name:}\hspace{50pt}

\vspace{0.5cm}
  Section:\hspace{50pt}

\end{flushright}
\begin{flushleft}


A uniformly charged sphere has total charge \bm{$ Q = 1\, \mathrm{\mu C} $} \ and radius \bm{$R = 10\,  \mathrm{cm}$}.

\hfill


If the electric field is \bm{ $\mid \vec{E} \mid = 10^5 \mathrm{\frac{N}{C}}$} at a distance $\boldsymbol{r}$ from the center of the sphere, how much is the value of $\boldsymbol{r}$ ?

\hfill




Hint: there are \textbf{2 answers}!
\bm{$k=\frac{1}{4\pi \cdot \epsilon _0} \approx 8.9 \times 10^9 \mathrm{\frac{N\cdot m^2}{C^2}}$}

\end{flushleft}


\begin{flushright}
\includegraphics[scale=0.5]{1.PNG} 
\end{flushright}







\end{document} 

