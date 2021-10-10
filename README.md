<b>Boolean Operators</b> use <b>AND, OR, NOT</b> to limit or expand a search. <p><b>AND</b> <i>narrows a search by requiring the results contain both of the search terms connected by AND</i>. In other words, the search results will contain search term X and search term Y.</p> <p><b>OR</b> <i>broadens a search and is usually used when searching related or similar terms.</i> In other words, the search results will contain search term X or search term Y or both.</p>
<p><b>NOT</b><i>narrows searches by excluding sources with a specified search term.</i>In other words, the results will not contain search term X.</p>

---

# Boolean-Laws

<b><i>a OR b = b OR a</i></b>   
Java OR Python = Python OR Java

<b><i>a AND b AND c AND d = b AND d AND c AND a</i></b></br>
Java AND Python AND Bigdata AND Apache = Python AND Apache AND Bigdata AND Java

<b><i>a AND (b OR C) = a AND (c OR b)</i></b></br>
Java AND (Python OR C++)  =  Java AND (C++ OR Python)

<b><i>x OR (y AND z) = (y and z) OR x</i></b></br>
Java OR (Python AND Bigdata) = (Python and bigdata) OR Java

 <b><i>a OR b OR c = (a OR b) OR c = a OR (b OR c) = (a OR c) OR b</i></b></br>
Java OR Golang OR C++  =  (Java OR Golang) OR C++  =  Java OR (Golang OR C++) =  (Java OR C++) OR Golang      

 <b><i>a AND b AND c = (a AND b) AND c = a AND (b AND c) = (a AND c) AND b</i></b></br> 
Java AND Golang AND C++  =  (Java AND Golang) AND C++  =  Java AND (Golang AND C++) = (Java AND C++) AND Golang

<b><i>a AND (b OR c OR d) = a AND (b OR (c OR d))</b></i></br>
Java AND (Golang OR C++ OR Python) = Java AND (Golang OR (C++ OR Python))     

<b><i>a AND (b OR c) ≠ (a AND b) OR c </i> </b></br>
Java AND (Golang OR C++) ≠ (Java AND Golang) OR C++

 <b><i>e AND (f OR g) = (e AND f) OR (e AND g) and e OR (f AND g) = (e OR f) AND (e OR g)</i></b></br>
 AWS AND (shell OR perl ) = (AWS AND shell) OR (AWS AND perl) and 
 AWS OR (shell AND perl) = (AWS OR shell) AND (AWS OR Perl)  

 <b><i> NOT(p AND k) = NOT(p) OR NOT(k) and NOT(p OR k) = NOT(p) AND NOT(k)</i></b></br>
 NOT(Jenkin AND Container) = NOT(Jenkin) OR NOT(Container) and NOT(Jenkin OR Container) = NOT(Jenkin) AND NOT(Container) 

<b><i> s AND (s OR w) = s and s OR (s AND w) = s </i></b></br>
C# AND (C# OR VB.Net) = C# and 
C# OR (C# AND VB.Net) = C# 


