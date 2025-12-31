<!-- TwitterSentiment README (HTML) -->

<h1>TwitterSentiment</h1>
<p><strong>Pipeline for pulling and performing sentiment analysis of Tweets on a specific subject</strong></p>

<hr>

<h2>TLDR</h2>
<p>
  <strong>TwitterSentiment</strong> is a reproducible data pipeline to pull tweets on a specific subject, preprocess and clean
  text for use, perform VADER sentiment analysis, and visualize results.
</p>

<h2>Highlights</h2>
<ul>
  <li><strong>API Usage</strong>: access and pulled data from Twitter API</li>
  <li><strong>Text Data</strong>: organizing, cleaning, and preprocessing text data for analysis</strong></li>
  <li><strong>Object-Oriented Programming</strong>: class object for reproducible sentiment analysis</li>
  <li><strong>Sentiment Analysis</strong>: trends in environmental drivers across seasons, climates, and ecosystems</li>
  <li><strong>GitHub and Collaboration</strong>: group project maintained through GitHub</li>
</ul>

<h2>Skills</h2>
<ul>
  <li><strong>Languages</strong>: Python</li>
  <li><strong>Libraries</strong>: Pandas, VADER, matplotlib</li>
  <li><strong>Compute</strong>: API usage, object-oriented programming</li>
  <li><strong>Data Source</strong>: <a href="https://ameriflux.lbl.gov](https://docs.x.com/x-api/introduction">X API</a></li>
</ul>

<h2>Test Case 1: Climate Change Analysis</h2>
<p>
  As a test case, we used the TwitterSentiment pipeline to extract and analyze sentiment towards climate change on
  Twitter across various locations in the United States. From this, we were able to identify regional trends. For 
  example, of the locations observed, Arizona had the most negative tweets regarding climate change, while Florida
  had the most neutral sentiment and New York the most positive.

  Insert image here.
</p>

<h2>Workflow Overview</h2>
<pre>
carbonflux/
├── X_webscrape.py          # Pipeline to pull subject data from Twitter API
├── load_data.py            # Function to load Tweet pickle and preprocess
├── sentimentAnalysis.py    # Class to perform sentiment analysis
├── test_case1              # Climate change test case
└── README.md
</pre>

<h2>Future Directions</h2>
<ul>
  <li><strong>Peer-Reviewed Publication</strong>: In revision, stay tuned!</li>
  <li><strong>AmeriFlux 2025 Annual Meeting Poster</strong>: 
    <a href="communication/AmeriFluxPoster.pdf">View PDF</a>
  </li>
  <li><strong>Biennial Conference of Science and Management Speaker Presentation</strong>: 
    <a href="communication/Presentation_Biennial.pdf">View PDF</a>
  </li>
  <li><strong>Python for Ecologist Workshop Leader</strong>: used this data to train ecologists in Matplotlib and seaborn</li>
  <li><strong>American Geophysical Union 2024 Poster</strong>: 
    <a href="communication/AmeriFluxPoster.pdf">View PDF</a>
  </li>
</ul>

<h2>Contact</h2>

<p>
  For questions or collaboration: <strong>marleeyork2025@gmail.com</strong><br>
<p>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue.svg="badge/status-research--prototype-purple.svg
</p>
