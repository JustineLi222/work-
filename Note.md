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
<p>The goal of curve fitting</p>

<p>Purpose of interpolation:</p>
<p>creating a curve that fits all data points</p>
<p>predict what other data point will be by extrapolation</p>

<h3>how curve fitting find the best fit?</h3>
https://www.youtube.com/watch?v=peBOquJ3fDo
https://github.com/lukepolson/youtube_channel/blob/main/Python%20Tutorial%20Series/curvefit1.ipynb
<u1>
       <li>One way of doing this is to minimize 
square of different between the estimated value and orginal y value by adjusting the parameters in beta. 
              This is called the method of least squares
       </li>
       <li>using maximum likelihood function to find the best fit for beta</li>
</u1>
<p>popt: p optimal</p>
<p>pcov: p covariance ,it returns a matrix</p>
<p>it gives an estimate of error of estimated parameters</p>
<p>the diagonal value of matrix is correspond to each parameters</p>
<p>if one of the value is very large,it means the chances of error is large so the paramter is not useful because changing the value of that paramter don't have great effect on the model</p>
<p>defining the region of curve fitting</p>
<p>x_data = x_stuff[(x_stuff>725) & (x_stuff<850)]
y_data = y_stuff[(x_stuff>725) & (x_stuff<850)]</p>
<h1>6/7/2023</h1>

<h2>linear regression</h2>
<p>use it to find coefficient of a linear curve</p>
<p>y=a+bx</p>
<p>b=r*sy/sx</p>
<p>s is standard deviation and r is Pearson's correlation coefficient</p>
<p>a=mean of y - mean of x multiple b</p>

<h2>Some basics of javscript</h2>
<p>all things in javascript can be object</p>
<p>an object has property and method</p>
<p>property has an value e.g car:"red"</p>
<p>method just like an function</p>
<p>something that is not an object:numbers,null,string,boolean</p>
<p>but you can still use length function to check the string length as javascript will turn string into an object temporilary </p>
<h3>Why creating an object?</h3>
<p>more organized</p>
<h3>Spread operator</h3>
<p>add existing array into new array</p>

<h2>7/7</h2>
<h2>M5stickC</h2>
<p>IoT development platform</p>
<p>based on esp32</p>
<h3>applications</h3>
<ul>
       <li>watches</li>
       <li>Gopro
       <p>use to take a photo or switch to video mode</p>
       </li>
       <li>remote controller for tv</li>
</ul>
<p>can connected to internet by WiFi</p>

<h2>10/7</h2>
<h3>Swift</h3>
<p>Assets stores color and images </p>
<h4>Types</h4>
<p>Int</p>
<p>e.g var highscore: Int = 0</p>
<p>Double</p>
<p>has at least 15 d.p</p>
<p>Float</p>
<p>at most 6 d.p</p>
<p>String</p>
<p>e.g var myname: String= "peter"</p>
<p>Bool</p>
<p>e/g var isDarkMoodeOn: Bool=true</p>
<p>you can create your custom type which is class</p>
<h4>Type inference</h4>
<p>just like python</p>
<p>array</p>
<p>e.g var ages=[1,2,3]</p>
<p>you can define a empty int array.
var ages:[Int]=[]
</p>
<p>add item to the end:  ages.append()</p>
<p>add item to anywhere you want: ages.insert(value you want to add, at: index)</p>

<p>ages.count to find the length of array</p>
<p>? / optional means it can be no value and nil</p>
<p>Sets</p>
<p>unordered,no duplicates</p>
<p>faster insertion,removal and lookup than array</p>
<p>var ageSet : Set<Int> =[1,2,3]</p>
<p>can create a set based on the array by Set()</p>
<p>conform hashable</p>
<p>the set can find the value in constant time using hash value</p>
<p>using ageSet.contains(value you want) to check whether it is in the set</p>
<p>ageSet.insert(value) no need specify position cuz it is unordered </p>
<p>Dictionaries</p>
<p>key:value </p>
<pre><p>declare dictionary:   
       let devices: [String:String]=[
       "phone": "iPhoneX",
       "laptop": "Macbook pro"
       ]  
      // key is always string</p></pre>

<h4>Functions</h4>
<p>func funcname(){}</p>
<p>func function2(hi:Int)->Int. it is going to return a Int</p>
<p>0...25 means 0 to 25</p>
<p>0..<25 means 0 tp 24</p>
<h4>enum</h4>
<p>stand for enumeration</p>
<p>a group of values that are related</p>
<pre>
       enum Phone{
              case iPhone11Pro
              case iPhoneSE
       }
</pre>
<p>use dot to access item inside e.g .iPhone11Pro</p>
<p>We use enum because it can reduce error due to typo</p>
<p>You can also give enum a raw value</p>
<pre>
       enum Phone:String{
              case iPhone14: "This is will be my next Phone"
              case iPhoneSE: "small"
       }
</pre>
<p>extract the raw value by Phone.iPhone14.rawValue</p>
<h4>Switch statement</h4>
<pre>
       switch(Phone){
       case .iPhone14:
              print("1")
       case .iPhoneSE:
              print("2")
       }
</pre>
<h4>Operators</h4>
<p>division: if calculating fraction,need to change both of var to double/float</p>
<h4>Optionals</h4>
<p>handles the absence of values</p>
<p>declare optionals: var d:String?</p>
<p>unwrap optionals: before you access the function</p>
<p>use ! at the end of the var to unwrap the optional and get the value</p>
       <pre>
              if present!=nil {
                     print(present!.surprise())
              }
       </pre>
<p>optional binding</p>
<pre>
       if let actualpresent=present{
              print(actualpresent.surprise())
       }
</pre>
<p>if it is nil ,it going to pass through if statement</p>
<p>unwrapped variable: var d:String!</p>
<p>xcode will not check unwrapped variable is nil or not so the program will crash more possibily.</p>

