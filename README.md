## Computational Neuroscience Research: Brain Science Institute, KIST (2021)

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=Tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/> <img src="https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=Numpy&logoColor=white"/> <img src="https://img.shields.io/badge/GoogleColab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=white"/> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=Ubuntu&logoColor=white"/> <img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=JSON&logoColor=white"/> <img src="https://img.shields.io/badge/AdobeIllustrator-FF9A00?style=flat-square&logo=AdobeIllustrator&logoColor=white"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=PyCharm&logoColor=white"/> <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=macOS&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=Slack&logoColor=white"/>

### - Affordance
<img src="https://user-images.githubusercontent.com/45449025/130319151-1c108bfd-7d5e-479d-b299-2ab2b82a26c1.png" width="800px" height="450px" title="aff1"></img>
<img src="https://user-images.githubusercontent.com/45449025/130319180-c5071622-ebe9-452f-a52b-c1faf1ce64c7.png" width="800px" height="450px" title="aff2"></img>
<img src="https://user-images.githubusercontent.com/45449025/130319194-b71d8d49-5289-4611-bef6-7c9818c9d60a.png" width="800px" height="450px" title="aff3"></img>
<img src="https://user-images.githubusercontent.com/45449025/130319199-7579dc36-a303-44f2-bed1-284fb7ccb80c.png" width="800px" height="450px" title="aff4"></img>

### - Poisson Spike Train with Matlab
<img src="https://user-images.githubusercontent.com/45449025/130318902-754d0215-2552-4338-a1a2-a6c0c3296882.png" width="800px" height="500px" title="poisson"></img>
<br/>
i.	A variability of spike trains can be measured by the coefficient of variation (CV)<br/>
ii.	The exponential distribution is equal to the probability density function<br/>
iii.	Refractory time should be deleted as it is not the case of a general Poisson process where an equal likelihood applies to the next spike at any given time<br/>
iv.	We tried out generating and simulating Poisson spike train using Matlab according to the direction by the book ‘Principles of Computational Modelling in Neuroscience’<br/>

### - Leaky Integrate-and-Fire model with Python
<img src="https://user-images.githubusercontent.com/45449025/130318972-88d21781-0698-43ce-9aec-4a44270457ff.png" width="400px" height="300px" title="ifneuron">
<img src="https://user-images.githubusercontent.com/45449025/130319001-963bcd12-30d5-4614-acd5-a27e9ce736ed.png" width="400px" height="300px" title="bursting">
<img src="https://user-images.githubusercontent.com/45449025/130319064-b9c620b1-547a-45ba-8f62-c674d4ba8228.png" width="400px" height="300px" title="adaptation">
<img src="https://user-images.githubusercontent.com/45449025/130319035-33cb603d-22db-4cdd-bea0-9d372f8a38fa.png" width="400px" height="300px" title="hhmodel">
i.	We simulated the IF (Integrate-and-Fire) model for bursting and adaptation<br/>
ii.	In a LIF model, no external input means no spiking activity and the only way to have sustained activity in the absence of inputs is to add a positive constant input<br/>
iii.	The input has two possible interpretations; 1) Additional external inputs that are not explicitly modeled and that are approximated as constant, and the other is 2) Internal neuronal excitability properties<br/>
iv.	To assess whether the IF model still respect the physiological value objective, we need to simulate the neural network and compare its activities against experimental data<br/>

### - PVLV (Primary Value and Learned Value Pavlovian Learning Algorithm)
<img src="https://user-images.githubusercontent.com/45449025/130318946-75f5e452-cfb4-47e4-91fb-6895a3bce4b4.png" width="800px" height="500px" title="pvlv"></img>
<br/>
i.	PVLV model is made for understanding the reward-predictive firing properties of dopamine neurons as an alternative to the temporal-difference algorithm suggested by Sutton<br/>
ii.	It is a biologically plausible framework for understanding the neural basis of reward learning<br/>
iii.	The primary value (PV) system controls the performance and learning during primary rewards and learns about primary rewards whereas the learned value (LV) system learns to fire for conditioned stimuli that are associated with rewards<br/>
iv.	We simulated the responses of the dopaminergic neuron by feeding different strengths of stimulus in each session to test the algorithm which has shown the expected activity according to the degree of the stimulus<br/>
v.	Its output activity follows its membrane potential and the excitatory input the unit receives, and the total conductance went negative as soon as the output activity came down<br/>
