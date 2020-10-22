<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1">

  <!-- bootstrap -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">

  <!-- Google fonts -->
  <link href='http://fonts.googleapis.com/css?family=Roboto:400,300' rel='stylesheet' type='text/css'>

  <link rel="stylesheet" type="text/css" href="style.css" />

</head>

<body>


<!-- Header -->
<div id="header" style="text-align:center">
  <h1>Natural Language Processing (NLP)</h1>
  <h3>Adopted from <a href="http://web.stanford.edu/class/cs124/" target="_blank">CS124 by Stanford University</a> (2020)</h3>
  <h3>and <a href="http://web.stanford.edu/class/cs224n/" target="_blank">CS224n by Stanford University</a> (2020)</h3>
  <h3>and <a href="http://computational-linguistics-class.org/lectures.html" target="_blank">CIS530 Computational Linguistics</a> (2020)</h3>  
  <b>Updated: 2020/10/09</b>
  <br>  
  <div style="clear:both;"></div>
</div>


<!-- Intro -->
<div class="container sec" id="intro">
  <p>
    Dear students, I hope the following webpage will assist you in your learning journey about NLP, machine learning and deep learning. <br>
  </p>
</div>


<!-- Content -->
<div class="container sec" id="content">

  <h2>Prerequisites</h2>
  <ul>
      <li><b>Proficiency in Python</b>
          <p>Become familiar with Python 3 (using Numpy, pandas, NLTK, scikit-learn and Keras).</p>
          <p><u>The following resources are recommended if you new to Python Programming:</u></p>
          <ul><p>
              <li>Udemy Python 3 - Learning Python Programming Step-by-Step for Beginners [require login]: <a href="https://www.udemy.com/course/learn-python-programming-a-step-by-step-course-to-beginners/learn/lecture/12935322#content" target="_blank">Udemy course - Python Programming</a></li>
              <li>Udemy Python 3 - Programming basics to advanced: <a href="https://www.udemy.com/course/learn-python-programming-a-step-by-step-course-to-beginners/" target="_blank">Udemy course - Python for Beginners</a></li>
              <li>Youtube (free) - Learn Python in 45 minutes! <a href="https://collab.hpc.ufs.ac.za/index.php/s/cKFTSdtLwnDXyKo" target="_blank">YouTube [74.7MB]</a></li>
              <li>Kaggle introduction to Python (very good): <a href="https://www.kaggle.com/learn/python" target="_blank">Kaggle - Python</a> - Good introduction if you are not familiar with programming.</li>		
			  <li>Google introduction to Python (excellent): <a href="https://developers.google.com/edu/python" target="_blank">Google’s Python Class</a> - If you know how to program but are not proficient in Python, I would recommend going through <b>Google’s Python Class</b> for people who already know how to code, taught by Nick Parlante.</li>	
          </p></ul>   
          <p><u>Useful Python Resources:</u></p>
          <ul><p>
              <li>Chris Albon. Python Scripts for Machine Learning and NLP: <a href="https://chrisalbon.com/#machine_learning" target="_blank">https://chrisalbon.com/#machine_learning</a></li>
              <li>Jason Browlee. Machine Learning Mastery with Python: <a href="https://machinelearningmastery.com/" target="_blank">https://machinelearningmastery.com/</a></li>
              <li>MLwhiz. NLP Learning Series: <a href="https://mlwhiz.com/nlpseries/" target="_blank">https://mlwhiz.com/nlpseries/</a></li>
              <li>TowardsDataScience: Machine Learning and NLP: <a href="https://towardsdatascience.com/machine-learning/home" target="_blank">https://towardsdatascience.com/machine-learning/home</a></li>
              <li>NLTK: <a href="https://www.nltk.org/" target="_blank">https://www.nltk.org/</a> - Natural Langauge Toolkit (Bird,2009)</li>
			  <li>Gensim: <a href="https://pypi.org/project/gensim/" target="_blank">https://pypi.org/project/gensim/</a> - Gensim [library for topic modelling, document indexing and similarity retrieval with large corpora]:</li>
			  <li>scikit-learn: <a href="https://scikit-learn.org/stable/" target="_blank">https://scikit-learn.org/stable/</a></li>
          </p></ul>		  
          <p><u>Useful Keras (Python) Resources:</u></p>
          <ul><p>
		      <li>Keras introduction: <a href="https://chrisalbon.com/" target="_blank">https://chrisalbon.com/</a> (scroll down for the Keras notebooks)</li>
              <li>Keras blog: <a href="https://blog.keras.io" target="_blank">https://blog.keras.io</a> (very useful examples using Keras REST API)</li>	
              <li>Keras Home Page: <a href="https://keras.io/examples/" target="_blank">https://keras.io/examples/</a> (examples by Chollet himself)</li>				  
              <li>Keras Github: <a href="https://github.com/keras-team/keras/tree/master/examples" target="_blank">https://github.com/keras-team/keras/tree/master/examples</a> (these are very useful examples)</li>
          </p></ul>		  
      </li>      
      <li><b>Calculus, Linear Algebra</b>
          <p>You should be comfortable taking (multivariable) derivatives and understanding matrix/vector notation and operations.</p>
      </li>
      <li><b>Basic Probability and Statistics</b>
          <p>You should know basics of probabilities, gaussian distributions, mean, standard deviation, etc.</p>
      </li>
      <li><b>Foundations of Machine Learning</b>
          <p>You should know the basics of machine learning.
             There are many introductions to ML, in webpage, book, and video form. One approachable introduction is Hal Daum&eacute;’s in-progress <a href="http://ciml.info"><i>A Course in Machine Learning</i></a>. Reading the first 5 chapters of that book would be good background. Knowing the first 7 chapters would be even better!</p>
      </li>
  </ul>

  <h2>Reference Texts</h2>
  <p>
    The following texts are useful, and all of them can be read free online.
  </p>
  <ul>
      <li>Dan Jurafsky and James H. Martin. <a href="https://web.stanford.edu/~jurafsky/slp3/" target="_blank">Speech and Language Processing (3rd ed. draft)</a> [free downloads]</li>
      <li>Jacob Eisenstein. <a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf" target="_blank">Natural Language Processing</a> [free download]</li>
      <li>Ian Goodfellow, Yoshua Bengio, and Aaron Courville. <a href="http://www.deeplearningbook.org/" target="_blank">Deep Learning</a></li>
  </ul>
    <p>
    If you have no background in machine learning, the following book is <b>required reading</b>:
    </p>
    <ul>
      <li>
      Sebastian Raschka and Vahid Mirjalili. <a href="https://sebastianraschka.com/books.html" target="_blank">Python Machine Learning. 3rd edition. 2019. Packt</a>
      </li>
  </ul>
    <p>
    If you have no background in neural networks, you might find one of these books helpful to give you more background:
    </p>
    <ul>
      <li>
      Michael A. Nielsen. <a href="http://neuralnetworksanddeeplearning.com" target="_blank">Neural Networks and Deep Learning</a>
      </li>
      <li>
      Eugene Charniak. <a href="https://mitpress.mit.edu/books/introduction-deep-learning" target="_blank">Introduction to Deep Learning</a>
      </li>
  </ul>  
