# ai6102-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [AI6102 Assignment 1 Solved](https://www.ankitcodinghub.com/product/ai6102-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95330&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AI6102 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Question 1: Consider a multi-class classification problem of C classes. Based on the parametric forms of the conditional probabilities of each class introduced on the 54th Page (“Extension to Multiple Classes”) of the lecture notes of L4, derive the learning procedure of logistic regression for multi-class classification problems.

Hint: define a loss function by borrowing an idea from binary classification, and derive the gradient descent rules to update {w(c)}’s.

Question 2: This is a hands-on exercise to use the LinearSVC API of scikit-learn1 to train a linear SVM on a binary classification dataset. The details of instructions are described as follows.

1. Download the a5a dataset from the LIBSVM Dataset page.

This is a preprocessed dataset of the Adult dataset in the UCI Irvine Machine Learning Repository2, which consists of a training set (available here) and a test set (available here).

Each file (the train set or the test set) is a text format in which each line represents a labeled data instance as follows:

label index1:value1 index2:value2 …

where “label” denotes the class label of each instance, “indexT” denotes the T-th feature, and valueT denotes the value of the T-th feature of the instance. This is a sparse format, where only non-zero feature values are stored for each

1Read Pages 65-66 of the lecture notes of L5 for reference 2The details of the original Adult dataset can be found here.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
instance. For example, suppose given a data set, where each data instance has 5 dimensions (features). If a data instance whose label is “+1” and the input data instance vector is [2 0 2.5 4.3 0], then it is presented in a line as

+1 1:2 3:2.5 4:4.3

Hint: sciki-learn provides an API (“sklearn.datasets.load svmlight file”) to load such a sparse data format. Detailed information is available here.

2. Givenasetof5candidatevaluesoftheparameterCinLinearSVC,{0.01,0.1,1,10,100}, use 3-fold cross-validation to determine which is the best value of C in terms of classification accuracy on the a5a training set. Generate the following table

based on your experimental results. Note that for all the other parameters in LinearSVC, you can simply use the default values. If you set them to be other

values, specify them in your submitted PDF file.

Table 1: The 3-fold cross-validation results of varying values of C in LinearSVC on the a5a training set (in accuracy).

C=0.01 C=0.1 C=1 C=10 C=100 Accuracy of linear SVMs ? ? ? ? ?

Hint: there are no specific functions of cross-validation for SVMs in sciki-learn. However, you can use some APIs under the category “Model Selection → Model validation” to implement it. Some examples can be found here.

3. Set the parameter value of C to the best one found in the previous step, use Lin- earSVC to train a model using the whole a5a training set, and make predictions on the a5a test set. List the result in terms of accuracy in the following table, where c∗ is the best value of C based on cross-validation in the previous step.

Table 2: Test results of LinearSVC with the best value of C on the a5a test set (in accuracy).

C = c∗ Accuracy of linear SVMs ?

Question 3 (optional): Using the kernel trick introduced in L5 to extend the regular- ized linear regression model to solve nonlinear regression problems. Derive a closed- form solution.

2

</div>
</div>
</div>
