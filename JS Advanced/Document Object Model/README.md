<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1251">
<meta name=Generator content="Microsoft Word 14 (filtered)">


</head>

<body lang=EN-US link=blue vlink=purple>

<div class=WordSection1>

<h1>Lab: Document Object Model</h1>

<p class=MsoNormal>Problems for in-class lab for the <a
href="https://softuni.bg/courses/javascript-advanced">“JavaScript Advanced”
course @ SoftUni</a>. Submit your solutions in the SoftUni judge system at <a
href="https://judge.softuni.bg/Contests/328/">https://judge.softuni.bg/Contests/328/</a>.</p>

<h2>1.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>Sum
Numbers</h2>

<p class=MsoNormal><span lang=BG>Write a JS function </span>that <strong><span
style='font-family:"Calibri","sans-serif"'>reads</span></strong> two numbers
from input fields in a <strong><span style='font-family:"Calibri","sans-serif"'>web
page</span></strong> and puts their <strong><span lang=BG style='font-family:
"Calibri","sans-serif"'>sum </span></strong><strong><span style='font-family:
"Calibri","sans-serif"'>in another field</span></strong> when the user <strong><span
style='font-family:"Calibri","sans-serif"'>clicks</span></strong> on a button.</p>

<h3>Input/Output</h3>

<p class=MsoNormal>There will be no input/output, your program should instead <strong><span
style='font-family:"Calibri","sans-serif"'>modify</span></strong> the DOM of
the given HTML document.</p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample HTML</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=CodeCxSpFirst style='line-height:normal'>&lt;input
  type=&quot;text&quot; id=&quot;num1&quot; /&gt; +</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;input
  type=&quot;text&quot; id=&quot;num2&quot; /&gt; =</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;input type=&quot;text&quot;
  id=&quot;sum&quot; readonly=&quot;readonly&quot; /&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;input
  type=&quot;button&quot; value=&quot;Calc&quot; onclick=&quot;calc()&quot;
  /&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;script&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>    function calc() { </p>
  <p class=CodeCxSpMiddle style='line-height:normal'>       <span
  style='color:#00B050'>// TODO: sum = num1 + num2</span></p>
  <p class=CodeCxSpMiddle style='line-height:normal'>    }</p>
  <p class=CodeCxSpLast style='line-height:normal'>&lt;/script&gt;</p>
  </td>
 </tr>
</table>

<h3>Examples</h3>

<h3><img border=0 width=373 height=217 src="README.md_files/image001.png"> </h3>

<h2>2.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>Show More</h2>

<p class=MsoNormal><span lang=BG>Write a JS function </span>that <strong><span
style='font-family:"Calibri","sans-serif"'>expands</span></strong> a hidden
section of text when a link is <strong><span style='font-family:"Calibri","sans-serif"'>clicked</span></strong>.
The link should <strong><span style='font-family:"Calibri","sans-serif"'>disappear</span></strong>
as the rest of the text shows up.</p>

<h3>Input/Output</h3>