</div>


<!-- Content -->
<!-- Note the margin-top:-20px and the <br> serve to make the #schedule hyperlink display correctly (with the h2 header visible) -->
<div class="container sec" id="schedule" style="margin-top:-20px">
<h2>Online Courses</h2>
<p>
The following courses I found useful in learning about machine learning and deep learning.
</p>
<table class="table">
  <colgroup>
    <col style="width:5%">
    <col style="width:25%">
    <col style="width:70%">
  </colgroup>
  <thead>
  <tr class="active">
    <th>#</th>
    <th>Description</th>
    <th>Online Course</th>
  </tr>
  </thead>
  <tbody>
   
  <tr>
    <td>1.1</td>
    <td>Introduction to Machine Learning
    </td>
    <td>
      Suggested Online Courses:
      <ol>
        <li>Machine Learning: Reading first 7 chapters of "A Course on Machine Learning" (recommended by Stanford): <a href="ttp://ciml.info/" target="_blank">ttp://ciml.info/</a></li>
        <li>Machine Learning by Prof Andrew Ng (Stanford University), Coursera: <a href="https://www.coursera.org/learn/machine-learning/home/welcome" target="_blank">https://www.coursera.org/learn/machine-learning/home/welcome</a></li>
      </ol>
      Suggested Online Tutorials:
      <ol>
        <li>Intro to Machine Learning <b>(Kaggle)</b>: <a href="https://www.kaggle.com/learn/intro-to-machine-learning" target="_blank">https://www.kaggle.com/learn/intro-to-machine-learning</a> (covers how models work, model validation, underfitting, overfitting, random forest)</li>
        <li>Intermediate Machine Learning <b>(Kaggle)</b>: <a href="https://www.kaggle.com/learn/intermediate-machine-learning" target="_blank">https://www.kaggle.com/learn/intermediate-machine-learning</a> (covers missing values, categorical variables, pipelines, cross-validation, XGBoost, data leakage)</li>
      </ol>
    </td>	
  </tr>

  <tr>
    <td>1.2</td>
    <td>Introduction to Deep Learning
    </td>
    <td>
      Suggested Online Courses:
      <ol>
        <li>Introduction to Deep Learning by National Research University Higher School of Economics, Coursera: <a href="https://www.coursera.org/learn/intro-to-deep-learning" target="_blank">https://www.coursera.org/learn/intro-to-deep-learning</a></li>
      </ol>
    </td>
  </tr>
  
  <tr>
    <td>2.1</td>
    <td>Introduction to NLP
    </td>
    <td>
      Suggested Online Courses:
      <ol>
        <li>NLP with Python for Machine Learning Essential Training, LinkedIn Training: <a href="https://www.linkedin.com/learning/nlp-with-python-for-machine-learning-essential-training/welcome?u=37069596" target="_blank">https://www.linkedin.com/learning/nlp-with-python-for-machine-learning-essential-training</a> [UFS login required]</li>
      </ol>
    </td>
  </tr>
  
  <tr>
    <td>2.2</td>
    <td>Advanced NLP
    </td>
    <td>
      Suggested Online Courses:
      <ol>
        <li>Natural Language Processing by National Research University Higher School of Economics, Coursera: <a href="https://www.coursera.org/learn/language-processing" target="_blank">https://www.coursera.org/learn/language-processing</a></li>
      </ol>
    </td>
  </tr>
  
  </tbody>
