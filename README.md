# Analyzing-Term-Similarity
This is a program written in Python to load any csv with texts and measure character similarities among each word. Try entering the "Believe" for the root word and the CSV named <em>test_doc.csv</em>. If you try this, you should see results as below.

             0      1      2      3      4      5      6      7      8
Believe     98  101.0  108.0  105.0  101.0  118.0  101.0    NaN    NaN
I          105    NaN    NaN    NaN    NaN    NaN    NaN    NaN    NaN
am          97  109.0    NaN    NaN    NaN    NaN    NaN    NaN    NaN
Jason      106   97.0  115.0  111.0  110.0    NaN    NaN    NaN    NaN
I          105    NaN    NaN    NaN    NaN    NaN    NaN    NaN    NaN
like       108  105.0  107.0  101.0    NaN    NaN    NaN    NaN    NaN
to         116  111.0    NaN    NaN    NaN    NaN    NaN    NaN    NaN
have       104   97.0  118.0  101.0    NaN    NaN    NaN    NaN    NaN
fun        102  117.0  110.0    NaN    NaN    NaN    NaN    NaN    NaN
Do         100  111.0    NaN    NaN    NaN    NaN    NaN    NaN    NaN
you        121  111.0  117.0    NaN    NaN    NaN    NaN    NaN    NaN
program    112  114.0  111.0  103.0  114.0   97.0  109.0    NaN    NaN
I          105    NaN    NaN    NaN    NaN    NaN    NaN    NaN    NaN
program    112  114.0  111.0  103.0  114.0   97.0  109.0    NaN    NaN
with       119  105.0  116.0  104.0    NaN    NaN    NaN    NaN    NaN
Python     112  121.0  116.0  104.0  111.0  110.0    NaN    NaN    NaN
I          105    NaN    NaN    NaN    NaN    NaN    NaN    NaN    NaN
believe     98  101.0  108.0  105.0  101.0  118.0  101.0    NaN    NaN
this       116  104.0  105.0  115.0    NaN    NaN    NaN    NaN    NaN
script     115   99.0  114.0  105.0  112.0  116.0    NaN    NaN    NaN
will       119  105.0  108.0  108.0    NaN    NaN    NaN    NaN    NaN
work       119  111.0  114.0  107.0    NaN    NaN    NaN    NaN    NaN
well       119  101.0  108.0  108.0    NaN    NaN    NaN    NaN    NaN
Try        116  114.0  121.0    NaN    NaN    NaN    NaN    NaN    NaN
this       116  104.0  105.0  115.0    NaN    NaN    NaN    NaN    NaN
and         97  110.0  100.0    NaN    NaN    NaN    NaN    NaN    NaN
see        115  101.0  101.0    NaN    NaN    NaN    NaN    NaN    NaN
because     98  101.0   99.0   97.0  117.0  115.0  101.0    NaN    NaN
seeing     115  101.0  101.0  105.0  110.0  103.0    NaN    NaN    NaN
is         105  115.0    NaN    NaN    NaN    NaN    NaN    NaN    NaN
believing   98  101.0  108.0  105.0  101.0  118.0  105.0  110.0  103.0