<p class=MsoNormal>There will be no input/output, your program should instead <strong><span
style='font-family:"Calibri","sans-serif"'>modify</span></strong> the DOM of
the given HTML document.</p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample HTML</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=CodeCxSpFirst style='line-height:normal'>Welcome to the &quot;Show
  More Text Example&quot;.</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;a href=&quot;#&quot;
  id=&quot;more&quot; onclick= &quot;showText()&quot;&gt;Read more …&lt;/a&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;span
  id=&quot;text&quot; style= &quot;display:none&quot;&gt;Welcome to JavaScript
  and DOM.&lt;/span&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;script&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  function showText() {</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>    <span
  style='color:#00B050'>// TODO</span></p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  }</p>
  <p class=CodeCxSpLast style='line-height:normal'>&lt;/script&gt;</p>
  </td>
 </tr>
</table>

<h3>Examples</h3>

<p class=MsoNormal><img border=0 width=322 height=265 id="Picture 7"
src="README.md_files/image002.png"> <span style='font-family:Wingdings'>&agrave;</span>
<img border=0 width=322 height=265 id="Picture 6"
src="README.md_files/image003.png"></p>

<h2>3.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>Collect
List Items</h2>

<p class=MsoNormal><span lang=BG>Write a JS function </span>that scans a given <strong><span
style='font-family:"Calibri","sans-serif"'>HTML list</span></strong> and <strong><span
style='font-family:"Calibri","sans-serif"'>appends</span></strong> all
collected list items’ text to a <strong><span style='font-family:"Calibri","sans-serif"'>text
area</span></strong> on the same page when the user <strong><span
style='font-family:"Calibri","sans-serif"'>clicks</span></strong> on a button.</p>

<h3>Input/Output</h3>

<p class=MsoNormal>There will be no input/output, your program should instead <strong><span
style='font-family:"Calibri","sans-serif"'>modify</span></strong> the DOM of
the given HTML document.</p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample HTML</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=CodeCxSpFirst style='line-height:normal'>&lt;ul
  id=&quot;items&quot;&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;li&gt;first
  item&lt;/li&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;li&gt;second
  item&lt;/li&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;li&gt;third
  item&lt;/li&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;/ul&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;textarea
  id=&quot;result&quot;&gt;&lt;/textarea&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;br&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;button
  onclick=&quot;extractText()&quot;&gt;Extract Text&lt;/button&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;script&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  function extractText() {</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>    <span
  style='color:#00B050'>// TODO</span></p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  }</p>
  <p class=CodeCxSpLast style='line-height:normal'>&lt;/script&gt;</p>
  </td>
 </tr>
</table>

<h3>Examples</h3>

<p class=MsoNormal><img border=0 width=335 height=302 id="Picture 8"
src="README.md_files/image004.png"> <span style='font-family:Wingdings'>&agrave;</span>
<img border=0 width=335 height=302 id="Picture 9"
src="README.md_files/image005.png"></p>

<h2>4.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>Colorize
Table</h2>

<p class=MsoNormal><span lang=BG>Write a JS function </span>that <strong><span
style='font-family:"Calibri","sans-serif"'>changes the color </span></strong>of
all <strong><span style='font-family:"Calibri","sans-serif"'>even</span></strong>
rows when the user <strong><span style='font-family:"Calibri","sans-serif"'>clicks</span></strong>
a button. Apply the color &quot;<strong><span style='font-family:"Calibri","sans-serif"'>Teal</span></strong>&quot;
to the target rows.</p>

<h3>Input/Output</h3>

<p class=MsoNormal>There will be no input/output, your program should instead <strong><span
style='font-family:"Calibri","sans-serif"'>modify</span></strong> the DOM of
the given HTML document.</p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample HTML</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=CodeCxSpFirst style='line-height:normal'>&lt;table&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;tr&gt;&lt;th&gt;Name&lt;/th&gt;&lt;th&gt;Town&lt;/th&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;tr&gt;&lt;td&gt;Eve&lt;/td&gt;&lt;td&gt;Sofia&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;tr&gt;&lt;td&gt;Nick&lt;/td&gt;&lt;td&gt;Varna&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;tr&gt;&lt;td&gt;Didi&lt;/td&gt;&lt;td&gt;Ruse&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;tr&gt;&lt;td&gt;Tedy&lt;/td&gt;&lt;td&gt;Varna&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;/table&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;button onclick=&quot;colorize()&quot;&gt;Colorize&lt;/button&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;script&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  function colorize() {</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>    <span
  style='color:#00B050'>// TODO</span></p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  }</p>
  <p class=CodeCxSpLast style='line-height:normal'>&lt;/script&gt;</p>
  </td>
 </tr>
</table>

<h3>Examples</h3>

<p class=MsoNormal> <img border=0 width=203 height=227
src="README.md_files/image006.png"> <span style='font-family:Wingdings'>&agrave;</span>
<img border=0 width=203 height=227 id="Picture 11"
src="README.md_files/image007.png"></p>

<h2>5.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>Countdown</h2>

<p class=MsoNormal>Write a JS program that <strong><span style='font-family:
"Calibri","sans-serif"'>implements </span></strong>a web countdown timer that
supports <strong><span style='font-family:"Calibri","sans-serif"'>minutes</span></strong>
and <strong><span style='font-family:"Calibri","sans-serif"'>seconds</span></strong>.
The user should be able to set the time by calling you function with the number
of seconds required. The time begins to count down as soon as the function is
called. Using the sample code, your function will be called as soon as the page
finishes loading and will begin to count down from 10 minutes.</p>

<h3>Input</h3>

<p class=MsoNormal>Your function will receive a <strong><span style='font-family:
"Calibri","sans-serif"'>number parameter</span></strong>, representing the
starting number of <strong><span style='font-family:"Calibri","sans-serif"'>seconds</span></strong>.</p>

<h3>Output</h3>

<p class=MsoNormal>There will be no output, your program should instead <strong><span
style='font-family:"Calibri","sans-serif"'>modify</span></strong> the DOM of
the given HTML document.</p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample HTML</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=CodeCxSpFirst style='line-height:normal'>&lt;input
  type=&quot;text&quot; id=&quot;time&quot; style=&quot;border:3px solid blue;
  text-align:center; font-size:2em;&quot; disabled=&quot;true&quot;/&gt;</p>
  <p class=Code style='line-height:normal'>&lt;script&gt;window.onload =
  function() { countdown(600); }&lt;/script&gt;</p>
  </td>
 </tr>
</table>

<h3>Examples</h3>

<p class=MsoNormal align=center style='text-align:center'><img border=0
width=301 height=203 id="Picture 10" src="README.md_files/image008.jpg"></p>

<h2>6.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>Extract
Parenthesis</h2>

<p class=MsoNormal>Write a JS function that when <strong><span
style='font-family:"Calibri","sans-serif"'>executed</span></strong>, extracts
all parenthesized text from a target paragraph by given element ID. The result
is a string, joined by &quot;; &quot; (semicolon, space).</p>

<h3>Input</h3>

<p class=MsoNormal>Your function will receive a <strong><span style='font-family:
"Calibri","sans-serif"'>string parameter</span></strong>, representing the
target element ID, from which text must be extracted. The text should be
extracted from the DOM.</p>

<h3>Output</h3>

<p class=MsoNormal><strong><span style='font-family:"Calibri","sans-serif"'>Return
a string</span></strong> with all matched text, separated by &quot;; &quot;
(semicolon, space).</p>

<h3>Examples</h3>

<p class=MsoNormal align=center style='text-align:center'><img border=0
width=396 height=188 id="Picture 2" src="README.md_files/image009.jpg"></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample call</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=Code style='line-height:normal'>let text =
  extract(&quot;content&quot;);</p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Result (stored in variable text)</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=Code style='line-height:normal'>Bulgarian brandy; alcoholic drink;
  even apples</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

<h2>7.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span>* Sum
Table</h2>

<p class=MsoNormal>Write a JS function that finds the first table in a document
and sums the values in the last column. The result is then displayed in an
element with ID &quot;sum&quot;.</p>

<h3>Input/Output</h3>

<p class=MsoNormal>There will be no input/output, your program should instead <strong><span
style='font-family:"Calibri","sans-serif"'>modify</span></strong> the DOM of
the given HTML document.</p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=680
 style='width:510.25pt;margin-left:1.15pt;border-collapse:collapse;border:none'>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  background:#D9D9D9;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=MsoNormal align=center style='margin:0in;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b>Sample HTML</b></p>
  </td>
 </tr>
 <tr>
  <td width=680 valign=top style='width:510.25pt;border:solid windowtext 1.0pt;
  border-top:none;padding:2.85pt 4.25pt 2.85pt 4.25pt'>
  <p class=CodeCxSpFirst style='line-height:normal'>&lt;table&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;tbody&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>   
  &lt;tr&gt;&lt;th&gt;Product&lt;/th&gt;&lt;th&gt;Cost&lt;/th&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>   
  &lt;tr&gt;&lt;td&gt;Beer&lt;/td&gt;   &lt;td&gt;2.88&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>   
  &lt;tr&gt;&lt;td&gt;Fries&lt;/td&gt;  &lt;td&gt;2.15&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>   
  &lt;tr&gt;&lt;td&gt;Burger&lt;/td&gt; &lt;td&gt;4.59&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>   
  &lt;tr&gt;&lt;td&gt;Total:&lt;/td&gt; &lt;td
  id=&quot;sum&quot;&gt;&lt;/td&gt;&lt;/tr&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>  &lt;/tbody&gt;</p>
  <p class=CodeCxSpMiddle style='line-height:normal'>&lt;/table&gt;</p>
  <p class=CodeCxSpLast style='line-height:normal'>&lt;button
  onclick=&quot;sum()&quot;&gt;Sum&lt;/button&gt;</p>
  </td>
 </tr>
</table>

<h3>Example</h3>

<p class=MsoNormal align=center style='text-align:center'><img border=0
width=281 height=285 id="Picture 4" src="README.md_files/image010.jpg"><span
style='font-family:Wingdings'>&agrave;</span> <img border=0 width=281
height=286 id="Picture 5" src="README.md_files/image011.jpg"></p>

</div>

</body>

</html>
