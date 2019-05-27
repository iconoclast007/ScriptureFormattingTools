# ScriptureFormattingTools
Code uses Python (Jupyter) to reformat KJV scripture into Latex source code: generates indexes and local concordance, word counts, etc.

## Indexes currently included
Code can certainly be added to 
AWIP - All words in passage

NWIV - NUmber of Words in Verse

PNIP - Proper Nouns in passage


# Sample Output (for Esther 10) -- cut and past directly into Latex source files and then
use your favorite Latex Tool
%%%%%%%%%%%%%%%%%%%%%%%%%%%
Chapter with Latex format
%%%%%%%%%%%%%%%%%%%%%%%%%%%


\footnote{\textcolor[cmyk]{0.99998,1,0,0}{\hyperlink{TOC}{Return to end of Table of Contents.}}}\textcolor[cmyk]{0.99998,1,0,0}{And the king Ahasuerus laid a tribute upon the land, and \emph{upon} the isles of the sea.}
[2] \textcolor[cmyk]{0.99998,1,0,0}{And all the acts of his power and of his might, and the declaration of the greatness of Mordecai, whereunto the king advanced him, \emph{are} they not written in the book of the chronicles of the kings of Media and Persia?}
[3] \textcolor[cmyk]{0.99998,1,0,0}{For Mordecai the Jew \emph{was} next unto king Ahasuerus, and great among the Jews, and accepted of the multitude of his brethren, seeking the wealth of his people, and speaking peace to all his seed.}


%%%%%%%%%%%%%%%%%%%%%%%%%%%
Chapter with indexed items
%%%%%%%%%%%%%%%%%%%%%%%%%%%