Computing distance between root: Believe and term: I
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
i  1  2  3  3  4  5  6
------------------------------
Computing distance between root: Believe and term: am
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
a  1  2  3  4  5  6  7
m  2  2  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: Jason
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
j  1  2  3  4  5  6  7
a  2  2  3  4  5  6  7
s  3  3  3  4  5  6  7
o  4  4  4  4  5  6  7
n  5  5  5  5  5  6  7
------------------------------
Computing distance between root: Believe and term: I
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
i  1  2  3  3  4  5  6
------------------------------
Computing distance between root: Believe and term: like
Levenshtein distance is 4
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
l  1  2  2  3  4  5  6
i  2  2  3  2  3  4  5
k  3  3  3  3  3  4  5
e  4  3  4  4  3  4  4
------------------------------
Computing distance between root: Believe and term: to
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
t  1  2  3  4  5  6  7
o  2  2  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: have
Levenshtein distance is 5
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
h  1  2  3  4  5  6  7
a  2  2  3  4  5  6  7
v  3  3  3  4  5  5  6
e  4  3  4  4  4  5  5
------------------------------
Computing distance between root: Believe and term: fun
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
f  1  2  3  4  5  6  7
u  2  2  3  4  5  6  7
n  3  3  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: Do
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
d  1  2  3  4  5  6  7
o  2  2  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: you
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
y  1  2  3  4  5  6  7
o  2  2  3  4  5  6  7
u  3  3  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: program
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
p  1  2  3  4  5  6  7
r  2  2  3  4  5  6  7
o  3  3  3  4  5  6  7
g  4  4  4  4  5  6  7
r  5  5  5  5  5  6  7
a  6  6  6  6  6  6  7
m  7  7  7  7  7  7  7
------------------------------
Computing distance between root: Believe and term: I
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
i  1  2  3  3  4  5  6
------------------------------
Computing distance between root: Believe and term: program
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
p  1  2  3  4  5  6  7
r  2  2  3  4  5  6  7
o  3  3  3  4  5  6  7
g  4  4  4  4  5  6  7
r  5  5  5  5  5  6  7
a  6  6  6  6  6  6  7
m  7  7  7  7  7  7  7
------------------------------
Computing distance between root: Believe and term: with
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
w  1  2  3  4  5  6  7
i  2  2  3  3  4  5  6
t  3  3  3  4  4  5  6
h  4  4  4  4  5  5  6
------------------------------
Computing distance between root: Believe and term: Python
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
p  1  2  3  4  5  6  7
y  2  2  3  4  5  6  7
t  3  3  3  4  5  6  7
h  4  4  4  4  5  6  7
o  5  5  5  5  5  6  7
n  6  6  6  6  6  6  7
------------------------------
Computing distance between root: Believe and term: I
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
i  1  2  3  3  4  5  6
------------------------------
Computing distance between root: Believe and term: believe
Levenshtein distance is 0
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
b  0  1  2  3  4  5  6
e  1  0  1  2  3  4  5
l  2  1  0  1  2  3  4
i  3  2  1  0  1  2  3
e  4  3  2  1  0  1  2
v  5  4  3  2  1  0  1
e  6  5  4  3  2  1  0
------------------------------
Computing distance between root: Believe and term: this
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
t  1  2  3  4  5  6  7
h  2  2  3  4  5  6  7
i  3  3  3  3  4  5  6
s  4  4  4  4  4  5  6
------------------------------
Computing distance between root: Believe and term: script
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
s  1  2  3  4  5  6  7
c  2  2  3  4  5  6  7
r  3  3  3  4  5  6  7
i  4  4  4  3  4  5  6
p  5  5  5  4  4  5  6
t  6  6  6  5  5  5  6
------------------------------
Computing distance between root: Believe and term: will
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
w  1  2  3  4  5  6  7
i  2  2  3  3  4  5  6
l  3  3  2  3  4  5  6
l  4  4  3  3  4  5  6
------------------------------
Computing distance between root: Believe and term: work
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
w  1  2  3  4  5  6  7
o  2  2  3  4  5  6  7
r  3  3  3  4  5  6  7
k  4  4  4  4  5  6  7
------------------------------
Computing distance between root: Believe and term: well
Levenshtein distance is 5
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
w  1  2  3  4  5  6  7
e  2  1  2  3  4  5  6
l  3  2  1  2  3  4  5
l  4  3  2  2  3  4  5
------------------------------
Computing distance between root: Believe and term: Try
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
t  1  2  3  4  5  6  7
r  2  2  3  4  5  6  7
y  3  3  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: this
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
t  1  2  3  4  5  6  7
h  2  2  3  4  5  6  7
i  3  3  3  3  4  5  6
s  4  4  4  4  4  5  6
------------------------------
Computing distance between root: Believe and term: and
Levenshtein distance is 7
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
a  1  2  3  4  5  6  7
n  2  2  3  4  5  6  7
d  3  3  3  4  5  6  7
------------------------------
Computing distance between root: Believe and term: see
Levenshtein distance is 5
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
s  1  2  3  4  5  6  7
e  2  1  2  3  4  5  6
e  3  2  2  3  3  4  5
------------------------------
Computing distance between root: Believe and term: because
Levenshtein distance is 4
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
b  0  1  2  3  4  5  6
e  1  0  1  2  3  4  5
c  2  1  1  2  3  4  5
a  3  2  2  2  3  4  5
u  4  3  3  3  3  4  5
s  5  4  4  4  4  4  5
e  6  5  5  5  4  5  4
------------------------------
Computing distance between root: Believe and term: seeing
Levenshtein distance is 5
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
s  1  2  3  4  5  6  7
e  2  1  2  3  4  5  6
e  3  2  2  3  3  4  5
i  4  3  3  2  3  4  5
n  5  4  4  3  3  4  5
g  6  5  5  4  4  4  5
------------------------------
Computing distance between root: Believe and term: is
Levenshtein distance is 6
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
i  1  2  3  3  4  5  6
s  2  2  3  4  4  5  6
------------------------------
Computing distance between root: Believe and term: believing
Levenshtein distance is 3
The complete distance matrix is depicted below
   b  e  l  i  e  v  e
b  0  1  2  3  4  5  6
e  1  0  1  2  3  4  5
l  2  1  0  1  2  3  4
i  3  2  1  0  1  2  3
e  4  3  2  1  0  1  2
v  5  4  3  2  1  0  1
i  6  5  4  3  2  1  1
n  7  6  5  4  3  2  2
g  8  7  6  5  4  3  3
------------------------------
