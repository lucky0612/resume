%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{tabular}{@{}p{0.33\textwidth}@{}p{0.67\textwidth}@{}}
\begin{minipage}[t]{0.33\textwidth}
    Github \hspace{1.5mm}:// \href{https://github.com/lucky0612}{\bf lucky0612} \\
    LinkedIn:// \href{https://www.linkedin.com/in/lakshya-raj-vijay-4a7258227}{\bf lakshya-raj-vijay-4a7258227} 
     
    % Extra vertical space
\end{minipage}
&
\begin{minipage}[t]{0.67\textwidth}
    \namesection{}{Lakshya Raj Vijay}{ \urlstyle{same}
     \bf 9602524537 | \href{mailto:20laravi03@gmail.com}{\bf 20laravi03@gmail.com}
    }
\end{minipage}
\end{tabular}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{SRM University Ktr}
\descript{B.Tech in Computer Science}
\location{2021 - 2025 | Chennai, India}
\location{ Current CGPA: 8.6 / 10.0}
\sectionsep

\subsection{TILAK PUBLIC SCHOOL}
\descript{XII Standard}
\location{June 2021|  Jaipur, India}
\location{ Percentage: 85 / 100}
\sectionsep

\subsection{Maheshwari Public School}
\descript{X Standard}
\location{May 2019 | Jaipur, India}
\location{ Percentage: 91 / 100}
\sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Coursework}
\subsection{Stanford (Coursera)}
Machine Learning 

\sectionsep

\subsection{Google (Coursera)}
Google IT Automation with Python 
\sectionsep

\subsection{Cisco}
Networking basics  \\
Operating System Basics 

\sectionsep

\subsection{AWS}
Machine Learning Foundations \\
Cloud Foundations\\
Data Engineering
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}

\subsection{FULLSTACK}
\textbullet{} Javascript \textbullet{} Html/Css \textbullet{} MongoDB\\ \textbullet{} Express.js \ \textbullet{} React.js \textbullet{} Node.js \textbullet{}Java\\ \textbullet{} Tailwind \textbullet{} Flask \textbullet{} FastApi\textbullet{} Postman \\ \textbullet{} JSF \textbullet{} Hibernate \textbullet{} SQL \sectionsep
\subsection{AIML}
\textbullet{}Python \textbullet{} Scikit-learn / Tensorflow \textbullet{}Keras \textbullet{} Matplotlib / Seaborn \textbullet{} NLP\\ \textbullet{} Numpy \textbullet{} Pandas  \textbullet{} Data Analytics \\ \sectionsep
\subsection{Extra}
\textbullet{} C++  \textbullet{} Solidity \textbullet{} Devops \textbullet{} CI/CD
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXTRA CURICULAR
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{EXTRA CURICULAR}
\descript{IEI (PROFESSIONAL BODY)  }
 Technical Team Member\\
\textbf{SRMMUN Society : }Business Relations and Marketing Member
\\
\textbf{AARUUSH : }Corporate Strategy and Implementation Member

\sectionsep
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\section{Experience}
\runsubsection{Samsung Prism}
\descript{Research Intern }
\location{Jan 2024 - May 2024 }
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item Developed a Web 3.0 Dapp for Samsung Internet, facilitating blockchain wallet connections and transactions. 
\item Established a Web 3.0 news section to update users on decentralized tech advancements and designed the frontend.
\end{tightemize}
\sectionsep

\runsubsection{AICTE}
\descript{AIML Intern }
\location{May 2023 – July 2023 }
\begin{tightemize}
\item Gained hands-on experience in AI/ML, mastering tools like Python, scikit-learn, TensorFlow, and PyTorch.
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\section{Projects}

\runsubsection{Student Online Meeting Monitoring Portal}
\descript{ }

Developed a full-stack portal for real-time student engagement analysis using Computer Vision and Deep Learning.
Built the back-end with Node.js and Express.js for data processing and API endpoints.
Created a React.js front-end for real-time monitoring and reporting.


\sectionsep

\runsubsection{Road Accident Prediction - Real Time}
\descript{ }

Implemented a CNN for object detection to enhance road safety through accurate obstacle identification.
Developed a model to recognize 43 traffic sign classes, improving road sign interpretation.
Used OpenCV for pothole detection and a CNN for real-time anomaly detection.
Employed Adam optimizer for efficient model training and integrated Mask R-CNN for improved accuracy.

\sectionsep

\runsubsection{IdeaForge}
\descript{ }

Developed IdeaForge, an AI-powered mobile app using Flutter and Node.js that transforms product ideas into comprehensive proposals, UI/UX designs, and website prototypes. Integrated multiple AI models (Gemini, MonsterAPI) to automate the entire product conceptualization process.


\sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\section{ACHIEVEMENTS}
\runsubsection{GOGGLE AI HACKATHON}
\descript{| WINNER }
\location{3\textsuperscript{rd} May 2024 | Global Platform}
Led a team to develop SparkAI, transforming ideas into dynamic content using Google’s GEMINI and AI tools. 
Secured the "Most Impressive Low-Code Implementation" award, winning recognition by the Google Labs team.
\sectionsep

\runsubsection{GLOBALLOGIC HITACHI 30HACKS }
\descript{| 2\textsuperscript{nd} RUNNER-UP}
\location{15\textsuperscript{th}March 2024 | Delhi, India}
Led team RAIL.AI in the final round of a railway system hackathon, integrating genetic algorithms and blockchain for automated operations.
Competed at the onsite event in Delhi, presenting innovative solutions for track scheduling.
\sectionsep

\runsubsection{IIT MADRAS APPIAN AI CHALLENGE }
\descript{| WINNER }
\location{6\textsuperscript{th}Jan 2024 | Chennai, India}
Led team Medh.AI to victory in developing AI-powered Business Process Automation solutions for Melbourne Airport.
Delivered enhanced efficiency, adaptive automation, and data-driven decision-making capabilities.
Recognized for innovation and impactful AI solutions at the prestigious competition hosted by IIT Madras.
\sectionsep
\end{minipage} 
\end{document}  \documentclass[]{article}