\footnote{\textcolor[cmyk]{0.99998,1,0,0}{\hyperlink{TOC}{Return to end of Table of Contents.}}}\textcolor[cmyk]{0.99998,1,0,0}{And the king Ahasuerus laid a tribute upon the land, and \emph{upon} the isles of the sea.}\index[NWIV]{17!Esther!Est 10:001}\index[AWIP]{And!Esther!Est 10:001}\index[AWIP]{the!Esther!Est 10:001}\index[AWIP]{king!Esther!Est 10:001}\index[AWIP]{Ahasuerus!Esther!Est 10:001}\index[AWIP]{laid!Esther!Est 10:001}\index[AWIP]{a!Esther!Est 10:001}\index[AWIP]{tribute!Esther!Est 10:001}\index[AWIP]{upon!Esther!Est 10:001}\index[AWIP]{the!Esther!Est 10:001 (2)}\index[AWIP]{land!Esther!Est 10:001}\index[AWIP]{and!Esther!Est 10:001}\index[AWIP]{\emph{upon}!Esther!Est 10:001}\index[AWIP]{the!Esther!Est 10:001 (3)}\index[AWIP]{isles!Esther!Est 10:001}\index[AWIP]{of!Esther!Est 10:001}\index[AWIP]{the!Esther!Est 10:001 (4)}\index[AWIP]{sea!Esther!Est 10:001}
[2] \textcolor[cmyk]{0.99998,1,0,0}{And all the acts of his power and of his might, and the declaration of the greatness of Mordecai, whereunto the king advanced him, \emph{are} they not written in the book of the chronicles of the kings of Media and Persia?}\index[NWIV]{41!Esther!Est 10:002}\index[AWIP]{And!Esther!Est 10:002}\index[AWIP]{all!Esther!Est 10:002}\index[AWIP]{the!Esther!Est 10:002}\index[AWIP]{acts!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002}\index[AWIP]{his!Esther!Est 10:002}\index[AWIP]{power!Esther!Est 10:002}\index[AWIP]{and!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002 (2)}\index[AWIP]{his!Esther!Est 10:002 (2)}\index[AWIP]{might!Esther!Est 10:002}\index[AWIP]{and!Esther!Est 10:002 (2)}\index[AWIP]{the!Esther!Est 10:002 (2)}\index[AWIP]{declaration!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002 (3)}\index[AWIP]{the!Esther!Est 10:002 (3)}\index[AWIP]{greatness!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002 (4)}\index[AWIP]{Mordecai!Esther!Est 10:002}\index[AWIP]{whereunto!Esther!Est 10:002}\index[AWIP]{the!Esther!Est 10:002 (4)}\index[AWIP]{king!Esther!Est 10:002}\index[AWIP]{advanced!Esther!Est 10:002}\index[AWIP]{him!Esther!Est 10:002}\index[AWIP]{\emph{are}!Esther!Est 10:002}\index[AWIP]{they!Esther!Est 10:002}\index[AWIP]{not!Esther!Est 10:002}\index[AWIP]{written!Esther!Est 10:002}\index[AWIP]{in!Esther!Est 10:002}\index[AWIP]{the!Esther!Est 10:002 (5)}\index[AWIP]{book!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002 (5)}\index[AWIP]{the!Esther!Est 10:002 (6)}\index[AWIP]{chronicles!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002 (6)}\index[AWIP]{the!Esther!Est 10:002 (7)}\index[AWIP]{kings!Esther!Est 10:002}\index[AWIP]{of!Esther!Est 10:002 (7)}\index[AWIP]{Media!Esther!Est 10:002}\index[AWIP]{and!Esther!Est 10:002 (3)}\index[AWIP]{Persia!Esther!Est 10:002}
[3] \textcolor[cmyk]{0.99998,1,0,0}{For Mordecai the Jew \emph{was} next unto king Ahasuerus, and great among the Jews, and accepted of the multitude of his brethren, seeking the wealth of his people, and speaking peace to all his seed.}\index[NWIV]{35!Esther!Est 10:003}\index[AWIP]{For!Esther!Est 10:003}\index[AWIP]{Mordecai!Esther!Est 10:003}\index[AWIP]{the!Esther!Est 10:003}\index[AWIP]{Jew!Esther!Est 10:003}\index[AWIP]{\emph{was}!Esther!Est 10:003}\index[AWIP]{next!Esther!Est 10:003}\index[AWIP]{unto!Esther!Est 10:003}\index[AWIP]{king!Esther!Est 10:003}\index[AWIP]{Ahasuerus!Esther!Est 10:003}\index[AWIP]{and!Esther!Est 10:003}\index[AWIP]{great!Esther!Est 10:003}\index[AWIP]{among!Esther!Est 10:003}\index[AWIP]{the!Esther!Est 10:003 (2)}\index[AWIP]{Jews!Esther!Est 10:003}\index[AWIP]{and!Esther!Est 10:003 (2)}\index[AWIP]{accepted!Esther!Est 10:003}\index[AWIP]{of!Esther!Est 10:003}\index[AWIP]{the!Esther!Est 10:003 (3)}\index[AWIP]{multitude!Esther!Est 10:003}\index[AWIP]{of!Esther!Est 10:003 (2)}\index[AWIP]{his!Esther!Est 10:003}\index[AWIP]{brethren!Esther!Est 10:003}\index[AWIP]{seeking!Esther!Est 10:003}\index[AWIP]{the!Esther!Est 10:003 (4)}\index[AWIP]{wealth!Esther!Est 10:003}\index[AWIP]{of!Esther!Est 10:003 (3)}\index[AWIP]{his!Esther!Est 10:003 (2)}\index[AWIP]{people!Esther!Est 10:003}\index[AWIP]{and!Esther!Est 10:003 (3)}\index[AWIP]{speaking!Esther!Est 10:003}\index[AWIP]{peace!Esther!Est 10:003}\index[AWIP]{to!Esther!Est 10:003}\index[AWIP]{all!Esther!Est 10:003}\index[AWIP]{his!Esther!Est 10:003 (3)}\index[AWIP]{seed!Esther!Est 10:003}\index[PNIP]{Jews!Esther!Est 10:003}


%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%% Word Statistics
%%%%%%%%%%%%%%%%%%%%%%%%%%


\normalsize



\subsection{Chapter Word Statistics}


%%%%%%%%%%
%%%%%%%%%%
 
