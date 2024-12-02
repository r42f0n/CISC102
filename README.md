java c
CISC102 Fall 2024 
Discrete Structures Portfolio
Due Date: Friday   December   6th 11:59pm EST (Kingston   Time)   to   GradeScope.
Part 1: Topic Review For   each   Unit   taught   this   term, write   a   short   summary   of   the   topic.   You   should   include   relevant definitions,   key   information,   and/or   information   on   how   to   solve   problems   from   this   unit.    A   summary   of   all   topics   covered   is   provided   at   the   end   of this   document.    It   is   recommended   you   review   your   weekly   check-ins.   Be   sure   to   clearly highlight and discuss the   topics   within   the   unit   you   have   mastered   and   those   that   you   are   still   learning.
Requirements: 
•    Between 400-700   words   for   each   section
• Most   definitions   from   the   unit   are   present
• The   summary   is   written   in   your   own   words
•    Must be   written   in   LATEX(See   Overleaf Template   in   onQ)
•   Include   helpful   reminders   that   are   particular   to    YOU    (eg.    “I   always   mix   up   equivalence   relations   and   partial   orders,   so   I   want   to   be   sure   to   remember   those   properties”).
A   Sample   Response   for   Part   1   is   included   at   the   end   of this   document.
Topic Reminder: 
•    Unit   1:   Integers   and   Proofs
                               。CISC102 Fall 2024
。Logic
。Proofs
• Unit   2:   Counting
。Counting   Techniques
。Recurrence   Relations
。Induction
•    Unit 3:   Sets,   Relations   and   Graphs
。Set   Theory
。Functions   and   Relations
。Graph   Theory
More   Questions   will   be   added   this   week.    No   questions   will   be   removed.    This   document   is   current   as   of Nov.    8th
Part 2: Problem Solving 
For each unit, some difficult problems are provided   below.    Please write a   full   solution   in   LATEXto   SIX problems   from   each   section.
Unit 1: Integers and Proofs 
1.    Use   a   truth   table   to   show   that
((p   →   q) ∧   (¬r   → (p ∨   s)))   ≡   (¬p ∨   q) ∧   (r   ∨   p ∨   s)
2.    Let   A   =   {a   ∈   Z   | 4   | a} and   B   =   {b   ∈   Z   | b   ≡   0      mod   4}.   Prove   that   A   =   B   .
3.   Let   P(x,y) represent   that   student   x   has   played   video   game   y,   and   let   Q(x)   represent   that student   x   is   in   Computing.      Using   this   notation   along   with   the   appropriate   quantifiers,   express   the   following   logical   phrases   in   English,   or   the   following   English   phrases   in   logic.   Then,   write   the   negation   of each   logical   statement.
(a)   ∀   x      ∃   y      P(x,y)
(b)    Every   computing   student   has   played   some   videogame
(c)    ∃   x    ∀   y      ¬P(x,y)
(d)    There   is   some   student   that   has   played   every   video   game
4.    Prove,   or   find   a   counterexample:   the   difference   of two   consecutive   perfect   squares   is   odd. 
5.    Prove   that   for   any   a,b,c   ∈   Z   that
ab + ac + bc   ≤   a2   + b2   + c2
[Hint:   consider   (a −   b)2   + (b −   c)2    + (c −   a)2] 
6.   Prove   that   if   gcd(a,m) = d   and   gcd(b,m) =   1   then   gcd(a   ·   b,m)   =   d.
7.    Prove   by   using   and   stating   the   logical   properties   that
p ∧   ¬q   =   ¬(¬(p ∨   q) ∨   q).
Unit 2: Counting 
1.    Prove    that   in    any    sequence   of   4    consecutive   integers,    exactly    one    of   them    must   be    a   multiple   of   4.
2.    Prove   by   induction   that   n3   + 2n   is   divisible   by   3   for   all   n   ∈ N.
3.    A   vegetarian   sandwich   could   have   one   bread   type   (whole   wheat,   white,   sourdough)   and   one   spread    (hummus,    pesto,    mayonnaise).         A    non-vegetarian    sandwich    could    have    one   bread   type   (whole   wheat,   white,   sourdough)   and   one   meat   (chicken,   ham,   beef).      How   many   differen代 写CISC102 Fall 2024 Discrete Structures PortfolioJava
代做程序编程语言t   sandwiches   are   on   the   menu?
4.   Prove   by   induction   that

