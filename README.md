# cs-6322-information-retrieval-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [CS 6322: Information Retrieval Homework 1 Solved](https://www.ankitcodinghub.com/product/cs-6322-information-retrieval-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;48916&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 6322: Information Retrieval  Homework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h1>Problem 1&nbsp; (100 points)</h1>
Tokenization

___________________________________________________________________

&nbsp;

A copy of the publicly available Cranfield collection is located on the UTD cs1, cs2, and csgrads1 machines at: /people/cs/s/sanda/cs6322/Cranfield

&nbsp;

Write a program to tokenize and gather information about tokens in the Cranfield collection of documents.&nbsp; You may use any of the following programming languages : C/C++, lex/yacc, Java, Pyhton.

&nbsp;

In the Cranfield collection the document and field boundaries are indicated with SGML tags (“document markup”). SGML tags are not considered words, so they should not be tokenized and included in any of the information your program gathers. The SGML tags in this data follow the conventional style:

&nbsp;

&lt;[/]?tag&gt; | &gt;[/]?tag (attr[=value])+&gt;

&nbsp;

The attributes and the values from the SGML conventional style are optional and appear rarely or not at all in this document collection.

&nbsp;

Use your program to tokenize the documents and to gather the following information:

&nbsp;

<ol>
<li>The number of tokens in the Cranfield text collection;</li>
<li>The number of unique words in the Cranfield text collection;</li>
<li>The number of words that occur only once in the Cranfield text collection; 4. The 30 most frequent words in the Cranfield text collection – list them and their respective frequency information; and</li>
<li>The average number of word tokens per document.</li>
</ol>
&nbsp;

&nbsp;

Turn in this information with your program description. Also make sure that you upload a separate README file describing the way your program should be run and all the additional software you attach. Your program should run on any UTD Unix machine.

&nbsp;

&nbsp;

&nbsp;

HINT: Program Description

&nbsp;

Describe the operation of your program and design decisions. Include the following information.

&nbsp;

<ol>
<li>How long the program took to acquire the text characteristics.</li>
<li>How the program handles:
<ol>
<li>Upper and lower case words (e.g. “People”, “people”, “Apple”, “apple”);</li>
<li>Words with dashes (e.g. “1996-97”, “middle-class”, “30-year”, “tean-ager”)</li>
<li>Possessives (e.g. “sheriff’s”, “university’s”)</li>
<li>Acronyms (e.g., “U.S.”, “U.N.”)</li>
</ol>
</li>
<li>Briefly discuss your major algorithms and data structures.</li>
</ol>
&nbsp;

<h1>Problem 2 (100 points)</h1>
Stemming

___________________________________________________________________

&nbsp;

After you tokenized the documents from the publicly available Cranfield collection, which is located at:

/people/cs/s/sanda/cs6322/Cranfield

&nbsp;

-you are asked to apply stemming to the tokens that you have recognized. For this reason, you need to run the Porter stemmer implementation of your choice. You can use any implementation of the Porter stemmer available in open-source.

&nbsp;

You will need to also report:

<ol>
<li>The number of distinct stems in the Cranfield text collection;</li>
<li>The number of stems that occur only once in the Cranfield text collection; 4. The 30 most frequent stems in the Cranfield text collection – list them and their respective frequency information; and</li>
<li>The average number of word-stems per document.</li>
</ol>
&nbsp;

&nbsp;
