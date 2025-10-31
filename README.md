<h1>📊 Analysis: Average Age by Performance Quartile and Role</h1>

<h2>📝 Description</h2>
<p>
This project includes a script that investigates the <strong>average age of employees across performance quartiles</strong>.
The analysis was motivated by a previous finding showing that <strong>Top Talent Account Executives</strong> have an average age of <strong>42 years</strong>.
The objective of this script is to verify whether a similar age pattern is observed across other roles and quartiles.
</p>

<hr>

<h2>📚 Table of Contents</h2>
<ol>
  <li><a href="#prerequisites">Prerequisites</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#data-analysis-steps">Data Analysis Steps</a></li>
  <li><a href="#ethical-considerations">Ethical Considerations</a></li>
  <li><a href="#export-results">Export Results</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#mock-example">Mock Example</a></li>
</ol>

<hr>

<h2 id="prerequisites">⚙️ Prerequisites</h2>
<ul>
  <li><strong>Python 3.x</strong> installed</li>
  <li><strong>Pandas</strong> library for data manipulation</li>
  <li><strong>OpenPyXL</strong> library for reading and writing Excel files</li>
</ul>

<hr>

<h2 id="installation">🧩 Installation</h2>
<p>You can install the required libraries using pip:</p>
<pre><code>pip install pandas openpyxl
</code></pre>

<hr>

<h2 id="data-analysis-steps">📈 Data Analysis Steps</h2>
<p>The main steps performed by the script are:</p>
<ol>
  <li><strong>Define Your Objective:</strong> Investigate the average age of employees in each performance quartile, based on prior findings where top-performing Account Executives averaged 42 years old.</li>
  <li><strong>Data Collection:</strong> Ensure the dataset includes <code>employee_id</code>, <code>age</code>, and <code>performance_score</code>.</li>
  <li><strong>Load the Data:</strong> Import data from an Excel file into a pandas DataFrame.</li>
  <li><strong>Data Cleaning:</strong> Handle missing values and validate age and performance score fields.</li>
  <li><strong>Calculate Quartiles:</strong> Segment employees into quartiles based on their performance scores.</li>
  <li><strong>Calculate Average Age:</strong> Group data by quartile and compute the average age for each group.</li>
  <li><strong>Analyze Results:</strong> Compare average ages across quartiles, focusing on whether top performers show a similar age trend.</li>
  <li><strong>Visualization (Optional):</strong> Create visual charts for age distribution across quartiles.</li>
  <li><strong>Report Findings:</strong> Summarize insights from the analysis.</li>
  <li><strong>Make Recommendations:</strong> Provide actionable suggestions for talent management and workforce planning.</li>
</ol>

<hr>

<h2 id="ethical-considerations">🧠 Ethical Considerations</h2>
<p>
This analysis aims to understand demographic trends related to performance without reinforcing stereotypes or age-related bias.
Age is only one variable among many and should <strong>never</strong> be interpreted as a determinant of talent, potential, or productivity.
</p>
<ul>
  <li>🔹 The analysis <strong>does not support discriminatory practices</strong> based on age.</li>
  <li>🔹 Results should be used to <strong>promote inclusion and equitable development opportunities</strong> for all employees.</li>
  <li>🔹 Interpret findings carefully, avoiding assumptions that correlate age directly with performance or capability.</li>
  <li>🔹 Always contextualize data insights within a broader, human-centered understanding of professional experience and diversity.</li>
</ul>

<hr>

<h2 id="export-results">📤 Export Results</h2>
<p>The processed data is exported into an Excel file containing:</p>
<ul>
  <li><code>Monthly_Age_Analysis</code> sheet</li>
  <li><code>Overall_Age_Analysis</code> sheet</li>
</ul>

<hr>

<h2 id="contributing">🤝 Contributing</h2>
<p>To contribute to this project:</p>
<ol>
  <li>Fork this repository.</li>
  <li>Create a new branch (<code>git checkout -b feature-name</code>).</li>
  <li>Commit your changes.</li>
  <li>Submit a pull request with a clear description.</li>
</ol>

<hr>

<h2 id="mock-example">🧠 Mock Example</h2>
<p>
Below is a simplified example demonstrating how the script processes and outputs results.
The dataset includes <strong>fictional employees</strong> with different roles and performance scores.
</p>

<h3>🧾 Input Example (Mock Dataset)</h3>
<table>
  <tr>
    <th>employee_id</th>
    <th>role</th>
    <th>age</th>
    <th>performance_score</th>
  </tr>
  <tr><td>001</td><td>SDR</td><td>26</td><td>82</td></tr>
  <tr><td>002</td><td>SDR</td><td>29</td><td>74</td></tr>
  <tr><td>003</td><td>EC</td><td>42</td><td>95</td></tr>
  <tr><td>004</td><td>EC</td><td>38</td><td>88</td></tr>
  <tr><td>005</td><td>EV</td><td>33</td><td>91</td></tr>
  <tr><td>006</td><td>EV</td><td>45</td><td>68</td></tr>
  <tr><td>007</td><td>SDR</td><td>23</td><td>60</td></tr>
  <tr><td>008</td><td>EC</td><td>47</td><td>72</td></tr>
</table>

<h3>⚙️ Process</h3>
<p>
The script calculates quartiles based on <code>performance_score</code> and computes the average <code>age</code> per quartile and per role.
</p>

<h3>📊 Mock Output Example</h3>
<table>
  <tr>
    <th>Role</th>
    <th>Quartile</th>
    <th>Average Age</th>
  </tr>
  <tr><td>SDR</td><td>Q1</td><td>27.5</td></tr>
  <tr><td>SDR</td><td>Q4</td><td>23.0</td></tr>
  <tr><td>EC</td><td>Q1</td><td>40.0</td></tr>
  <tr><td>EV</td><td>Q1</td><td>33.0</td></tr>
  <tr><td>EV</td><td>Q4</td><td>45.0</td></tr>
</table>

<p>
From the mock output, we observe that <strong>ECs (Account Executives)</strong> in the top quartile (Q1) indeed show a higher average age, around <strong>40 years</strong>, supporting the earlier finding that Top Talent ECs tend to be more experienced professionals.
</p>

<hr>