5.    In   a   dice   game   you   roll   a   die   three   times   in   a   row.    Determine   the   counts   for   each   of   the   following   scenarios:
(a)    On   the   first   roll   you   roll   a   5   (five).    How   many   outcomes   are   there   where   the   total   sum   is   even?
(b)   You   roll   exactly   two   3’s.   How   many   total   outcomes   are   there?
6.      Given   the   recurrence   relation   an      =   13an−1 −61an−2+123an−3 −90an−4    with   a0    = 3,   a1      = 4,   a2    = 2,   and   a3    =   −2.    Prove   using   strong   induction   that   the   closed   form   is
an      = 2n    + 3n − 2n3n   + 5n
[Note:   if the   base   cases   do   not   work,   then   email   Dr.    Meger] 
7.   At   a   Pok´emon   card   trading   party,   there   are   n   trainers,   where   n   ≥ 8.    Each   trainer   trades   cards   with   at   least   1   and   at   most   n   − 1   other   trainers.    Is   it   possible   for   each   trainer   to   complete   a   different   number   of trades?
8.   Prove   using   induction   that

Unit 3:    Sets, Relations and Graphs 
1.       (a)    Let   P,Q,R   be   sets   with    |P|   =   s,    |Q|   = t,   and   |R|   = u.    Determine   exactly   or   state   a range   of values:
i.      |P   ∪   (Q ∩ R)|   ii.      |(P ∪ Q) \ R|
(b)   Let   V   =   {1,   2,   3,   4,   5,   6,   7},   P   =   {1,   2,   5},   and   Q   =   {3,   5,   7}.   Answer   the   following:
i.    Find   (P ∩ Q)   × (P   ∪ Q)
ii.   Find   (P \ Q) × (V \ P)
iii.    Determine   P ∪ Q   (the   complement   of   P ∪ Q   in   V)
2.    Let   C   be   a   set   with   |C|   =   k,   and   D   be   a   set   with   |D|   = p,   where   k   < p.
(a)    How   many   functions   are   there   g   :   C   →   D?
(b)    How   many   injective   (one-to-one)   functions   are   there   g   : C   →   D?
3.    Let   R   =   {(a,b)   ∈ N2 |3   |   (a − b)}.    Prove   that   R   is   an   equivalence   relation.
4.         (a)   Determine   the   adjacency   matrix   for   K5   .
(b)    For   the   wheel   graph   Wn   ,   determine   for   what   values   of   n   ∈   N   Wn      has   a   Hamilton   Cylce,   and   describe   how   to   find   such   a   cycle.
5.    How   many   walks    (edges   and   vertices   may   repeat)   of   length   ℓ   are   there   between   distinct   vertices   in   C4   ?   Where   ℓ   is   the   specific   value   of:   the   last   2   digits   in   your   student   number   added   together.    [ Hint: Consider   the   adjacency   matrix]
6.    Suppose that F   is a forest with   n   vertices,   and   f-many   connected   components.    Determine   the   sum   of   the   degrees   of   all   vertices   in   F.    Give   an   explicit   formula   for   any   forest,   and   state   any/all   theorems   used.
7.   For   any   planar   graph   G =   (V,   E),   Euler’s   inequality   must   hold:   |E|   ≤   3|V   |   − 6Whenever a graph is triangle free,   we   have   the   added   benefit   that   every   region   has   at   least   4 edges   surrounding   it.   We   may   modify   the   computation   in   the   proof   of   Euler’s   Inequality to   determine   a   special   version   for   Triangle   free   graphs.
|E|   ≤   2|V   |   − 4
(a)    Determine   whether   Euler’s   Inequality   holds   for   the   following   graph.   Does   this   mean   that   the   graph   must   be   planar?   Explain.
(b)    Determine   whether   Euler’s   Triangle   Free   Inequality   holds   for   the   following   graph.

Figure   1:   A   simple   graph
8.   Let   f(x) = x-b/x+a   be   afunction   from   R   →   R   where   a   is   the   sum   of   your   student   number   and b   is   the   product   of the   first   two   nonzero   digits   of your   student   number.    Prove   or   disprove   that   f   is:(a)   injective(b)   surjective(c)   bijective



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