\begin{center}
\begin{longtable}{l|c|c|c|c}
\caption[Stats for Esther 10]{Stats for Esther 10} \label{table:Stats for Esther 10} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Verse(s)}} & \multicolumn{1}{|c|}{\textbf{Count}} & \multicolumn{1}{|c|}{\textbf{Unique}} & \multicolumn{1}{|c|}{\textbf{Italics}} & \multicolumn{1}{|c|}{\textbf{Uniq Italic}}  \\ \hline 
\endfirsthead
 
\multicolumn{5}{c}
{{\bfseries \tablename\ \thetable{} -- continued from previous page}} \\  
\hline \multicolumn{1}{|c|}{\textbf{Verse(s)}} & \multicolumn{1}{|c|}{\textbf{Count}} & \multicolumn{1}{|c|}{\textbf{Unique}} & \multicolumn{1}{|c|}{\textbf{Italics}} & \multicolumn{1}{|c|}{\textbf{Uniq Italic}}  \\ \hline 
\endhead
 
\hline \multicolumn{5}{|r|}{{Continued if needed}} \\ \hline
\endfoot 
1 & 17 & 14 & 1 & 1\\ \hline
2 & 41 & 26 & 1 & 1\\ \hline
3 & 35 & 26 & 1 & 1\\ \hline
\hline \hline
Total & 93 & 53 & 3 & 3



\end{longtable}
\end{center}

%%%%%%%%%%
%%%%%%%%%%
 
\subsection{Words by Frequency}
\scriptsize
\begin{center}
\begin{longtable}{l|r}
\caption[Word Frequencies in Esther 10]{Word Frequencies in Esther 10} \label{table:WordsIn-Esther-10} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Word}} & \multicolumn{1}{c|}{\textbf{Frequency}} \\ \hline 
\endfirsthead
 
\multicolumn{2}{c}
{{\bfseries \tablename\ \thetable{} -- continued from previous page}} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Word}} & \multicolumn{1}{c|}{\textbf{Frequency}} \\ \hline 
\endhead
 
\hline \multicolumn{2}{|r|}{{Continued if needed}} \\ \hline
\endfoot
 
\hline \hline
\endlastfoot
the & 15 \\ \hline
of & 11 \\ \hline
and & 7 \\ \hline
his & 5 \\ \hline
king & 3 \\ \hline
And & 2 \\ \hline
Ahasuerus & 2 \\ \hline
all & 2 \\ \hline
Mordecai & 2 \\ \hline
laid & 1 \\ \hline
a & 1 \\ \hline
tribute & 1 \\ \hline
upon & 1 \\ \hline
land & 1 \\ \hline
\emph{upon} & 1 \\ \hline
isles & 1 \\ \hline
sea & 1 \\ \hline
acts & 1 \\ \hline
power & 1 \\ \hline
might & 1 \\ \hline
declaration & 1 \\ \hline
greatness & 1 \\ \hline
whereunto & 1 \\ \hline
advanced & 1 \\ \hline
him & 1 \\ \hline
\emph{are} & 1 \\ \hline
they & 1 \\ \hline
not & 1 \\ \hline
written & 1 \\ \hline
in & 1 \\ \hline
book & 1 \\ \hline
chronicles & 1 \\ \hline
kings & 1 \\ \hline
Media & 1 \\ \hline
Persia & 1 \\ \hline
For & 1 \\ \hline
Jew & 1 \\ \hline
\emph{was} & 1 \\ \hline
next & 1 \\ \hline
unto & 1 \\ \hline
great & 1 \\ \hline
among & 1 \\ \hline
Jews & 1 \\ \hline
accepted & 1 \\ \hline
multitude & 1 \\ \hline
brethren & 1 \\ \hline
seeking & 1 \\ \hline
wealth & 1 \\ \hline
people & 1 \\ \hline
speaking & 1 \\ \hline
peace & 1 \\ \hline
to & 1 \\ \hline
seed & 1 \\ \hline
\end{longtable}
\end{center}



\normalsize



