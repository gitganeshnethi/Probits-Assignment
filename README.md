<h1>Probits Technologies - Assignment</h1> <br>

<h2><i>Problem Statement :</i></h2> 
<p><b>Extract the E-mail ID and Technologies from a resume or profile which is in the format of docx</b></p>
<p>The text extraction from a docx requires different libraries, processes.</p>

<h3>Libraries Used</h3>
<ul>
 <li>import docxpy</li>
 <li>import re</li>
 <li>from docx import *</li>
 <li>import pandas as pd</li>
 <li>import os</li>
 <li>import numpy as np</li>
 <li>import pandas as pd</li>
 <li>import string</li>
 <li>import nltk</li>
 <li>from nltk.corpus import stopwords</li>
 <li>from itertools import chain</li></ul>

<p>To solve this problem I used two different approaches where I can get Email-Id and Skills, Technologies</p>

<h3><i>Approach</i></h3>

<ul>
  <li>Regular Expression for Email-ID extraction and simple raw python code for skills and technologies</li>
  <li>Used NLTK to extract skills and Technologies</li></ul>
  
<h3><b>Breif explanation of two approaches</b></h3>

<h4>Extracting Email-ID</h4>
<li>
