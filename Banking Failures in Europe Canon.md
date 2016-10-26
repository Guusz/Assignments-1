Banking Failures in Europe Canon
================================


\documentclass[DIV=calc, paper=a4, fontsize=11pt, twocolumn]{scrartcl}	 % A4 paper and 11pt font size

\usepackage{lipsum} % Used for inserting dummy 'Lorem ipsum' text into the template
\usepackage[english]{babel} % English language/hyphenation
\usepackage[protrusion=true,expansion=true]{microtype} % Better typography
\usepackage{amsmath,amsfonts,amsthm} % Math packages
\usepackage[svgnames]{xcolor} % Enabling colors by their 'svgnames'
\usepackage[hang, small,labelfont=bf,up,textfont=it,up]{caption} % Custom captions under/above floats in tables or figures
\usepackage{booktabs} % Horizontal rules in tables
\usepackage{fix-cm}	 % Custom font sizes - used for the initial letter in the document

\usepackage{sectsty} % Enables custom section titles
\allsectionsfont{\usefont{OT1}{phv}{b}{n}} % Change the font of all section commands

\usepackage{fancyhdr} % Needed to define custom headers/footers
\pagestyle{fancy} % Enables the custom headers/footers
\usepackage{lastpage} % Used to determine the number of pages in the document (for "Page X of Total")

% Headers - all currently empty
\lhead{Group 10}
\chead{Applied Economic Analysis}
\rhead{European Banking Canon}

% Footers
\lfoot{}
\cfoot{}
\rfoot{\footnotesize Page \thepage\ of \pageref{LastPage}} % "Page 1 of 2"

\renewcommand{\headrulewidth}{0.0pt} % No header rule
\renewcommand{\footrulewidth}{0.4pt} % Thin footer rule

