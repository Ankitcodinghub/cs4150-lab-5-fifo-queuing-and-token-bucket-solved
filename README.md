# cs4150-lab-5-fifo-queuing-and-token-bucket-solved
**TO GET THIS SOLUTION VISIT:** [CS4150 Lab 5-FIFO queuing and Token bucket Solved](https://www.ankitcodinghub.com/product/cs4150-lab-5-fifo-queuing-and-token-bucket-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94553&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4150 Lab 5-FIFO queuing and Token bucket Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Write a C program called “shape” that implements token bucket based traffic shaping. This function should have two input arguments. The first argument is an integer and denotes the size of token bucket, whereas the second argument is the rate at which tokens are falling into the token bucket. The file “arrivals.txt” contains the list of packets arrivals. Each packet arrival is denoted by a line in this file as “X Y Z”, where X is arrival time, Y is packet ID, and Z is packet length. You should be able invoke your program as follows:
<pre>  ./shape 250 4.0 &lt; arrivals.txt
</pre>
The above invocation should shape the traffic in the file “arrivals.txt” using a token bucket of

capacity 250 and rate 4.0. The output of the above invocation should be, for each packet, “U

V W” (without quotes), where U is the transmission time of the packet (“%.2f” format), V

is the packet ID (“%d” format), and W is length of the packet (“%d” format). Your program

will be evaluated for 6 test cases by running the script “./testShape”, and 5 point will be

awarded for each test case passed. [30]
</li>
<li>Write a C program called “fifo” that implements a finite capacity FIFO queue. This function should have two input arguments. The first argument is an integer and denotes the buffer size (including the packet being served / HOL packet), whereas the second argument is the constant rate at which data is pushed to the output line of the queue. The HOL packet is held in buffer until it is completely transmitted. The file “arrivals.txt” contains the list of packets arrivals. Each packet arrival is denoted by a line in this file as “X Y Z”, where X is arrival time, Y is packet ID, and Z is packet length. You should be able invoke your program as follows:
<pre>  ./fifo 250 4.0 &lt; arrivals.txt
</pre>
The above invocation should simulate the traffic in the file “arrivals.txt” passing through a

FIFO queue of capacity 250 and output rate 4.0. The output of the above invocation should

be, for each packet, “U V W” (without quotes), where U is the transmission completion time

of the packet (“%.2f” format), V is the packet ID (“%d” format), and W is length of the

packet (“%d” format). Your program will be evaluated for 6 test cases by running the script “./testFifo”, and 5 point will be awarded for each test case passed
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3. The traffic in file “arrivals.txt” is first passed though a token bucket of capacity 500 and rate x, and then passed through a FIFO queue of capacity 1000 and rate 10.0. Write a C code/ bash script to find the largest x (upto 6 decimal places) which ensures that no packets are dropped by the FIFO queue?

</div>
</div>
<div class="layoutArea">
<div class="column">
End of paper

</div>
</div>
</div>
