# ee352-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [EE352 Lab 6 Solved](https://www.ankitcodinghub.com/product/ee352-lab-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94344&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE352 Lab 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In the previous weeks, we have considered amplitude modulation (AM) and its variants. We now consider angle modulation. To generate angle modulation, the amplitude of the modulated carrier is held constant and either the phase or the time derivative of the phase of the carrier is varied linearly with the message signal, m(t). These lead to phase modulation (PM) or frequency modulation (FM), respectively. In this week, we focus on FM.

FM is a system in which the amplitude of the carrier wave c(t) is kept constant, while its frequency and the rate of changes are varied by the message signal.

The time-domain representation of FM signal, when the carrier is c(t) = Ac cos (2πfc t) and the message signal is m(t), is given by

􏰀􏰂t􏰁

</div>
</div>
<div class="layoutArea">
<div class="column">
s(t)=Accos 2πfct+2πkf where kf represents the frequency sensitivity factor.

Frequency demodulation is the process that enables us to recover the original modulating signal from a frequency modulated signal. Here, we apply fmdemod(.) function to recover the original modulating signal.

In this week, our objectives are

a. to generate FM waveforms,

b. to consider the effect of different frequency sensitivity factors,

c. to observe and analyze the FM modulated waveforms in both time and frequency domains.

It is also useful to learn about the Matlab functions cumsum(.) and fmdemod(.) by using Matlab Help before performing the labwork given below.

2 Labwork

Read the preliminaries given above carefully before doing the experiment given below.

2.1 Modulation

<ol>
<li>Assume that the sampling frequency Fs = 2kHz and the durations of carrier signal c(t) and message signal m(t) are 0.2s.</li>
<li>Construct the carrier signal c(t) which is c(t) = Ac cos (2πfc t) with carrier frequency fc = 200Hz and Ac = 1.</li>
<li>Construct the message signal m(t) which is m(t) = Am cos (2πfm t) with message frequency fm = 50Hz and Am = 2.</li>
<li>Construct the frequency modulated signal, s(t) as given in Equation 1, for each following frequency sensitivity factor kf such as kf = [5, 25, 50]. (i.e. s1(t), s2(t), s3(t) )
Hint: Use MATLAB command cumsum() for the integration.
</li>
</ol>
April 22, 2021

</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
<div class="layoutArea">
<div class="column">
m(τ)dτ (1)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
EE 352 – Lab 6 (Frequency Modulation/Demodulation)

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>Plot m(t) and the time domain frequency modulated signals, s1(t), s2(t), s3(t) , with kf = [5, 25, 50] in the same figure using 4 × 1 subplot.</li>
<li>Compare and comment on the obtained frequency modulated signals in 2.1(e).</li>
</ol>
2.2 Signals in Frequency Domain

<ol>
<li>Obtain the Fourier transforms of m(t), c(t) and s1(t), s2(t), s3(t) for each kf = [5, 25, 50] where the number of DFT points (N) is the length of the signal.</li>
<li>Plot the magnitude of the frequency spectrum of m(t) and c(t) i.e., |M(f)| and |C(f)|, respectively in the same figure using 2 × 1 subplot.</li>
<li>Plot the magnitude of the frequency spectrum of s1(t), s2(t), s3(t) for each kf = [5, 25, 50] i.e. |S1(f)|, |S2(f)|, |S3(f)|, in the same figure using 3 × 1 subplot.</li>
<li>Comment on the effect of the different kf values to the frequency modulation.</li>
</ol>
2.3 Demodulation

<ol>
<li>Demodulate the each modulated signal s1(t), s2(t), s3(t) using fmdemod(.) function when kf = [5, 25, 50].</li>
<li>Plot the three demodulated signals and the message signal in the time domain on the same figure using 3 × 1 subplot.
Note: Use hold on command to plot the message and the corresponding demodulated signal.
</li>
<li>Comment on the results that you obtain in 2.3(b).</li>
</ol>
Note: All comments will be written in your reports. Please do not add the comments to the Matlab file.

</div>
</div>
</div>
