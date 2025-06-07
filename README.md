
%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}
\usepackage[colorlinks=true, urlcolor=blue, linkcolor=black]{hyperref}
\usepackage{xcolor}

\usepackage{graphicx}
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
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \useusepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{\item\small{#1 \vspace{-2pt}}}

\newcommand{\classesList}[4]{
	\item\small{
    	{#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
	\begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
  	\textbf{#1} & \textbf{\small #2} \\
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
	\begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
  	\small#1 & \textbf{}\\
	\end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\documentclass[11pt, a4paper]{article} % Set the font size to 11pt and paper size to A4
\usepackage{fontawesome} % For using icons
\usepackage{hyperref} % For hyperlinks
\usepackage[utf8]{inputenc} % For handling unicode characters
\usepackage{geometry} % For setting page geometry
\usepackage{enumitem} % For custom bullet points
\geometry{margin=0.45in} % Adjusts the margins to fit the content better on A4 paper

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape MUKUL KUMAR} \\ \vspace{1pt}
    \small 
    \raisebox{-0.1\height}\faPhone\ \textcolor{blue}{+91 9891326275} ~ 
    \raisebox{-2pt}{\includegraphics[height=10pt]{gmail.png}}~\href{mailto:techmukul001@gmail.com}{\underline{techmukul001@gmail.com}} ~
    \raisebox{-2pt}{\includegraphics[height=10pt]{linke.png}}~\href{https://www.linkedin.com/in/mukul-k-714215288/}{\underline{LinkedIn}} ~
    \raisebox{-2pt}{\includegraphics[height=10pt]{gitimage.png}}~\href{https://github.com/mukul18-11}{\underline{GitHub}} ~
    \raisebox{-2pt}{\includegraphics[height=10pt]{leetcode.png}}~\href{https://leetcode.com/u/mukul18_11/}{\underline{LeetCode}} \\
    \vspace{-8pt}
\end{center}






%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
    {Netaji Subhas University of Technology}{Dec 2021 - Aug 2025}
    {B.Tech in Mechanical{\color{white} Bachelor's Degree in Computer Science}}{Delhi, India}
  \resumeSubHeadingListEnd
%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
\resumeSubheading
  {\href{https://cdn.unstop.com/uploads/user-project-files/66a6c6792c11f_mukul_kumar_other.png}{AccioJob}}{March 2023 - July 2023}
  {Intern - Mentor {\color{white}GitHUb SQL NoSQL MongoDB MySQL PostgreSQL}}{On Site}
  \resumeItemListStart
    \resumeItem{Mentored over \textbf{1500 students}, providing guidance and support on Data Structures and Algorithms (DSA).}
    \resumeItem{Conducted over \textbf{1500+ technical interviews} focused on DSA, helping students prepare for real-world scenarios.}
    \resumeItem{Resolved student doubts and provided in-depth explanations to ensure a clear understanding of concepts.}
    \resumeItem{Built and implemented a \textbf{Discord chatbot} to automate common queries and facilitate smooth communication.}
  \resumeItemListEnd
\resumeSubHeadingListEnd
%-----------PROJECTS-----------
\section{PROJECTS}
\resumeSubHeadingListStart

\resumeProjectHeading
{\href{}{\textbf{\large{\underline{Keeper App}}}} $|$ \large{\underline{React.js}}}{}
\vspace{-0.5pt}  % Slightly reduced space
\resumeItemListStart
\vspace{-2pt}  % Tighter bullet spacing
\resumeItem{\normalsize{Built a \textbf{note-taking application} inspired by Google Keep using \textbf{React.js}.}}
\vspace{2pt}
\resumeItem{\normalsize{Implemented features for \textbf{creating, editing, and deleting notes}, focusing on component-based architecture.}}
\vspace{2pt}
\resumeItem{\normalsize{Emphasized \textbf{state management} and \textbf{responsive design} to enhance user experience.}}
\resumeItemListEnd
\vspace{-4pt}

\resumeProjectHeading
{\href{}{\textbf{\large{\underline{Chat App}}}} $|$ \large{\underline{Node.js, Express.js, Socket.io}}}{}
\vspace{-0.5pt}
\resumeItemListStart
\vspace{-2pt}
\resumeItem{\normalsize{Created a \textbf{real-time chat application} using \textbf{Node.js}, \textbf{Express.js}, and \textbf{Socket.io}.}}
\vspace{2pt}
\resumeItem{\normalsize{Enabled users to join different \textbf{chat rooms} and communicate instantly.}}
\vspace{2pt}
\resumeItem{\normalsize{Implemented features like \textbf{user authentication}, \textbf{message broadcasting}, and \textbf{real-time updates} to support multiple concurrent users.}}
\resumeItemListEnd
\vspace{-4pt}

\resumeProjectHeading
{\href{}{\textbf{\large{\underline{Weather App}}}} $|$ \large{\underline{Node.js, Express.js, APIs}}}{}
\vspace{-0.5pt}
\resumeItemListStart
\vspace{-2pt}
\resumeItem{\normalsize{Developed a \textbf{weather forecasting application} using \textbf{Node.js} and \textbf{Express.js}.}}
\vspace{2pt}
\resumeItem{\normalsize{Integrated with the \textbf{OpenWeatherMap API} to fetch real-time weather data.}}
\vspace{2pt}
\resumeItem{\normalsize{Implemented \textbf{dynamic content rendering} and \textbf{error handling} for enhanced user experience.}}

\resumeItemListEnd
\vspace{0pt}  % Minimal extra gap after last project

\resumeSubHeadingListEnd

%-----------Achievements-----------
\vspace{4pt}
\section*{Achievements {\color{white} Next.js \quad React Native \quad TypeScript}}

\resumeSubHeadingListStart
\resumeItem{Cleared \textbf{Amazon Machine Learning Summer School 2024}.}
\resumeItem{Prefinalist in \textbf{Flipkart Grid 6.0 Software Development and Information Technology Challenge}.}
\resumeItem{Solved \textbf{600+ coding questions} across various platforms.}
\resumeItem{Achieved \textbf{Rank 1857} in LeetCode Biweekly 156.}
\resumeSubHeadingListEnd


%-----------Skills-----------
\section{Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
    \item \textbf{Technical Skills:}
    \begin{itemize}
        \item \textbf{CS Subjects:} DSA, DBMS, OS, OOPS, Machine Learning
        \item \textbf{Programming Languages:} C/C++, JavaScript, Java, Python
        \item \textbf{Technologies:} React.js, Node.js, Express.js, Kotlin, AWS, GCP, Postgres, Scylla
    \end{itemize}
\end{itemize}



%-----------Position of Responsibility-----------
\section{Position of Responsibility}
\resumeSubHeadingListStart

\resumeProjectHeading
    {\textbf{\underline{JUNOON - NSUT Main Campus}} $|$ Team Member}{}
    \resumeItemListStart
    \resumeItemListEnd
\vspace{-13pt}

\resumeProjectHeading
    {\textbf{\underline{DRISHYAM - NSUT Main Campus}} $|$ Design Head}{}
    \resumeItemListStart
    \resumeItemListEnd
\vspace{-13pt}

\resumeProjectHeading
    {\textbf{\underline{IEEE - NSUT Main Campus}} $|$ Execom Member}{}
    \resumeItemListStart
    \resumeItemListEnd

\resumeSubHeadingListEnd
\vspace{-10pt}
\end{document}
my skills cloumn has leetsers a litthle bit bigger mainly because i remove one line now all letters size is differnt i want you to make a little bigger size so that it fits perfectrly in a4 size one page
