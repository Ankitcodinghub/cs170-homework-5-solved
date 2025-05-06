# cs170-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [CS170 Homework 5 Solved](https://www.ankitcodinghub.com/product/cs170-homework-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96691&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS170 Homework 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
2 Arbitrage

Shortest-path algorithms can also be applied to currency trading. Suppose we have n cur- rencies C = {c1, c2, . . . , cn}: e.g., dollars, Euros, bitcoins, dogecoins, etc. For any pair i, j of currencies, there is an exchange rate ri,j: you can buy ri,j units of currency cj at the price of one unit of currency ci. Assume that ri,i = 1 and ri,j ≥ 0 for all i, j.

The Foreign Exchange Market Organization (FEMO) has hired Oski, a CS170 alumnus, to make sure that it is not possible to generate a profit through a cycle of exchanges; that is, for any currency i ∈ C, it is not possible to start with one unit of currency i, perform a series of exchanges, and end with more than one unit of currency i. (That is called arbitrage.)

More precisely, arbitrage is possible when there is a sequence of currencies ci1,…,cik such that ri1,i2 · ri2,i3 · · · · · rik−1,ik · rik,i1 &gt; 1. This means that by starting with one unit of currency ci1 and then successively converting it to currencies ci2 , ci3 , . . . , cik and finally back to ci1 , you would end up with more than one unit of currency ci1 . Such anomalies last only a fraction of a minute on the currency exchange, but they provide an opportunity for profit.

We say that a set of exchange rates is arbitrage-free when there is no such sequence, i.e. it is not possible to profit by a series of exchanges.

</div>
</div>
<div class="layoutArea">
<div class="column">
(a)

(b)

3

</div>
<div class="column">
Give an efficient algorithm for the following problem: given a set of exchange rates ri,j which is arbitrage-free, and two specific currencies s,t, find the most advantageous sequence of currency exchanges for converting currency s into currency t.

Hint: represent the currencies and rates by a graph whose edge weights are real numbers.

Oski is fed up of manually checking exchange rates, and has asked you for help to write a computer program to do his job for him. Give an efficient algorithm for detecting the possibility of arbitrage. You may use the same graph representation as for part (a).

Money Changing.

</div>
</div>
<div class="layoutArea">
<div class="column">
Fix a set of positive integers called denominations x1, x2, . . . , xn (think of them as the integers 1, 5, 10, and 25). The problem you want to solve for these denominations is the following:

</div>
</div>
<div class="layoutArea">
<div class="column">
Given an integer A, express it as

</div>
<div class="column">
n

A = 􏰀aixi i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
for some nonnegative integers a1, . . . , an ≥ 0. 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
l (a) Under which conditions on the denominations xi are you able to do this for all integers

A &gt; 0?

(b) Suppose that you want, given A, to find the nonnegative ai’s that satisfy A = 􏰅ni=1 aixi, and such that the sum of all ai’s is minimal —that is, you use the smallest possible number of coins. Define a greedy algorithm for this problem. (Your greedy algorithm may not necessarily solve the problem, i.e., it may give a suboptimal answer on some inputs)

(c) Show that the greedy algorithm finds the optimum ai’s in the case of the denominations 1, 5, 10, and 25, and for any amount A.

(d) Give an example of a denomination where the greedy algorithm fails to find the optimum ai’s for some A. (Do you know of an actual country where such a set of denominations exists?)

4 Bounded Bellman-Ford (Optional)

You may submit your solution to this problem if you wish it to be graded, but it will be worth no points.

Modify the Bellman-Ford algorithm so that given a graph G, nodes s and t, and an in- teger k, it finds the weight of the lowest-weight path from s to t with the restriction that the path must have at most k edges.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
