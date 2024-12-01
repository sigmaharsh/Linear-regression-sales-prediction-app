# Linear-regression-sales-prediction-app
<h2>This app is a Machine learning model which runs svm.py app which is basically predicting sales of an organization since i have used streamlit it provides a decent ui </h2>
<p> I have used the following libraries below </p>
<ul>
	<li> streamlit </li>
	<li> pandas </li>
	<li> matplotlib </li>
	<li> scikit-learn </li>
</ul>
<body>
  <h1>Streamlit App Setup Guide</h1>
  <p>This guide explains how to activate a Python virtual environment and run a Streamlit app on <strong>Linux</strong> or <strong>macOS</strong>. 
     <strong>Note:</strong> These instructions may not work on Windows.</p>

  <h2>Prerequisites</h2>
  <ul>
    <li>Python 3.6 or higher installed</li>
    <li>pip (Python package installer)</li>
  </ul>

  <h2>Steps to Setup and Run</h2>

  <h3>1. Create a Virtual Environment</h3>
  <p>Open a terminal in your project directory and run:</p>
  <pre><code>python3 -m venv prediction</code></pre>
  <p>move the svm.py and the .csv file into virtual enviornment folder named "prediction"</p>
    <pre><code>cp svm.py ~/path/to/the/predictionfolder</code></pre>
    <pre><code>cp sales_data_past_2_years.csv  ~/path/to/the/predictionfolder</code></pre>

  <h3>2. Activate the Virtual Environment</h3>
  <pre><code>source prediction/bin/activate</code></pre>
  <p>After activation, your terminal prompt should display <code>(prediction)</code>.</p>

  <h3>3. Install Streamlit</h3>
  <p>With the virtual environment activated, install Streamlit:</p>
  <pre><code>pip install streamlit</code></pre>

  <h3>4. Run the Streamlit App</h3>
  <p>Navigate to the directory containing <code>svm.py</code> and run:</p>
  <pre><code>streamlit run svm.py</code></pre>

  <h3>5. Stop the Streamlit App</h3>
  <p>To stop the app, press <strong>CTRL + C</strong> in the terminal.</p>

  <h3>6. Deactivate the Virtual Environment</h3>
  <p>When done, deactivate the virtual environment with:</p>
  <pre><code>deactivate</code></pre>

  <h2>Warning for Windows Users</h2>
  <p>The above instructions are optimized for Linux and macOS. On Windows, commands may differ, and additional setup may be required.</p>

  <h2>Troubleshooting</h2>
  <ul>
    <li><strong>Command not found:</strong> Ensure Python and pip are installed and available in your system's PATH.</li>
    <li>Verify Streamlit installation with <code>pip list</code> inside the virtual environment.</li>
  </ul>

  <p> the streamlit app now should run on your localhost port 8501</p>