</table>
</div>


<!-- Content -->
<!-- Note the margin-top:-20px and the <br> serve to make the #schedule hyperlink display correctly (with the h2 header visible) -->
<div class="container sec" id="schedule" style="margin-top:-20px">
<h2>Content</h2>
<p>
The learning material I consider important theoretical background if you want to become involve in NLP with machine learning and/or deep learning.
</p>
<table class="table">
  <colgroup>
    <col style="width:5%">
    <col style="width:25%">
    <col style="width:70%">
  </colgroup>
  <thead>
  <tr class="active">
    <th>Date</th>
    <th>Description</th>
    <th>Learning Materials</th>
  </tr>
  </thead>
  
  <tr>
    <td>1</td>
    <td>Introduction to Regular Expressions and Text Normalization
    </td>
    <td>
      Suggested Reading:
      <ol>
        <li>Jurafsky and Martin (2020): <a href=" https://web.stanford.edu/~jurafsky/slp3/2.pdf" target="_blank">Chapter 2 - Regular Expressions, Text Normalization, and Edit Distance</a> (textbook chapter)</li>
        <li>Dey et al (2009): <a href="https://dl.acm.org/doi/pdf/10.1145/1390749.1390763" target="_blank">Opinion Mining From Noisy Text Data</a> (this paper covers text pre-processing)</li>
      </ol>
    </td>
  </tr>

  <tr>
    <td>2</td>
    <td>Language Modeling
	<br>
	      [<a href="https://web.stanford.edu/~jurafsky/slp3/slides/LM_4.pdf" target="_blank">slides</a>]
    </td>
    <td>
      Suggested Reading:
      <ol>
        <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/3.pdf" target="_blank">Chapter 3 - Language modeling with N-Grams</a> (textbook chapter). Pages 1-16 (plus section 3.6,"The Web and Stupid Backoff")</li>
      </ol>
    </td>
  </tr>

  <tr>
    <td>3</td>
    <td>Text Classification and Sentiment Analysis
	<br>
		  NB [<a href="https://web.stanford.edu/~jurafsky/slp3/slides/7_NB.pdf" target="_blank">slides</a>]<br>
		  Sentiment [<a href="https://web.stanford.edu/~jurafsky/slp3/slides/7_Sent.pdf target="_blank">slides</a>]
    </td>
    <td>
      Suggested Reading - Naive Bayes and Text Classification:
      <ol>
        <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/4.pdf" target="_blank">Chapter 4 - Naive Bayes Classification and Sentiment Classification</a> (textbook chapter). Pages 1-14, sections 4.1 through 4.8</li>
        <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/21.pdf" target="_blank">Chapter 21 - Lexicons for Sentiment, Affect, and Connotation.</a> (textbook chapter). Pages 1-6, plus section 21.6 (page 15)</li>		
		<li>Poria et al (2020): <a href="https://arxiv.org/pdf/2005.00357.pdf" target="_blank">Beneath the tip of the iceberg: Current challenges and new directions in sentiment analysis research</a> (latest review paper on sentiment analysis)</li>			
      </ol>
      Suggested Reading - Logistic Regression:
      <ol>
        <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/5.pdf" target="_blank">Chapter 5 - Logistic Regression</a> (textbook chapter). Pages 1-6, optional: pages 7-17</li>		
      </ol>	  
      Optional for Sentiment Analysis:
      <ol>
		<li><a href="http://collab.hpc.ufs.ac.za/index.php/s/pgfEzZ948XxaiF8" target="_blank">Sentiment Analysis</a> (summary by Kotzé)</li>
      </ol>	  
    </td>
  </tr>
 
 
  <tr>
    <td>4</td>
    <td>Introduction to Neural Networks
    </td>
    <td>
      Suggested Readings:
      <ol>
	    <li><a href="http://jalammar.github.io/visual-interactive-guide-basics-neural-networks/" target="_blank">Visual and Interactive Guide to the Basics of Neural Networks</a> (a tutorial by Jay Alammar)</li>
	    <li><a href="http://jalammar.github.io/feedforward-neural-networks-visual-interactive/" target="_blank">Visual and Interactive Look at Basic Neural Network Math</a> (a tutorial by Jay Alammar)</li>
      </ol>		
    </td>
  </tr>
  
  <tr>
    <td>5</td>
    <td>Word Vectors
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture01-wordvecs1.pdf" target="_blank">slides</a>]
      [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes01-wordvecs1.pdf" target="_blank">notes (lecture 1)</a>]
      [<a href="https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=1" target="_blank">YouTube video 1</a>]	  
      <br><br>
      Gensim word vectors example:
      <br>
      [<a href="http://collab.hpc.ufs.ac.za/index.php/s/tCnaDwyCQz896ZF" target="_blank">python code</a>]
      [<a href="http://web.stanford.edu/class/cs224n/materials/Gensim%20word%20vector%20visualization.html" target="_blank">preview</a>]
    </td>
    <td>
      Suggested Readings:
      <ol>
	    <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/6.pdf" target="_blank">Chapter 6 - Vector Semantics and Embeddings</a> (textbook chapter). Pages 1-7, 17-26, and review 7-16 (should already be familiar)</li>
        <li><a href="http://jalammar.github.io/illustrated-word2vec/" target="_blank">The Illustrated Word2Vec</a> (tutorial by Jay Alammar)</li>		
        <li><a href="http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/" target="_blank">Word2Vec Tutorial - The Skip-Gram Model</a> (tutorial by McCormick)</li>
        <li><a href="https://towardsdatascience.com/representing-text-in-natural-language-processing-1eead30e57d8" target="_blank">Representing text in natural language processing</a> (tutorial by Michel Kana)</li>
        
		<li>Mikolov et al (2013a): <a href="http://arxiv.org/pdf/1301.3781.pdf" target="_blank">Efficient Estimation of Word Representations in Vector Space</a> (original word2vec paper)</li>
        <li>Mikolov et al (2013b): <a href="http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf" target="_blank">Distributed Representations of Words and Phrases and their Compositionality</a> (negative sampling paper)</li>
		<li>Le et al (2014): <a href="https://arxiv.org/abs/1405.4053" target="_blank">Distributed Representations of Sentences and Documents</a> (original doc2vec/paragraphvector paper)</li>
		<li>Enriquez et al (2016): <a href="https://www.sciencedirect.com/science/article/pii/S0957417416304833?via%3Dihub" target="_blank">An approach to the use of word embeddings in an opinion classification task</a> (paper to show how to use word2vec)</li>
      </ol>		
	  Python Code:
      <ol>	
		<li><a href="https://github.com/RaRe-Technologies/gensim" target="_blank">Gensim - Word2Vec Python</a> - Google's word2vec reimplementation written in Python (cython). There are also doc2vec and topic modelling methods.</li>
      </ol>
    </td>
  </tr>

  <tr>
    <td>6</td>
    <td>Word Vectors 2 and Word Senses
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture02-wordvecs2.pdf" target="_blank">slides</a>]
      [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes02-wordvecs2.pdf" target="_blank">notes (lecture 2)</a>]<br>
	  [<a href="http://nlp.stanford.edu/projects/glove/" target="_blank">glove pretrained</a>]
	  [<a href="https://www.youtube.com/watch?v=kEMJRjEdNzM&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=2" target="_blank">YouTube video 2</a>]	  
    </td>
    <td>
      Suggested Readings:
      <ol>
        <li>Pennington et al (2014): <a href="http://aclweb.org/anthology/D/D14/D14-1162.pdf" target="_blank">GloVe: Global Vectors for Word Representation</a> (original GloVe paper)</li>
        <li>Levy et al (2015): <a href="http://www.aclweb.org/anthology/Q15-1016" target="_blank">Improving Distributional Similarity with Lessons Learned from Word Embeddings</a></li>
        <li>Schnabel et al (2015): <a href="http://www.aclweb.org/anthology/D15-1036" target="_blank">Evaluation methods for unsupervised word embeddings</a></li>
        <li>Bonanowki et al (2017): <a href="https://www.mitpressjournals.org/doi/abs/10.1162/tacl_a_00051?mobileUi=0&" target="_blank">Enriching Word Vectors with Subword Infomration</a> (original FastText paper)</li>
		<li>Mikolov et al (2018): <a href="https://arxiv.org/abs/1712.09405" target="_blank">Advances in Pre-Training Distributed Word Representations</a></li>		
      </ol>
      Additional Readings:
      <ol>
      	<li><a href="http://aclweb.org/anthology/Q16-1028" target="_blank">A Latent Variable Model Approach to PMI-based Word Embeddings</a></li>
      	<li><a href="https://transacl.org/ojs/index.php/tacl/article/viewFile/1346/320" target="_blank">Linear Algebraic Structure of Word Senses, with Applications to Polysemy</a></li>
      	<li><a href="https://papers.nips.cc/paper/7368-on-the-dimensionality-of-word-embedding.pdf" target="_blank">On the Dimensionality of Word Embedding.</a></li>
      </ol>
	  Python Code:
      <ol>	  
	    <li><a href="https://blog.keras.io/using-pre-trained-word-embeddings-in-a-keras-model.html" target="_blank">Using pre-trained word embeddings in a Keras model</a> (by Francois Chollet)</li>	  
      </ol>	  
    </td>
  </tr>

  
  <tr>
    <td>7</td>
    <td>Introduction to Neural Network Language Models (LM)
      <br>
    </td>
    <td>
      Suggested Readings:
      <ol>
	  	<li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/7.pdf" target="_blank">Chapter 7 - Neural Networks and Neural Language Models</a> (textbook chapter)</li>
        <li>Bengio (2003): <a href="http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf" target="_blank"> A Neural Probabilistic Language Model</a> (original paper)</li>
      </ol>
      </td>
  </tr>
  
  
  <tr>
    <td>8</td>
    <td>Word Window Classification, Neural Networks
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture03-neuralnets.pdf" target="_blank">slides</a>]
      [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes03-neuralnets.pdf" target="_blank">notes (lectures 3 and 4)</a>]
      [<a href="https://www.youtube.com/watch?v=8CWyBNX6eDo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=3" target="_blank">YouTube video 3</a>]	  
    </td>
    <td>
      Suggested Readings:
      <ol>
        <li><a href="https://collab.hpc.ufs.ac.za/index.php/s/9B4SEXWoq58tDoX" target="_blank">Review of differential calculus</a></li>
      </ol>
      Additional Readings:
      <ol>
      	<li>Collobert et al (2011): <a href="http://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf" target="_blank">Natural Language Processing (Almost) from Scratch</a> (seminal paper)</li>
      </ol>
    </td>
  </tr>
  
  
  <tr>
    <td>9</td>
    <td>Matrix Calculus and Backpropagation
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture04-neuralnets.pdf" target="_blank">slides</a>]
      [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes03-neuralnets.pdf" target="_blank">notes (lectures 3 and 4)</a>]
      [<a href="https://www.youtube.com/watch?v=yLYHDSv-288&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=4" target="_blank">YouTube video 4</a>]		  
    </td>
    <td>
      Suggested Readings:
      <ol>
        <li><a href="http://cs231n.github.io/neural-networks-1/" target="_blank">CS231n notes on network architectures</a> (stanford)</li>
        <li><a href="http://cs231n.github.io/optimization-2/" target="_blank">CS231n notes on backprop</a> (stanford)</li>
        <li><a href="http://www.iro.umontreal.ca/~vincentp/ift3395/lectures/backprop_old.pdf" target="_blank">Learning Representations by Backpropagating Errors</a></li>
        <li><a href="https://collab.hpc.ufs.ac.za/index.php/s/z3cWnWwzJeG9PdE" target="_blank">Derivatives, Backpropagation, and Vectorization</a></li>
        <li><a href="https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b" target="_blank">Yes you should understand backprop</a></li>
      </ol>
      </td>
  </tr>

 
  <tr>
    <td>10</td>
    <td>The probability of a sentence? Recurrent Neural Networks (RNN) and Language Models (LM)
      <br>
	  [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture06-rnnlm.pdf">slides</a>]
      [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes05-LM_RNN.pdf" target="_blank">notes (lecture 5)</a>]
      [<a href="https://www.youtube.com/watch?v=iWea12EAu6U&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=6" target="_blank">YouTube video 6</a>]	  
    </td>
    <td>
      Suggested Readings:
      <ol>
	    <li>Goodfellow et al (2016): <a href="http://www.deeplearningbook.org/contents/rnn.html" target="_blank">Chapter 10 - Sequence Modeling: Recurrent and Recursive Neural Nets</a> (<i>Deep Learning</i> book chapter) - (Sections 10.1 and 10.2)</li>
        <li><a href="http://karpathy.github.io/2015/05/21/rnn-effectiveness/" target="_blank">The Unreasonable Effectiveness of Recurrent Neural Networks</a> (blog post overview)</li>
        <li><a href="http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/" target="_blank">Recurrent Neural Networks Tutorial</a> (practical guide by Denny Britz)</li>
		<li><a href="http://norvig.com/chomsky.html" target="_blank">On Chomsky and the Two Cultures of Statistical Learning</a></li>
      </ol>
    </td>
  </tr>
 
 
  <tr>
    <td>11</td>
    <td>Vanishing Gradients and Fancy RNNs
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture07-fancy-rnn.pdf" target="_blank">slides</a>]
      [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes05-LM_RNN.pdf" target="_blank">notes (lecture 5)</a>]
      [<a href="https://www.youtube.com/watch?v=QEw0qEa0E50&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=7" target="_blank">YouTube video 7</a>]	  
    </td>
    <td>
      Suggested Readings:
      <ol>
        <li>Goodfellow et al (2016): <a href="http://www.deeplearningbook.org/contents/rnn.html" target="_blank">Chapter 10 - Sequence Modeling: Recurrent and Recursive Neural Nets</a> (<i>Deep Learning</i> book chapter) - (Sections 10.3, 10.5, 10.7-10.12)</li>
        <li><a href="http://ai.dinfo.unifi.it/paolo//ps/tnn-94-gradient.pdf" target="_blank">Learning long-term dependencies with gradient descent is difficult</a> (one of the original vanishing gradient papers)</li>
        <li><a href="https://arxiv.org/pdf/1211.5063.pdf" target="_blank">On the difficulty of training Recurrent Neural Networks</a> (proof of vanishing gradient problem)</li>
        <li><a href="http://colah.github.io/posts/2015-08-Understanding-LSTMs/" target="_blank">Understanding LSTM Networks</a> (blog post overview by Colah)</li>
      </ol>
    </td>
  </tr>

  
  <tr>
    <td></td>
    <td>Machine Translation, Seq2Seq and Attention
    </td>
    <td>
      Not covering it (currently outside scope of research interest)<br>
	  Suggested Readings:
      <ol>
        <li><a href="http://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/" target="_blank">Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)</a> (tutorial by Jay Alammar)</li>
      </ol>		
    </td>
  </tr>

  
 <tr>
    <td>12</td>
    <td>Question Answering and an introduction to Transformer architectures<br>
    [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture10-QA.pdf" target="_blank">slides</a>]
    [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes07-QA.pdf" target="_blank">notes</a>]
	[<a href="https://www.youtube.com/watch?v=yIdF-17HwSk&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=10" target="_blank">YouTube video 10</a>]	
  </td>
    <td>
      Suggested Readings:
      <ol>
        <li><a href="https://arxiv.org/abs/1706.03762.pdf"                target="_blank">Attention Is All You Need</a> (seminal paper)</li>
        <li><a href="https://jalammar.github.io/illustrated-transformer/" target="_blank">The Illustrated Transformer</a> (tutorial by Jay Alammar)</li>
        <li><a href="https://jalammar.github.io/illustrated-gpt2/"        target="_blank">The Illustrated GPT-2 (Visualizing Transformer Language Models)</a> (tutorial by Jay Alammar)</li>		
        <li><a href="https://ai.googleblog.com/2017/08/transformer-novel-neural-network.html" target="_blank">Transformer (Google AI blog post)</a></li>
        <li><a href="https://arxiv.org/pdf/1607.06450.pdf" target="_blank">Layer Normalization</a></li>
        <li><a href="https://arxiv.org/pdf/1802.05751.pdf" target="_blank">Image Transformer</a></li>
        <li><a href="https://arxiv.org/pdf/1809.04281.pdf" target="_blank">Music Transformer: Generating music with long-term structure</a></li>
      </ol>
    </td>
  </tr>

  
  <tr>
    <td>13</td>
    <td>CNNs for NLP <br>
    [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture11-convnets.pdf" target="_blank">slides</a>]
    [<a href="http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes08-CNN.pdf" target="_blank">notes</a>]
	[<a href="https://www.youtube.com/watch?v=EAJoRA0KX7I&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=11" target="_blank">YouTube video 11</a>]		
    </td>
    <td>
      Suggested Readings:
      <ol>
	    <li>Goodfellow et al (2016): <a href="http://www.deeplearningbook.org/contents/convnets.html" target="_blank">Chapter 9 - Convolutional Networks (CNN)</a> (<i>Deep Learning</i> book chapter)</li>
        <li>Kim (2014): <a href="https://arxiv.org/abs/1408.5882.pdf" target="_blank">Convolutional Neural Networks for Sentence Classification</a></li>
        <li>Hinton et al (2012): <a href="https://arxiv.org/abs/1207.0580" target="_blank">Improving neural networks by preventing co-adaptation of feature detectors</a></li>
        <li>Kalchbrenner et al (2014): <a href="https://arxiv.org/pdf/1404.2188.pdf" target="_blank">A Convolutional Neural Network for Modelling Sentences</a></li>
      </ol>
	  Python Code:
      <ol>	  
	    <li><a href="https://github.com/cmasch/cnn-text-classification" target="_blank">Python CNN (Keras) implementation of Kim (2014)'s paper</a></li>	  
      </ol>
    </td>
  </tr>

  
  <tr>
    <td>14</td>
    <td>Contextual Word Representations: BERT
    <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/Jacob_Devlin_BERT.pdf" target="_blank">slides</a>]
	  [<a href="https://www.youtube.com/watch?v=S-CspeZ8FHc&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=13" target="_blank">YouTube video 13</a>]	  	  
    <td>Suggested readings:
      <ol>
        <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/10.pdf" target="_blank">Chapter 10 - Encoder-Decoder Models, Attention, and Contextual Embeddings</a> (textbook chapter)</li>
        <li>Devlin et al (2018) <a href="https://arxiv.org/pdf/1810.04805.pdf" target="_blank">BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding</a> (original BERT paper)
        </li>
	  	<li><a href="http://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/" target="_blank">A Visual Guide to Using BERT for the First Time</a> (tutorial by Jay Alammar)</li>		
      </ol>
    </td>
  </tr>
  
  
  <tr>
    <td>15</td>
    <td>Modeling contexts of use: Contextual Representations and Pretraining. ELMo and BERT.
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture14-contextual-representations.pdf" target="_blank">slides</a>]
	  [<a href="https://www.youtube.com/watch?v=5vcj8kSwBCY&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=14" target="_blank">YouTube video 14</a>]	  
    </td>
    <td>Suggested readings:
      <ol>
        <li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/10.pdf" target="_blank">Chapter 10 - Encoder-Decoder Models, Attention, and Contextual Embeddings</a> (textbook chapter)</li>
	    <li><a href="http://www.davidsbatista.net//blog/2018/12/06/Word_Embeddings/" target="_blank">Language Models and Contextualised Word Embeddings</a> (tutorial by David S. Batista)</li>
		<li><a href="http://jalammar.github.io/illustrated-bert/" target="_blank">The Illustrated BERT, ELMo, and co.</a> (tutorial by Jay Alammar)</li>
	    <li>Peters et al (2018): <a href="http://aclweb.org/anthology/N18-1202" target="blank">Deep Contextualized Word Representations</a> (original ELMo paper)</li>
        <li>Devlin et al (2018) <a href="https://arxiv.org/pdf/1810.04805.pdf" target="_blank">BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding</a> (original BERT paper)		
	    <li>Smith (2019): <a href="https://arxiv.org/abs/1902.06006.pdf" target="blank">Contextual Word Representations: A Contextual Introduction</a></li>		
      </ol>
    </td>
  </tr>
  
  
  <tr>
    <td>16</td>
    <td>
      Natural Language Generation
      <br>
	  [<a href="http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture15-nlg.pdf" target="_blank">slides</a>]
	  [<a href="https://www.youtube.com/watch?v=4uG1NMKNWCU&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=15"  target="_blank">YouTube video 15</a>]
    </td>
    <td>
    Suggested readings:
      <ol>
        <li><a href="https://arxiv.org/abs/1904.09751.pdf" target="_blank">The Curious Case of Neural Text Degeneration</a></li>
        <li><a href="https://arxiv.org/abs/1704.04368.pdf" target="_blank">Get To The Point: Summarization with Pointer-Generator Networks</a></li>
        <li><a href="https://arxiv.org/abs/1805.04833.pdf" target="_blank">Hierarchical Neural Story Generation</a></li>
        <li><a href="https://arxiv.org/abs/1603.08023.pdf" target="_blank">How NOT To Evaluate Your Dialogue System</a></li>
      </ol>
    </td>
  </tr>

		
  <tr>
    <td>17</td>
    <td>
      Conversational Agents (aka "Chatbots")
      <br>
    </td>
    <td>
    Suggested readings:
      <ol>
		<li>Jurafsky and Martin (2020): <a href="https://web.stanford.edu/~jurafsky/slp3/26.pdf" target="_blank">Chapter 26 - Dialogue Systems and Chatbots</a> (textbook chapter)</li>
		<li>Kottur et al (2017): <a href=" https://www.ijcai.org/proceedings/2017/0521.pdf" target="_blank">Exploring Personalized Neural Conversational Models</a></li>		
		<li>Gao et al (2018): <a href="http://arxiv.org/abs/1809.08267" target="_blank">Neural Approaches to Conversational AI</a></li>		
      </ol>
    </td>
  </tr>
  
  
  <tr class="warning">
    <td>18</td>
    <td>Python review session
      <br>
      [<a href="https://collab.hpc.ufs.ac.za/index.php/s/P4Tta3s9JNcBcjj" target="_blank">slides</a>]
      [<a href="https://collab.hpc.ufs.ac.za/index.php/s/4HzQCZExeqWNfn8" target="_blank">code</a>]
    </td>
    <td>
      Use these resources to review your Python Programming skills
    </td>
  </tr>

  
  <tr class="warning">
    <td>19</td>
    <td>
      Practical Tips for NLP Projects
      <br>
      [<a href="http://web.stanford.edu/class/cs224n/readings/final-project-practical-tips.pdf" target="_blank">notes</a>]
    </td>
    <td>
      Suggested Readings:
      <ol>
        <li><a href="https://www.deeplearningbook.org/contents/guidelines.html" target="_blank">Practical Methodology</a> (<i>Deep Learning</i> book chapter)</li>
      </ol>
    </td>
  </tr>

  
  </tbody>
</table>
</div>

<!-- jQuery and Bootstrap -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
</body>

</html>
