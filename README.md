# Analyzing-Term-Similarity
This is a program written in Python to load any csv with texts and measure character similarities among each word. Try entering the <strong>Believe</strong> for the root word and the CSV named <em>test_doc.csv</em>.

<p>If you try the csv provided here, you should see results like that below.</p>
<p>These results show the Unicode value for each character.</p>
<img src="https://raw.githubusercontent.com/JasonScottSchneider/Analyzing-Term-Similarity/master/documentation/results1.jpg" />
<p>After running the Levenshtein distance with the csv provided and the root word <strong>Believe</strong>, you should see results like that below.</p>
<img src="https://raw.githubusercontent.com/JasonScottSchneider/Analyzing-Term-Similarity/master/documentation/results2_1.jpg" />
<img src="https://raw.githubusercontent.com/JasonScottSchneider/Analyzing-Term-Similarity/master/documentation/results2_2.jpg" />
<img src="https://raw.githubusercontent.com/JasonScottSchneider/Analyzing-Term-Similarity/master/documentation/results2_3.jpg" />
<p>It is interesting to see that switching the order of letters changes the distance measure as shown below among <strong>believing</strong>, <strong>believe</strong>, <strong>beleive</strong>, and <strong>belevie</strong>. This shows that the Levenshtein distance is not just making assumption on whether a word has the same characters, but it is measuring the order that characters occur, too.
<img src="https://raw.githubusercontent.com/JasonScottSchneider/Analyzing-Term-Similarity/master/documentation/results3.jpg" />
