%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}

%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generated PDF is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Hajun Song} \\ \vspace{10pt}
    \small 0432 821 772 $|$ \href{mailto:lolzing78@gmail.com}{lolzing78@gmail.com} \\
\end{center}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Queensland University of Technology}{Brisbane, QLD}
      {Bachelor of Information Technology in Computer Science, Minor in Cyber Security}{Expected Grad - Dec 2024}
    \resumeItemListStart
      \resumeItem{\textbf{Relevant Coursework}{: Cyber Security, Modern Data Management, Database Management, Machine Learning, Algorithm and Complexity, Networks, Programming Principles, Microprocessors and Digital Systems, Building IT Systems}}
    \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------WORK EXPERIENCE-----------
\section{Work Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Go Gaming Lounge}{Manager}{2018 -- Current}{}  
      \resumeItemListStart
        \resumeItem{Supervised a team to ensure a safe and efficient working environment.}
        \resumeItem{Implemented and managed a flexible timetable shift to optimize operational efficiency. Designed schedules to accommodate peak hours and maximize staff effectiveness.}
        \resumeItem{Maintained and updated the local storage server, ensuring seamless data management and accessibility, contributing to streamlined operations.}
      \resumeItemListEnd
      
    \resumeSubheading
      {Bae Song PTY LTD}{Commercial Cleaning Safety Supervisor}{2020 -- Current}{}
      \resumeItemListStart
        \resumeItem{Developed and implemented safety hazard protocols, identified and mitigated potential risks for a secure work environment.}
        \resumeItem{Maintained strong client relationships, committed to continuous improvement, driving enhancements for operational efficiency.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Academic Projects}
  \resumeSubHeadingListStart
    \resumeProjectHeading
      {\textbf{Movie Collection: Algorithmic Analysis and Testing in C\#}}{C\#}
      \resumeItemListStart
        \resumeItem{Examined data structures within a movie collection using algorithms and assessing their time complexity.}
        \resumeItem{Developed a software test plan, generated test data, and analyzed the outcomes to ensure effective algorithmic implementation and robust testing methodology.}
      \resumeItemListEnd

    \resumeProjectHeading
      {\textbf{Object Recognition with Keras API}}{Python | Keras, Team project}
      \resumeItemListStart
        \resumeItem{Utilized the Caltech-256 dataset to implement methods for identifying categories. Developed an image recognition program using the Keras API, specifically Visual Transformers.}
        \resumeItem{Achieved over 50\% accuracy on validation data despite challenges with limited training samples and model complexity, marking a significant milestone in applying deep learning models to practical datasets.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
  \resumeSubHeadingListStart
    \resumeItemListStart
      \resumeItem{\textbf{Languages}{: C\#, Python, C, SQL (Basic), JavaScript (Basic), HTML/CSS}}
      \resumeItem{\textbf{Developer Tools}{: Git, Google Colaboratory, VS Code, Visual Studio, IntelliJ}}
      \resumeItem{\textbf{Libraries}{: Keras, pandas, NumPy, Matplotlib}}
    \resumeItemListEnd
  \resumeSubHeadingListEnd

\end{document}
