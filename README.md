% Options for packages loaded elsewhere
\PassOptionsToPackage{unicode}{hyperref}
\PassOptionsToPackage{hyphens}{url}
%
\documentclass[
]{article}
\usepackage{amsmath,amssymb}
\usepackage{lmodern}
\usepackage{iftex}
\ifPDFTeX
  \usepackage[T1]{fontenc}
  \usepackage[utf8]{inputenc}
  \usepackage{textcomp} % provide euro and other symbols
\else % if luatex or xetex
  \usepackage{unicode-math}
  \defaultfontfeatures{Scale=MatchLowercase}
  \defaultfontfeatures[\rmfamily]{Ligatures=TeX,Scale=1}
\fi
% Use upquote if available, for straight quotes in verbatim environments
\IfFileExists{upquote.sty}{\usepackage{upquote}}{}
\IfFileExists{microtype.sty}{% use microtype if available
  \usepackage[]{microtype}
  \UseMicrotypeSet[protrusion]{basicmath} % disable protrusion for tt fonts
}{}
\makeatletter
\@ifundefined{KOMAClassName}{% if non-KOMA class
  \IfFileExists{parskip.sty}{%
    \usepackage{parskip}
  }{% else
    \setlength{\parindent}{0pt}
    \setlength{\parskip}{6pt plus 2pt minus 1pt}}
}{% if KOMA class
  \KOMAoptions{parskip=half}}
\makeatother
\usepackage{xcolor}
\usepackage[normalem]{ulem}
\setlength{\emergencystretch}{3em} % prevent overfull lines
\providecommand{\tightlist}{%
  \setlength{\itemsep}{0pt}\setlength{\parskip}{0pt}}
\setcounter{secnumdepth}{-\maxdimen} % remove section numbering
\ifLuaTeX
  \usepackage{selnolig}  % disable illegal ligatures
\fi
\IfFileExists{bookmark.sty}{\usepackage{bookmark}}{\usepackage{hyperref}}
\IfFileExists{xurl.sty}{\usepackage{xurl}}{} % add URL line breaks if available
\urlstyle{same} % disable monospaced font for URLs
\hypersetup{
  hidelinks,
  pdfcreator={LaTeX via pandoc}}

\author{}
\date{}

\begin{document}

\hypertarget{want2remember-cs-3338-final-project}{%
\section{\texorpdfstring{\textbf{Want2Remember -- CS 3338 Final
Project}}{Want2Remember -- CS 3338 Final Project}}\label{want2remember-cs-3338-final-project}}

A simple browser-based memory tracker that allows users to store, view,
and delete memory notes using localStorage. Built with HTML, CSS, and
JavaScript. Final project by Kevin Bayona-Galindo \& Niko Tartinsky.

\hypertarget{jira-board}{%
\subsection{\texorpdfstring{\textbf{Jira
Board}}{Jira Board}}\label{jira-board}}

Sprint planning, task tracking, and bugs are managed through Jira:\\
\href{https://cs3338group6.atlassian.net/jira/software/projects/W2R/boards/39}{\uline{https://cs3338group6.atlassian.net/jira/software/projects/W2R/boards/39}}

\hypertarget{project-objectives}{%
\subsection{\texorpdfstring{\textbf{Project
Objectives}}{Project Objectives}}\label{project-objectives}}

\begin{itemize}
\item
  \begin{quote}
  Create a simple memory-saving app using web technologies
  \end{quote}
\item
  \begin{quote}
  Store memory entries (title + note) locally using browser localStorage
  \end{quote}
\item
  \begin{quote}
  Allow deletion of individual memories with real-time UI updates
  \end{quote}
\item
  \begin{quote}
  Integrate testing (TestRail), project tracking (Jira), and deployment
  (Docker)
  \end{quote}
\item
  \begin{quote}
  Document the full lifecycle of the project across 4 snapshots
  \end{quote}
\end{itemize}

\hypertarget{why-this-project-matters}{%
\subsection{\texorpdfstring{\textbf{Why This Project
Matters}}{Why This Project Matters}}\label{why-this-project-matters}}

Want2Remember helps users store bite-sized personal notes or reminders.
It\textquotesingle s a great demonstration of client-side storage, UI
responsiveness, and full-stack-ready design (via Docker setup).

\hypertarget{how-to-run-the-project}{%
\subsection{\texorpdfstring{\textbf{How to Run the
Project}}{How to Run the Project}}\label{how-to-run-the-project}}

\hypertarget{option-1-run-locally}{%
\subsubsection{\texorpdfstring{\textbf{�� Option 1: Run
Locally}}{�� Option 1: Run locally}}\label{option-1-run-locally}}

\begin{enumerate}
\def\labelenumi{\arabic{enumi}.}
\item
  \begin{quote}
  Download or clone the repository
  \end{quote}
\item
  \begin{quote}
  git clone
  https://github.com/kbthepioneer/Want2Remember-Final-Project.git
  \end{quote}
\end{enumerate}

\end{document}
