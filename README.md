java c
FINC5090 - Finance in the Global Economy 
Individual Assignment Outline 
Semester 2, 2024 
Instructions 
1.   Read   the   instructions   carefully.
2.   This   assignment   is   worth   25% of   total   marks   for   FINC5090.
3.   The   DUE   DATE   is   6 SEPTEMBER   2024.   The   submission   link   will   stop   accepting submissions   at   23:59 on   the   submission   date. Do   not   send   your   work   via   email   if
you miss the deadline. Submissions after the deadline will not be accepted.
4.   Plagiarism is a serious academic offense   that   will   result   in   receiving   zero   marks   and possible disciplinary action.
5.   Ensure   that   you   write   your   correct   Student   ID   at   the   top   of   each   page.    This   is   important so that the marker knows who the author of the assignment is.
6.   Submit your assignment in PDF format only.
Task 
1.   In this task, you will analyze monthly banking statistics   data   to   answer   specific   questions   about   the   Australian banking   sector.    You   are provided   with   data   on   monthly banking statistics from the this website. For this assignment, you must   focus   from   March   2019 to   May   2024.
2.   In these data, you   will see   monthly statistics for each   bank   operating   in   Australia.   For   this   assignment, we   are   only   interested   in   commercial   banks,i.e., banks   that,   in addition to other activities, also   take   deposits   from   and   make   loans   to   house-   holds.
3.   Using   these   data, you   are   required   to   answer   the   following   five   questions:
(a) (3 Marks) The   first   task   relates   to   the   composition   of   banks’ loan   portfolios.   Here, you must determine the share   of   households’   real-estate   loans   in   the   overall loan portfolio of   banks. Technically, this corresponds to a ratio:

Please   note   that   the   dataset   is   a   panel   dataset,   meaning   it   provides   time-   series information for multiple banks.   As you work with the data, you can   estimate   this   ratio   at   the   bank   level   and   then   present   a   time-series   plot   of   the mean   with   95 percent   confidence   intervals. OR, you   can   aggregate   the   data   across   all   banks,estimate   this   ratio   for   each   month, and   present   a   time-series of this estimate. Your interpretation will differ slightly depending on which   of   the   two   you   choose. 
What are the potential factors driving the fluctuations   in the time-series?
(b) (10 Marks) The   next   task   relates   to   a   core   activity   performed   by   banks:   tak-   ing deposits and making loans.   We are interested   in   deposits   (from   all   sec-   tors).      You   are   required   to   estimate   the   Loan-To-Deposit   ratio   that   is   esti-mated   as:
This   ratio   generally   tells   how   much   of   the   loan   volume   is   funded   by   de-   posits.   For instance,   a ratio   of   1 means that   a   bank   has   originated   a   dollar   of loan for each dollar of deposit. A very high or very low Loan-To-Deposit   ratio is not ideal.    A very high ratio implies   excessive   risk   due   to   liquidity,   funding,   and   credit   risk.    A very   low   ratio   indicates   low profitability,   idle   funds, and low competitiveness.Based   on   average   values   over   the   sample   period   for   each   bank, rank   the   big   4 Australian banks, i.e., ANZ Banking Group, Commonwealth Bank, NAB,   and   Westpac.
Next,   from Yahoo   Finance,    download   time-series   of   monthly   returns   for   these   four   banks.      From   these   data,
estimate   a   stock’s   monthly   return   as  From Ken French’s Data Library, click   on ‘International   Research   Returns’   and   download   file   named   ‘Fama/French   Asia   Pacific   ex   Japan   5 Factors’   . This   zipped   folder   contains   monthly returns for factors known to systematically affect stock returns. We are interested in   the sum of Mkt_Rf and RF, which will yield a monthly代 写FINC5090 - Finance in the Global Economy Semester 2, 2024R
代做程序编程语言 return series for the   market.    Next,   subtract   this   sum   from   each   stock’s   return   for   each   period,   which yields a market-adjusted return. We do this operation to subtract fac-   tors affecting all stocks in a given month. The   output   for   this   task   should   include   a   2x2 panel   of   figures: one   figure   for   each   bank. Each   figure   will   contain a   time   series of   a   bank’sLoan-To-Deposit   Ratio and market-adjusted stock returns based on adjusted closing price. In your write-up,   explain how you   think   the   market   perceived   changes   in   this ratio.
(c) (5 Marks) The   next   task   relates   to   the   competitiveness   of   the   Australian banking   sector.    Your   main   task   is   determining   the   evolution   of   the bank-   ing   sector’s   competition   between   March   2019   and   May   2024.    In   finance,   a   measure of   market concentration and competition is Herfindahl–Hirschman   Index (HHI). A higher HHI indicates a less competitive market. The HHI   is   defined   as:

Here,   Xi    equals   either   total   loans   (for   loan   markets)   or   total   deposits   (for   deposit markets) for bank i.   When you repeat this calculation for each time   period,   you   will   end   up   with   two   time-series   for   HHI   based   on   loan   and   deposit markets. Based on this information, you are   required to understand   and interpret the competition dynamics in the Australian banking sector.
For   example, in   market   there   are   total   deposits   of   4 dollars, and   Bank   A   and B   has   deposits   of   3   dollars   and   1   dollar,   respectively.    Thus,   Bank   A   and   B have   a   deposit   market   share   of   75 ( =   3/4)   and   25 (   = 1/4)   percent. Then,HHI for   this   market   is   752   +   252    = 6,   250. In   your   judgment, whether   competition is high or low, you should use the following classification:
Value 
Classification 
HHI <= 100 
Highly competitive industry 
HHI <= 1500 
Unconcentrated markets 
1500 < HHI <= 2500 
Moderately concentrated markets 
HHI > 2500 
Concentrated markets 
(d) (5 Marks) In   June   2022,   ANZ   Banking   Group   Limited   announced   the   takeover of   Suncorp-Metway   Group.      In   August   2023,   the   Australian   Competition         and Consumer Commission (ACCC) blocked the deal, stating that this deal         would further entrench the banking oligopoly.   Evaluate how substantial is ACCC’s claim.   To do so, you may   assume   ANZ   and   Suncorp   as   one bank, repeat   the   steps   that   you   took   in   part   (c) above, and   contrast   the   results. 
(e) (2 Marks) What   is   (are) the   key   caveat(s) of   your   analysis   in   (a)-(d)?
4.   The   word   limit   for   this   project   is   2,000   words. This   word   limit   includes   your   write-up   only   and   excludes   all   other   sections   like   references, section   headings/sub-headings,   and   figure   descriptions,   et   cetera. Write   on   A4   sized   page,   single-spaced, 2.5cm   margins   (top, bottom, left, and   right) with   the   Times   New   Roman font   with   size   12.
5.   Refrain   from   writing   stories. Make   your   point   as   quickly   as   possible. A   suc-   cinct write-up of analysis is always appreciated by the readers.   Note that this is   academic work.   You must substantiate your claim either by your analysis or by   providing a reference from an academic journal (not random websites or blogs).   The   referenced   work   must   be   peer-reviewed   (academic   journals)   or   reputable   (the   Australian   Financial   Review,   the   Economist,   the   Time,   Wall   Street Journal,   etcetera). You   have   access   to   all   sources   via   the   University’s   library. Follow   APA citation style.
6.   We will   discuss   these   questions   in   detail   in   the   first   three   tutorials   (Weeks   2,   3,   and   4). Please   make   sure   you   attend   these   tutorials.




         
加QQ：99515681  WX：codinghelp
