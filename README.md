# hy330-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [HY330 Assignment 2 Solved](https://www.ankitcodinghub.com/product/hy330-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91846&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;HY330 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
General Information

The goal of this assignment is to become familiar with different modulation schemes, the impact of noise and frequency offset, as well as pulse shaping. Furthermore some up- sampling issues are investigated to better understand the challenges of sampling theo- rem.

Exercise 1

In this exercise you will investigate the accuracy of the three different up-sampling/interpolation schemes proposed by students during the lectures. Consider the case of doubling the sam-

ple rate, thus for each input sample two are output.

<ol>
<li>Build the logic of the three schemes in a single flowgraph called lab2_1.grc:
<ol>
<li>(a) &nbsp;For each input sample a second sample is produced with zero amplitude (zero
padding).
</li>
<li>(b) &nbsp;For each input sample a second sample is produced with the exact same ampli- tude (duplication/repetition).</li>
<li>(c) &nbsp;Foreachinputsampleasecondsampleisproducedwiththeaverageamplitude of the current and next input samples.</li>
</ol>
</li>
<li>Use the proper combinations of the available GNU Radio blocks and implement the three aforementioned schemes.</li>
<li>Test the three schemes by using the following parameters:
<ol>
<li>(a) &nbsp;Input sample rate 48000 Hz.</li>
<li>(b) &nbsp;Output sample rate 96000 Hz.</li>
<li>(c) &nbsp;A test cosine signal from 0 up to 24 kHz. Use a QT Range slider to adjust the frequency in real time.</li>
</ol>
</li>
<li>Report and discuss your findings. How is the frequency domain affected? Which system is the best?</li>
<li>Recall, the decimation process of the previous assignment. In that case, after the decimation aliasing artifacts appeared. In the interpolation schemes above, do you observe any kind of artifacts? If yes, explain why they appear and try to compensate them.
NOTE: You can evaluate all the schemes by using a spectrum analyzer block with three input ports
</li>
<li>Afterevaluatingthethreeschemes,doyouconsiderofabetterschemetoup-sample? If yes, report the reasoning, build the scheme, test it against the others, and report your findings.
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Exercise 2

In this exercise you will implement a resampler, by combining properly decimation and interpolation implemented in the previous assignment and at Exercise 1. Note that your final result should compensate as much as possible any aliasing or other artifacts. The SNR between the signal tone and any other artifact should be at least 20 dB. For the interpolation process you can choose one of the three proposed schemes of Exercise 1.

<ul>
<li>Create a flowgraph with the name lab2_2.grc</li>
<li>Assume a source sampling rate of srcs = 48 kHz and a test cosine signal from 0 up
to 24 kHz. Use a QT Range slider to adjust the frequency in real time.
</li>
<li>Resample properly the signal to 72 kHz, by combining properly decimation and interpolation. Use a frequency sink operating at 72 kHz to visually inspect the result.
Exercise 3

This exercise will help you to get familiar with the modulation and constellation, as well as the impairments of noise and Carrier Frequency Offset (CFO). For this assignment you will use the lab2_3.grc flowgraph.
</li>
</ul>
<ol>
<li>Thelab2_3.grcflowgraphusesaBPSKmodulationthatmapsdataintoconstellation points. There are two sliders. The first controls the amplitude of noise, whereas the second inserts a Carrier Frequency Offset (CFO) at the system. Note that CFO is a common hardware impairment between the TX and RX device and telecommunica- tion standards should always deal with it. Play with the sliders by adjusting their values and report what you observe. How each one of the impairment (noise, CFO) affects the constellation points?</li>
<li>Modify properly the flowgraph in order to support other modulations schemes too. More precisely the flowgraph should support:
• BPSK • QPSK • 16QAM • 64QAM

The constellation point mappings are depicted at Figures 1-4.
</li>
<li>You may observe that the maximum IQ amplitude of each modulation scheme is dif- ferent. This means that the mean energy of each modulation scheme is different. In general this is not desirable. For this reason, perform normalization at the constel- lation points of each modulation scheme. The normalization factors can be retrieved from the table below. Report a screenshot for each one of the modulations.
2
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Figure 1: BPSK constellation points

Figure 2: QPSK constellation points

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: 16-QAM constellation points

</div>
</div>
<div class="layoutArea">
<div class="column">
Modulation

BPSK

QPSK 16-QAM 64-QAM

</div>
<div class="column">
Normalization factor

3

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰈

</div>
</div>
<div class="layoutArea">
<div class="column">
1/ 2

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰈 1/􏰈10

</div>
</div>
<div class="layoutArea">
<div class="column">
1/ 42

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Figure 4: 64-QAM constellation points

<ol start="4">
<li>For each one of the modulations report the maximum possible noise amplitude that can be achieved without errors. Actually without a demodulator this value can not be precise. Just provide an empirical estimation. Compare your findings and provide a brief explanation.</li>
<li>Do the same for the CFO. How each of the modulations is affected. Is there any similarity with the previous task or not? Discuss.</li>
</ol>
Exercise 4

Alter the flowgraph of the previous task, in order to support 8-PSK modulation too.

<ol>
<li>Assuming that one of the constellation points is the (1+0j) find the others. How did you compute the coordinates of the rest of the constellation points? Report.</li>
<li>Provide a screenshot with the constellation.</li>
<li>Compare the 8-PSK with the QPSK, regarding the immunity in noise and CFO.</li>
<li>Compare the spectrum of 8-PSK and 16-QAM. What do you observe?
4
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Exercise 5

In this exercise you will investigate the Frequency Shift Modulation (FSK). For this as- signment you will use the lab2_5.grc flowgraph. This simulation is quite similar with the PSK case. The Frequency Sink provides a graphical view of the transmitted signal, whereas the Time Sink provides a view of the bit stream after the demodulation.

<ol>
<li>Try different values of noise and CFO and compare your findings with the BPSK. Is the FSK more resilient to noise and CFO? Discuss!</li>
<li>Search through the literature and report your findings about the Modulation Index and Deviation parameters and how they are used in FSK.</li>
<li>How the CFO affects the FSK modulation?</li>
<li>Using existing blocks, try to recover from the CFO effect.</li>
</ol>
</div>
</div>
</div>
