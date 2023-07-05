# <h1>work</h1>


4/7/2023

<h2>1.Tensor Flow</h2>

https://www.youtube.com/watch?v=i8NETqtGHms
<br>
deal with linear alegbra and stat
multi dimension array
run on the browser with tensorflow.js

The model that TensorFlow creates is like a set of instructions for the computer that tell it what to look for and how to do things. Once the model is created, we can use it to make the computer do things like recognize pictures or translate languages.

<h2>2.Signal to noise ratio</h2>
https://www.youtube.com/watch?v=MSKYeWfsNO0
<br>
2.1Power Signal to noise ratio


<p>equation:avg signal power/avg noise power</p>
2.2Voltage
<p>rms signal voltage/rms noise voltage</p>
<p>rms: root mean squared</p>
<p>SNR power=(SNR voltage)^2</p>
<p>express in terms of Db</p>
<b>10log(SNR power) for power</b><br>
<b>20log(SNR voltage) for voltage</b>


<h2>Random Forest</h2>
<p>Model ensembing</p>
<p>increase test accuracy and lower the cost using decision tree</p>
<p>train bunch of decision tree to form a forest</p>
<p>take the most frequency result of decision trees as final prediction</p>
<p>regression:average the result of decision tree</p>
<p>uncorrelatedness increase the accuracy</p>
<p>uncorrelating tree method:</p>
<ol>
       <li>Bootstrapping
              <p>sampling several small portion of the large dataset  </p>
       </li>
       <li>Bootstrap aggregrating</li>
       <li>Feature randomness
              <p>limit the feature that the tree can split on</p>
       </li>
       
</ol>
<p>https://www.youtube.com/watch?v=cIbj0WuK41w</p>

<h2>Decision tree</h2>
<p>https://www.youtube.com/watch?v=cIbj0WuK41w</p>
<p>Repeating asking true or false question to split the data into purest subgroups</p>
<pre><p>  
       supervised
            |
      |------------|
Regression     classification
</p></pre>
<p>recursion until the leaf node ,the result of prediction can be found in leaf node</p>
<p>After comparing each possible variable,the decision tree picks the one that leads to the purest branches.</p>
<p>Keep on branching until reach the purest state or max depth=3 of the tree.</p>
<p>we limit the depth of the tree to avoid overfitting.</p>
<p>learn quirks from a specific dataset and make it harder to predict the whole population.</p>

<h2>Scipy</h2>
<p>first create a func for predicted equation.the first argument must be x</p>
<p>then define x and y data point using np.array</p>

<h1>5/7</h1>
<h2>Train scipy to find the coefficient of the curve</h2>
<h2>open virutal env</h2>
<p>avoid conflicts of different package in different folder</p>
<pre>python3 -m venv .env
source .env/bin/activate</pre>
<h2>find peaks in graph</h2>
https://www.youtube.com/watch?v=75mdKyA76i8
<h2>freeze requirement</h2>
<p>open a new file to store installed package</p>
<h2>curve fitting</h2>




