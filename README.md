# Resume-1

\documentclass[a4paper,10pt]{article}

% ---------- Margins ----------
\usepackage[left=0.55in,right=0.55in,top=0.55in,bottom=0.55in]{geometry}

% ---------- Packages ----------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{xcolor}
\usepackage{fontawesome5}
\usepackage{titlesec}
\usepackage{parskip}
\usepackage{microtype}

% ---------- Brand Colors ----------
\definecolor{primary}{HTML}{0B3D91}

% ---------- Links ----------
\hypersetup{
    colorlinks=true,
    urlcolor=primary
}

% ---------- Section Style ----------
\titleformat{\section}{\large\bfseries\color{primary}}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{6pt}{3pt}

% ---------- Global Line Spacing (1-page safe) ----------
\linespread{1.08}\selectfont

% ---------- Bullet Spacing (General) ----------
\setlist[itemize]{itemsep=0.5ex, topsep=0.6ex, leftmargin=*}

% ---------- Wrapping Tweaks ----------
\sloppy
\emergencystretch=2em

\begin{document}

% ==================== HEADER ====================%
{\LARGE \textbf{\color{primary} ANANDHACHITAN A}}

\noindent
{\color{primary}\faMapMarker*} Coimbatore
\hfill
{\color{primary}\faPhone} 8610282361
\hfill
{\color{primary}\faEnvelope} \href{mailto:anandhachitan03@gmail.com}{anandhachitan03@gmail.com}

\noindent
{\color{primary}\faLinkedin} \href{https://www.linkedin.com/in/anandhachitan-a-a8440b260/}{linkedin.com/in/anandhachitan-a-a8440b260/}

\vspace{5pt}

% ==================== EXPERIENCE ====================%
\section*{Experience}

\noindent\textbf{Software Developer Intern}
\hfill \textbf{VWR Avantor, Coimbatore}
\hfill Sep 19 2025 -- Mar 19 2026

\textit{IMCM Application (Inventory \& Chemical Management Platform)}
\begin{itemize}
    \item Contributed to an enterprise stock management web application used for ordering and tracking laboratory products across scientific supply chains; collaborated across \textbf{6 sprints} with engineering and QA.
    \item Built/extended \textbf{8+ REST endpoints} in \textbf{Java \& Spring Boot} for catalog, cart, order, and reconciliation modules; aligned contracts with frontend needs.
    \item Enforced validation rules and transactional safeguards for order lifecycles; \textbf{added 30+ unit/integration tests} (JUnit, MockMVC) to strengthen reliability.
    \item Integrated MySQL repository methods for items, lots, and stock ledgers; \textbf{authored 4 API specs/hand‑over notes} to support deployment and support teams.
\end{itemize}

\noindent\textbf{SEO \& Web Design Intern}
\hfill \textbf{Boostability Pvt Ltd, Coimbatore}
\hfill Jun 2024 -- Sep 2024

\begin{itemize}
    \item Built \textbf{12+} responsive pages/components using HTML, CSS, and Bootstrap; organized reusable styles for consistency.
    \item Assisted in keyword planning; prepared \textbf{40+} keyword lists/meta updates across \textbf{15} pages for on‑page/off‑page SEO workflows.
    \item Refined navigation and accessibility (headings, labels, alt text); triaged and resolved \textbf{10+} UI issues with the team.
\end{itemize}

% ==================== PROJECTS ====================%
\section*{Projects}

% ---- Local reduced spacing ONLY for projects ----
{\setlist[itemize]{itemsep=0.2ex, topsep=0.2ex, leftmargin=*}

\noindent\textbf{AI Interview Scheduler}
\hfill \textit{Next.js, Supabase, Express.js, Tailwind CSS, OpenRouter, VAPI}

\begin{itemize}
    \item Designed a full‑stack system for interview creation, scheduling, and assessment with role‑based access; configured \textbf{12+} routes and \textbf{5+} interview templates.
    \item Integrated OpenRouter models for JD‑aware question sets; added VAPI voice sessions accessible via shareable links; conducted \textbf{20+} pilot sessions.
    \item Implemented \textbf{6+} API handlers for session orchestration; stored artifacts and results in Supabase with basic audit logs.
\end{itemize}

\noindent\textbf{Hotel Booking Web Application}
\hfill \textit{MERN Stack}

\begin{itemize}
    \item Built a booking platform with search, comparison, reservation workflows, authentication, and protected routes across \textbf{10+} views.
    \item Created an admin dashboard for property listings, inventory updates, and booking approvals; refined UI for mobile and desktop.
\end{itemize}

} % END reduced spacing block

% ==================== EDUCATION ====================%
\section*{Education}

\begin{tabular*}{\linewidth}{@{}p{5.3cm} p{6.2cm} @{\extracolsep{\fill}} p{3cm}@{}}

\textbf{M.Sc. Software Systems (In Progress)} 
& PSG College of Arts and Science 
& CGPA: 8.1 \\[4pt]

\textbf{Higher Secondary Education} 
& Brindhavan Higher Secondary School 
& 89.24\% \\[4pt]

\textbf{Secondary Education (SSLC)} 
& Brindhavan Higher Secondary School 
& 89\% \\

\end{tabular*}

% ==================== TECHNICAL SKILLS ====================%
\section*{Technical Skills}

\noindent\textbf{Programming Languages:} Java, Python, SQL \\
\noindent\textbf{Frameworks:} Spring, Spring Boot \\
\noindent\textbf{Tools \& Version Control:} Git, GitHub \\
\noindent\textbf{Databases:} MySQL \\
\noindent\textbf{Frontend:} HTML, CSS, Bootstrap, React \\
\noindent\textbf{Backend:} Node.js, REST APIs

% ==================== CERTIFICATIONS ====================%
\section*{Certifications \& Publications}

\noindent NPTEL — Computer Networks; Python for Data Science \\
\noindent Coursera — Text Retrieval and Search Engines (UIUC) \\
\noindent Research Publication — \textit{Impact of Artificial Intelligence in Language Learning}, IJRAR

\end{document}