\usepackage{lettrine} % Package to accentuate the first letter of the text
\newcommand{\initial}[1]{ % Defines the command and style for the first letter
\lettrine[lines=3,lhang=0.3,nindent=0em]{
\color{DarkGoldenrod}
{\textsf{#1}}}{}}

%----------------------------------------------------------------------------------------
%	TITLE SECTION
%----------------------------------------------------------------------------------------

\usepackage{titling} % Allows custom title configuration

\newcommand{\HorRule}{\color{DarkGoldenrod} \rule{\linewidth}{1pt}} % Defines the gold horizontal rule around the title

\pretitle{\vspace{-30pt} \begin{flushleft} \HorRule \fontsize{50}{50} \usefont{OT1}{phv}{b}{n} \color{purple} \selectfont} % Horizontal rule before the title

\title{European banking regulations} % Your article title

\posttitle{\par\end{flushleft}\vskip 0.5em} % Whitespace under the title

\preauthor{\begin{flushleft}\large \lineskip 0.5em \usefont{OT1}{phv}{b}{sl} \color{black}} % Author font configuration

\author{} % Your name

\postauthor{\footnotesize \usefont{OT1}{phv}{m}{sl} \color{Black} % Configuration for the institution name
       Tilburg University % Your institution

\par\end{flushleft}\HorRule} % Horizontal rule after the title

\date{26-10-2016} % Add a date here if you would like one to appear underneath the title block

%----------------------------------------------------------------------------------------

\begin{document}

\maketitle % Print the title

\thispagestyle{fancy} % Enabling the custom headers/footers for the first page 

%----------------------------------------------------------------------------------------
%	ABSTRACT
%----------------------------------------------------------------------------------------

% The first character should be within \initial{}
\textbf{This part of the canon will focus on how European banks are regulated.}

%----------------------------------------------------------------------------------------
%	ARTICLE CONTENTS
%----------------------------------------------------------------------------------------

\section*{Section 1}
Regulation policy includes three lines of defence that all contribute to the main goal, financial stability. The first line of defence is policy that prevents developments leading to threats of financial stability. An example of first line policy is mandatory extensive due diligence on mortgages. The second line of defence is policy that increases the resilience of the financial system. An example of second line policy is additional capital requirements for financial institutions. The last line of defence is policy decreasing systemic risk, damage limitation. Whenever an institution fails, the damage to the financial system should be as low as possible such that the taxpayer is paying the damage. An example of third line policy is extensive and sound resolution schemes.

After the global financial crisis of 2008 a major consensus was reached concluding that the European banking regulation was not adequate. Some additional regulations were needed. The Basel Committee of Banking Supervision (BCBS) expanded their guidelines of banking supervision. The European Union (EU) implemented these guidelines in EU legislation. 

Important key principles of European banking regulation from the most recent Basel accord (Basel III) are discussed below.  
First of all, capital requirements, banks need to have a minimum common equity ratio that equals 4.5\%. 
This ratio is calculated by total common equity divided by the total amount of risk-weighted assets. 

 \begin{equation} \label{eq1}
\begin{split}
4.5\% & \geq \frac{Common Equity}{Risk Weighted Assets}
\end{split}
\end{equation}

Moreover a capital ratio of 6\% is demanded. This capital is the sum of common equity, preferred stocks and non-controlling interests. As an addition, a counter cyclical common equity buffer is required; this additional buffer can be up to 2.5\%. In Europe, the implementation of this counter cyclical buffer is not fully implemented yet.

Another key principle is the leverage ratio. This implies that the amount of common equity must be 3\% of total risk exposure. Total risk exposure is exposure of all balance-sheet assets and off-balance sheet risks. In Europe, the leverage ratios of banks are supervised, but not mandatory yet.

The last key principle of banking regulation in the EU is a set of liquidity requirements. A bank is pressurized to have a certain amount of high-quality liquid assets. This amount of liquid assets should equal the net cash outflows over 30 days.
The second liquidity requirement is a Net Stable Funding Ratio (NSFR). This ratio, the available amount of stable funding must be higher than the minimum required amount of stable funding over a one-year period of extended stress.

\begin{table}[]
\centering
\caption{NAMEN ANR TABEL PLAATS DEZE STRAKS VOORAAN}
\label{my-label}
\begin{tabular}{|l|l|}
\hline
Frank van Casteren & ANR  \\ \hline 
Guus van de Wakker & ANR \\ \hline
Dian van Rooi & ANR \\ \hline
Ruben Uijting & ANR \\ \hline
Job Teurlinx &  \\ \hline
Freek Heuvelmans &  \\ \hline
David Chapa &  \\ \hline
Robbert van Riel & 571548  \\ \hline
\end{tabular}
\end{table}

%----------------------------------------------------------------------------------------
%	REFERENCE LIST
%----------------------------------------------------------------------------------------

\begin{thebibliography}{99} % Bibliography - this is intentionally simple in this template

\bibitem[Pleur hier de referenties indien die er zijn]{Pleur hier de referenties indien die er zijn}

\newblock {hoi}
 
\end{thebibliography}

%----------------------------------------------------------------------------------------

\end{document}
Function of Banks
-----------------

Causes of Banking Failures
--------------------------

Consequences of Banking Failures
---------------------------------

History of Banking Failures
-----------------------------
Ever since banks were created the possibility that they could fail has been present. The causes for failure 
in the first banks were due to mismanagement or external factors that banks did not foresee and were 
not prepared to face. One of the first documented cases of a banking failure in Europe is the Amsterdam 
banking crisis of 1763. This crisis came about because the banking sector in the Netherlands had borrowed 
heavily using basic goods as collateral (a guarantee of payment), these goods were sold at a higher price 
than usual due to the Seven Year’s War. When the war was over the prices of the basic goods fell 
dramatically and the amount of money available decreased to a point where intervention by the Bank of 
Amsterdam was required to provide enough money for the banking system. Throughout the rest of the 
18th and 19th centuries most of the banking failures were triggered by mismanagement in banks and/or 
critical loss of confidence from the depositors in the ability of the banks to repay the money that had been 
deposited in their institutions. Notable examples of these situations are the Panics of 1825 and 1866. In 
the year of 1825 a stock market crash in London that was caused from reckless investments in Latin 
America caused the collapse of six banks in London, this event is considered to mark the beginning of the 
modern economic cycles due to the fact that the panic was not caused by an external event but rather by 
speculative behavior. In the 1866 crisis, the failure of a bank called Overend, Gurney and Co. again because 
of mismanagement, prompted the failure of over 200 companies. In the 20th century the worst banking 
crisis was the Great Depression in United States. This event in 1929 was caused by a crash in the American 
Stock Market. Four years later 11,000 of United States 25,000 banks had failed and at the height of the 
Great Depression unemployment had risen to 25%. In the 21st Century we have already had a severe 
banking crisis. This crisis was again brought about by mismanagement and lack of oversight from 
regulating authorities which led to essentially banks betting that housing prices would continue to rise, 
leading to a “housing bubble”. Banks lent money to people who were not credit worthy, and they 
eventually could not pay back, which led to the banks losing money on the money they could not recover 

Regulations
------------

Possible Threats in the Future
--------------------------------
