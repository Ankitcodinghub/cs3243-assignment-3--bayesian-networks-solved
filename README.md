# cs3243-assignment-3--bayesian-networks-solved
**TO GET THIS SOLUTION VISIT:** [CS3243 Assignment 3- Bayesian networks Solved](https://www.ankitcodinghub.com/product/cs3243-assignment-3-bayesian-networks-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114603&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3243  Assignment 3- Bayesian networks Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Important: Read all the instructions below carefully before you start working on the assignment, and before you make a submission.

• You must do this assignment in groups of two only. Please write the names and matriculation numbers of your team members in the code file you submit.

• Sign up your group on LumiNUS: Class and Groups → Class Groups – This time, you can form groups with anyone in the module.

– i.e., there is no tutorial restriction on group forming.

– Group size is strictly 2 students (No groups of 3 or individuals submissions are allowed.

Reason: It helps us to manage logistics and grading).

• Submission instructions (These instructions are different from Assignment 1 and Assignment 2, please pay attention)

– You need to submit only the python code file on LumiNUS.

– You don’t have to write any report this time!

– Make only one submission (i.e., one python file) per group.

– File names:

The code filename should be b net A3 xx.py

E.g. b net A3 02.py (note that it is 02 and not 2).

• Points will be deducted for not following the instructions, including the naming convention. Please follow the file naming convention closely.

• Kindly check that the submitted code will be able to run on SoC’s Sunfire account. We will be using Sunfire (our UNIX server) to evaluate all submissions.

1 Submission

Your submissions should contain only ONE python code file (please name it according to the instructions above). No report for this assignment!

1.1 Code

• Your answer should be returned by the infer() function. However, do note that you need to construct() the network first!

• Executable: If your program can not be executed, you will get 0 for your code components.

• Correctness: Please make sure your algorithm logic is correct. You will lose mark significantly if you can not pass our test cases.

• Timing: We will time your solution and use the timing information as one of the components in grading.

Figure 1: Bayesian network for earthquake problem.

2 Grading

• We will be grading your implementation based on two criteria—correctness and efficiency.

• Each criteria carries the same weightage (i.e., Correctness: 5 points and Efficiency: 5 points).

3 Problem Statement

In this assignment, you are required to implement a Bayesian network, given the structure in the form of variables and dependencies. Additionally, you need to determine the joint probability given the prior and conditional probabilities. Take care that you don’t do unnecessary calculations in your code.

4 Logistics – Input/Output

4.1 Example problem

Consider the Bayesian network given in Figure 1

4.2 Input

Input is provided as a set of JSON files as follows:

• structure.json

– Contains the variables and dependencies.

– For instance the BN in Figure 1 is encoded as follows.

– Each key in the variables dictionary (e.g., Burglary) corresponds to a node in the BN, with the values corresponding to the key representing the domain. Hence, in this case, the domain comprises Boolean values.

– Each key in the dependencies dictionary (e.g., Alarm) corresponds to a node in the BN, with the values representing the dependencies. Hence, you read the first entry as Alarm depends on Burglary and Earthquake.

– The entire structure is specified in the similar manner (i.e., no hidden nodes or traps will be laid!).

– You are required to construct the BN using this information.

• values.json

– Contains the prior and conditional probabilities associated with the nodes.

– For instance the probability values associated with the nodes in the BN above are encoded as follows.

{

“prior_probabilities”: {

“Burglary”: {

“True”: 0.01,

“False”: 0.99

},

“Earthquake”: {

“True”: 0.02,

“False”: 0.98

}

},

“conditional_probabilities”: {

“Alarm”: [

{

“Burglary”: “True”,

“Earthquake”: “True”,

“own_value”: “True”, “probability”: 0.95

},

{

“Burglary”: “True”,

“Earthquake”: “True”,

“own_value”: “False”, “probability”: 0.05

},

{

“Burglary”: “False”,

“Earthquake”: “True”,

“own_value”: “True”, “probability”: 0.29

},

{

“Burglary”: “False”,

“Earthquake”: “True”,

“own_value”: “False”, “probability”: 0.71

},

{

“Burglary”: “True”,

“Earthquake”: “False”,

“own_value”: “True”, “probability”: 0.94

},

{

“Burglary”: “True”,

“Earthquake”: “False”,

“own_value”: “False”,

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47

“probability”: 0.06

},

{

“Burglary”: “False”,

“Earthquake”: “False”,

“own_value”: “True”,

“probability”: 0.001

},

{

“Burglary”: “False”,

“Earthquake”: “False”,

“own_value”: “False”,

“probability”: 0.999

}

],

“JohnCalls”: [

{

“Alarm”: “True”,

“own_value”: “True”, “probability”: 0.9

},

{

“Alarm”: “True”,

“own_value”: “False”, “probability”: 0.1

},

{

“Alarm”: “False”,

“own_value”: “True”, “probability”: 0.05

},

{

“Alarm”: “False”,

“own_value”: “False”,

“probability”: 0.95

}

],

“MaryCalls”: [

{

“Alarm”: “True”,

“own_value”: “True”, “probability”: 0.7

},

{

“Alarm”: “True”,

“own_value”: “False”, “probability”: 0.3

},

{

“Alarm”: “False”,

“own_value”: “True”, “probability”: 0.01

},

{

“Alarm”: “False”,

“own_value”: “False”,

“probability”: 0.99

}

48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 64 65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95 96 97 98 99

100 101 102 103 104 105

– The keys prior probabilities and conditional probabilities are self explanatory.

– You read the Prior probabilities as: Probability of Burglary happening is 0.01 and not happening is 0.99.

– You read the Conditional probabilities as: P (Alarm = T | Burglary = T,Earthquake = T) = 0.95, P (Alarm = T | Burglary = F,Earthquake = T) = 0.29 and so on. (own value refers to the value the variable takes. In the above, own value of Alarm is True).

– Similarly, P (JohnCalls = F | Alarm = T) = 0.1.

• queries.json

– Contains a list of queries that we are interested in.

– For instance, the sample queries could be encoded as follows:

{ “index” : 1,

“given” : {“Alarm” : “False”},

“tofind” : {“MaryCalls” : “True”}

},

{ “index” : 2,

“given” : {“Burglary”: “False”, “Earthquake”: “True”},

} “tofind” : {“Alarm”: “False”}

4 5 6 7 8 9

10

– The index key refers to the query number. It is important to use the same index number for the answer.

– You read the first query as “Find P (MaryCalls = T | Alarm = F)”.

4.3 Output

• Your submission should infer the probability of the given query.

• The output should be returned by the infer() function in the form of a list of dictionaries.

• E.g., For the queries above, the answer should be returned as follows.

[ { “index” : 1, “answer” : 0.01 },

] { “index” : 2, “answer” : 0.71 }

1 2 3 4