\subsection{Words Alphabetically}
\scriptsize
\begin{center}
\begin{longtable}{l|r}
\caption[Word Alphabetically in Esther 10]{Word Alphabetically in Esther 10} \label{table:WordsIn-Esther-10} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Word}} & \multicolumn{1}{c|}{\textbf{Frequency}} \\ \hline 
\endfirsthead
 
\multicolumn{2}{c}
{{\bfseries \tablename\ \thetable{} -- continued from previous page}} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Word}} & \multicolumn{1}{c|}{\textbf{Frequency}} \\ \hline 
\endhead
 
\hline \multicolumn{2}{|r|}{{Continued if needed}} \\ \hline
\endfoot
 
\hline \hline
\endlastfoot
Ahasuerus & 2 \\ \hline
And & 2 \\ \hline
For & 1 \\ \hline
Jew & 1 \\ \hline
Jews & 1 \\ \hline
Media & 1 \\ \hline
Mordecai & 2 \\ \hline
Persia & 1 \\ \hline
\emph{are} & 1 \\ \hline
\emph{upon} & 1 \\ \hline
\emph{was} & 1 \\ \hline
a & 1 \\ \hline
accepted & 1 \\ \hline
acts & 1 \\ \hline
advanced & 1 \\ \hline
all & 2 \\ \hline
among & 1 \\ \hline
and & 7 \\ \hline
book & 1 \\ \hline
brethren & 1 \\ \hline
chronicles & 1 \\ \hline
declaration & 1 \\ \hline
great & 1 \\ \hline
greatness & 1 \\ \hline
him & 1 \\ \hline
his & 5 \\ \hline
in & 1 \\ \hline
isles & 1 \\ \hline
king & 3 \\ \hline
kings & 1 \\ \hline
laid & 1 \\ \hline
land & 1 \\ \hline
might & 1 \\ \hline
multitude & 1 \\ \hline
next & 1 \\ \hline
not & 1 \\ \hline
of & 11 \\ \hline
peace & 1 \\ \hline
people & 1 \\ \hline
power & 1 \\ \hline
sea & 1 \\ \hline
seed & 1 \\ \hline
seeking & 1 \\ \hline
speaking & 1 \\ \hline
the & 15 \\ \hline
they & 1 \\ \hline
to & 1 \\ \hline
tribute & 1 \\ \hline
unto & 1 \\ \hline
upon & 1 \\ \hline
wealth & 1 \\ \hline
whereunto & 1 \\ \hline
written & 1 \\ \hline
\end{longtable}
\end{center}



\normalsize



\subsection{Word Lengths in Chapter}
\normalsize
\begin{longtable}{l|p{3.75in}}
\caption[Words by Length in Esther 10]{Words by Length in Esther 10} \label{table:WordsIn-Esther-10} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Length}} & \multicolumn{1}{c|}{\textbf{Words}} \\ \hline 
\endfirsthead
 
\multicolumn{2}{c}
{{\bfseries \tablename\ \thetable{} -- continued from previous page}} \\ 
\hline \multicolumn{1}{|c|}{\textbf{Length}} & \multicolumn{1}{c|}{\textbf{Words}} \\ \hline 
\endhead
 
\hline \multicolumn{2}{|r|}{{Continued if needed}} \\ \hline
\endfoot
 
\hline \hline
\endlastfoot
1 & a \\ \hline
2 & of, in, to \\ \hline
3 & And, the, and, sea, all, his, him, \emph{are}, not, For, Jew, \emph{was} \\ \hline
4 & king, laid, upon, land, \emph{upon}, acts, they, book, next, unto, Jews, seed \\ \hline
5 & isles, power, might, kings, Media, great, among, peace \\ \hline
6 & Persia, wealth, people \\ \hline
7 & tribute, written, seeking \\ \hline
8 & Mordecai, advanced, accepted, brethren, speaking \\ \hline
9 & Ahasuerus, greatness, whereunto, multitude \\ \hline
10 & chronicles \\ \hline
11 & declaration \\ \hline
\end{longtable}






%%%%%%%%%%
%%%%%%%%%%
