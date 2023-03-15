<html>
  <head>
    
  </head>
  <body>
   	<h1>SkimLit Web App: NLP Model for Abstract Sentence Classification</h1>
	<p>SkimLit is a web application that uses machine learning to classify abstract sentences into different roles they play (e.g., objective, methods, results, etc.). The model enables researchers to quickly skim through scientific literature and dive deeper into relevant details when necessary.</p>
	<h2>Technologies</h2>
	<p>The SkimLit web application is built with the following technologies:</p>
	<ul>
		<li>React</li>
		<li>Material UI</li>
		<li>Flask</li>
		<li>TensorFlow</li>
		<li>tensorflow_hub</li>
		<li>sklearn</li>
		<li>Matplotlib</li>
		<li>NumPy</li>
		<li>Pandas</li>
	</ul>
	<h2>Usage</h2>
	<p>To use the SkimLit web application, follow these steps:</p>
	<ol>
		<li>Clone the repository:</li>
		<p><code>git clone https://github.com/&lt;username&gt;/&lt;repository_name&gt;.git</code></p>
		<li>Install the required packages:</li>
		<p><code>pip install -r requirements.txt</code></p>
		<p><code>npm install</code></p>
		<li>Start the Flask server:</li>
		<p><code>python app.py</code></p>
		<li>Start the React app:</li>
		<p><code>cd client</code></p>
		<p><code>npm start</code></p>
		<li>Open the application in your web browser at <a href="http://localhost:3000">http://localhost:3000</a>.</li>
	</ol>
	<h2>Models</h2>
	<p>The following models were used in SkimLit:</p>
	<ul>
		<li>NaiveBayes Model: 72% Accuracy</li>
		<li>Conv1D Model: 78% Accuracy</li>
		<li>Model using Pretrained Token Embedding (Universal Sentence Embedding): 75% Accuracy</li>
		<li>Conv1D Model using Character Level Embedding: 73% Accuracy</li>
		<li>Model with both Token and Character Level Embedding: 76% Accuracy</li>
		<li>Model with Token, Character and Position Level Embedding: 81% Accuracy</li>
	</ul>
	<h2>Notebooks</h2>
	<p>All the notebooks used to train and evaluate SkimLit's models are available in this repository.</p>
	<h2>Acknowledgments</h2>
	<p>This project was developed as part of the "Natural Language Processing in TensorFlow" course by TensorFlow. Special thanks to the instructors of the course for providing guidance and support throughout the project.</p>
  </body>
</html>



