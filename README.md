# it5001-lab-5b-map-filter-reduce-solved
**TO GET THIS SOLUTION VISIT:** [IT5001 Lab 5b-Map, Filter, Reduce Solved](https://www.ankitcodinghub.com/product/it5001-week-5b-map-filter-reduce-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119262&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IT5001 Lab 5b-Map, Filter, Reduce Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Part 1 Map and Filter

In this exercise, try to come up with the answer without using IDLE/Python first. If there is an error, specify the cause and type of the error. Then type the expressions into IDLE to verify your answers. The objective is for you to understand why and how they work.

L = [9,2,1,3,4,5,6]

Expressions Output

map(lambda x: x &gt; 2, L)

list(filter(lambda x:x&gt;2,L))

tuple(map(lambda x: ‘o’ if x%2 else ‘e’,L))

list(filter(lambda x: ‘o’ if x%2 else ‘e’,L))

list(map(str,list(filter(lambda x:x%2,L))))

str(list(filter(lambda x:x&gt;30,map(lambda x:x*x,L))))

Part 2 Scale/Square Tuples

&gt;&gt;&gt; map(lambda x:x*x, L)

[81, 4, 1, 9, 16, 25, 36]

&gt;&gt;&gt; map(lambda x:x*2, L)

[18, 4, 2, 6, 8, 10, 12]

Part 3 Sum Digits Square

We solved the “Sum Digits” problem of writing function sum(n) which returns the sum of all the digits in n before. Write an alternative implementation sds(n) using our version of map() and built-in function sum().

How about “Sum Digit Square”? Write a function sdss(n) which returns the sum of the square of every digit in n.

Part 4 Taylor Series

The Taylor series is an infinite sum of many terms, e.g.

How do we use our version of map() and sum() to compute the above without using loops or recursion?

Part 5 Reduce

def reduce(f, seq): if not seq:

return seq

first = seq[0] for i in seq[1:]:

first = f(first,i)

return first

Predict the output of the following function call:

reduce(lambda x,y:x+y,[1,2,3])
