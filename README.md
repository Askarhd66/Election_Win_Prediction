<h1>Election Outcome Modeling from Campaign Spend and Popularity</h1>

<h2>Project overview</h2>
<p>
An election dataset was collected with information on campaign spending and candidate
popularity. This project uses logistic regression to estimate the probability that a
candidate will win or lose based on these factors.
</p>

<h2>Business / political problem</h2>
<p>
Campaign teams wanted to:
</p>
<ul>
  <li><b>Understand the relationship</b> between spending, popularity, and winning.</li>
  <li><b>Estimate win probability</b> for different campaign strategies.</li>
  <li><b>Allocate budgets</b> more effectively across candidates or regions.</li>
</ul>

<h2>Objectives</h2>
<ul>
  <li><b>Build a logistic regression model</b> to classify win vs loss.</li>
  <li><b>Quantify the impact</b> of money spent and popularity rank.</li>
  <li><b>Evaluate model performance</b> using standard classification metrics.</li>
</ul>

<h2>Data and features</h2>
<p>
The dataset includes:
</p>
<ul>
  <li><b>Campaign spend:</b> amount of money spent by the candidate.</li>
  <li><b>Popularity rank:</b> relative popularity score or ranking.</li>
  <li><b>Target variable:</b> election outcome (win or lose).</li>
</ul>

<h2>Methodology</h2>
<ul>
  <li><b>Data preprocessing:</b> cleaning, scaling numeric variables.</li>
  <li><b>EDA:</b> exploring how spend and popularity relate to outcomes.</li>
  <li><b>Modeling:</b> logistic regression on scaled data.</li>
  <li><b>Evaluation:</b> confusion matrix, accuracy, ROC curve, and AUC.</li>
</ul>

<h2>Key results</h2>
<ul>
  <li><b>Win probability estimates</b> for each candidate.</li>
  <li><b>Coefficient interpretation</b> showing how spend and popularity affect odds of winning.</li>
  <li><b>Scenario analysis</b> by varying spend or popularity inputs.</li>
</ul>

<h2>Impact</h2>
<ul>
  <li><b>Strategic planning:</b> data-driven guidance for campaign investments.</li>
  <li><b>Resource allocation:</b> focusing funds where they have the most impact.</li>
</ul>
