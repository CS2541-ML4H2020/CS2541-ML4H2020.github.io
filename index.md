<div class="home" id="home">
  <h1 class="pageTitle">CSC2541HS 2020: Topics in Machine Learning:</h1>
  <h2 class="pageTitle">Machine Learning for Health </h2>
  <p>
This course will give a broad overview of machine learning for health. We begin with an overview of what makes healthcare unique, and then explore machine learning methods for clinical and healthcare applications through recent papers. We discuss the recent successes of of graphical models, deep learning, time-series analysis, and transfer learning in the context of health. We also broadly cover concepts of learning, algorithmic fairness, interpretability, and causality. We emphasize the importance of collaboration between technical and non-technical researchers, and consider the implications of machine learning in healthcare governance and policy. Students will choose and complete a course project, and make project presentations at the end of the course. 
  </p>
  <p>
    <b>This course requires a strong background in linear algebra and probability theory, or strong grades in the machine learning course</b>. Familiarity with programming and software engineering is beneficial, but not required.
</p>
  <p>
    CS2541 will be capped to students who have an appropriate background this semester. 
    If you are interested in taking the course, please come to our first lecture and fill out the course application
    <a href="https://goo.gl/forms/DFm2SPYZTUiVrsEk2">https://goo.gl/forms/DFm2SPYZTUiVrsEk2</a>
  </p>
  
<h2>Overview</h2>
<p>Instructor: <a href="http://www.marzyehghassemi.com/">Dr. Marzyeh Ghassemi</a><br>
Course Title: Topics in Machine Learning: Machine Learning for Health<br>
Time: Thursdays 1 PM - 3 PM <br>
Room: <a href="http://map.utoronto.ca/utsg/building/070">GB 221</a><br>

TAs: Taylor Killian, Nathan Ng<br>

Markus: <a href="https://markus.teach.cs.toronto.edu/csc2541-2019-01">https://markus.teach.cs.toronto.edu/csc2541-2019-01</a><br>

Piazza: <a href="https://piazza.com/utoronto.ca/winter2019/csc2541">https://piazza.com/utoronto.ca/winter2019/csc2541</a>
</p>


<h2>Grading</h2>
<p>Course grade will be made up of:
  <ul>
    <li><b>15%</b> Homework (<a href=/problem_set/CS2541-ProblemSet-1.pdf>1 problem set</a>) *</li>
    <li><b>10%</b> Weekly reflections submitted in <a href="https://markus.teach.cs.toronto.edu/csc2541-2019-01">Markus</a> for <b>all</b> required papers in reading list (1-2 questions)</li>
    <li><b>15%</b> <a href=/reflections>Paper presentation</a> done on a topic in-class (sign-up after the first lecture)</li>
    <li><b>60%</b> <a href=/Project>Course project</a> (an eight-page write up of your application of ML approaches to a healthcare problem)</li>
</ul>
* For the problem set, please complete the steps required to get access to MIMIC data outlined <a href="https://mimic.physionet.org/gettingstarted/access/">here</a>. One of the steps will require you to fill out a Data Use Agreement (DUA) where you will be asked for:
<ul>
  <li>A reference name. Write Marzyeh Ghassemi</li>
  <li>The general research area for which the data will be used: Write CS 2541 Homework</li>
</ul>
It takes some time so please ensure that you do this well before the deadline.
</p>



<div class="post">
	<h1 class="pageTitle">Schedule</h1>
	<!-- <img src="{{ '/assets/img/touring.jpg' | prepend: site.baseurl }}" alt=""> -->
	<p class="intro"> Jump to <a href="#feb">Feb.</a> or <a href="#mar">Mar.</a></p>
  <table style="width:100%">
  <tr>
    <th>Date</th>
    <th>Subject</th> 
    <th>Readings</th>
    <th>Student Presentation</th>
    <th>Deadlines</th>
  </tr>
  <tr>
    <td>Jan 10, 2019 </td>
    <td>Lecture 1: Why is healthcare unique? <br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 1.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://arxiv.org/pdf/1806.00388.pdf">Opportunities in Machine Learning for Healthcare</a></li>
        <li>[Required] <a href="https://www.bmj.com/content/361/bmj.k1479">Biases in electronic health record data due to processes within the healthcare system: retrospective observational study</a></li>
      </ul>
    </td>
    <td>
    </td>
    <td>
    </td>
  </tr>
  <tr>
    <td>Jan 17, 2019 </td>
    <td>Lecture 2: Supervised Learning for Classification, Risk Scores and Survival <br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 2.pdf"> Slides </a> </td> 
    <td>
      <ul>		      
        <li>[Required] <a href="https://www.nature.com/articles/s41598-018-24271-9">Recurrent Neural Networks for Multivariate Time Series with Missing Values</a></li>	
        <li>[Required] <a href="https://academic.oup.com/jamia/article/24/3/488/2907906">Understanding vasopressor intervention and weaning: risk prediction in a public heterogeneous clinical time series database</a></li>	      
        <li>[Required] Deep Survival Analysis (<a href="https://arxiv.org/abs/1608.02158">https://arxiv.org/abs/1608.02158</a> or <a href="https://www.mlforhc.org/s/21.pdf">https://www.mlforhc.org/s/21.pdf</a>)</li>	
      </ul>
    </td>
    <td>
	<ul>		      
		<li> Grey Kuling on Big Data In Health Care: Using Analytics To Identify And Manage High-Risk And High-Cost Patients </li>
	 </ul>
    </td>
    <td>
	<b> Reflection Questions on Required Papers</b>: 
	<ul>		      
		<li> Contrast the predictive tasks (e.g., labels in the objective function) in each of the required papers; what are the benefits and drawbacks of each?</li>
		<li> Would you deploy any of these supervised models?</li>
	</ul>
    </td>
  </tr>
  <tr>
    <td>Jan 24, 2019</td>
    <td>Lecture 3: Causal inference with observational data<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 3.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://www.jstor.org/stable/2289064">Statistics and Causal Inference</a></li>
        <li>[Required] <a href="http://stm.sciencemag.org/content/7/299/299ra122">A targeted real-time early warning score (TREWScore) for septic shock.</a></li>
        <li>[Required] <a href="https://papers.nips.cc/paper/6767-reliable-decision-support-using-counterfactual-models.pdf">Reliable Decision Support using Counterfactual Models</a></li>
      </ul>
    </td>
    <td>
      <ol>
        <li>David Burns on Deep Barcodes for Fast Retrieval of Histopathology Scans</li>
        <li>Adamo Young and Michael Dimmick on GRAM: Graph-based Attention Model for Healthcare Representation Learning</li>
        <li>Geoff Klein and Matt Hemsley on Deep MR to CT Synthesis using Unpaired Data</li>
        <li>Phil Boyer on What-If Reasoning with Counterfactual Gaussian Processes</li>
      </ol>
    </td>
    <td>
      Office Hours for Homework will be held on Wednesday, Jan 23 at 4-6pm in GB 405.
	<br><br>    
	<b> Reflection Questions on Required Papers</b>: 
	<ul>		      
		<li> Describe causal identifiability, and its impact on learning with observational data?</li>
		<li> What is the difference between a standard  Gaussian Process (GP) and a causal GP (CGP) objective function? How does that impact learning?</li>
	</ul>	    
    </td>
  </tr>
  <tr>
    <td>Jan 31, 2019</td>
    <td>Lecture 4: Fairness, Ethics, and Healthcare<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 4.pdf"> Slides </a> </td>
    <td>
      <ul>
        <li>[Required] <a href="http://www.jmlr.org/proceedings/papers/v28/zemel13.pdf">Learning Fair Representations</a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1805.12002.pdf">Why is My Classifier Discriminatory?</a></li>     
      </ul>
    </td>
    <td>
      <ol>
        <li>Matthew MacKay and Amanjit Singh Kainth on Learning Fair Representations</li>
        <li>Duc Truong on Equality of Opportunity in Supervised Learning</li>
        <li>Punit Shah  on Evaluating Reinforcement Learning Algorithms in Observational Health Settings</li>
        <li>Devin Singh on Use of GANs in Medical Imaging </li>
      </ol>
    </td>
    <td>
	<b> Reflection Questions on Required Papers</b>: 
	<ul>		      
		<li> What are ways that bias can enter into a machine learning model's predictions?</li>
		<li> Are there reasons that bias in medical data may be harder to detect or distentangle?</li>
	</ul>
    </td>
  </tr>
  <tr>
    <td id="feb">Feb 7, 2019</td>
    <td>Lecture 5: Clinical Time Series Modelling<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 5.pdf"> Slides </a> </td>
    <td>
      <ul>
        <li>[Required] <a href="http://mucmd.org/CameraReadySubmissions/65%5CCameraReadySubmission%5Cclinical-intervention-prediction%20(4).pdf">Clinical Intervention Prediction and Understanding with Deep Neural Networks</a></li>
        <li>[Required] <a href="https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/5b73729d562fa79aabf87383/1534292642748/9.pdf">Towards Understanding ECG Rhythm Classification Using Convolutional Neural Networks and Attention Mappings</a></li>
        <li>[Required] <a href="https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/5b7372dc1ae6cf102e27b7e7/1534292701747/13.pdf">Disease-Atlas: Navigating Disease Trajectories using Deep Learning</a></li>
        <li>[Required] <a href="http://www.sciencedirect.com/science/article/pii/S1532046414000847">Identifying and mitigating biases in EHR laboratory tests.</a></li>
      </ul>
    </td>
    <td>
      <ol>
        <li>Allen Lee</li>
        <li>Kelvin Wong and Shun Da Suo on Disease-Atlas: Navigating Disease Trajectories using Deep Learning</li>
        <li>Seung Eun Yi and Chantal Shaib on Clinical Intervention Prediction and Understanding with Deep Neural Networks</li>
        <li>Pouria Mashouri on Towards Understanding ECG Rhythm Classification Using Convolutional Neural Networks and Attention Mappings</li>
      </ol>
    </td>
    <td>
      <a href='/problem_set/CS2541-ProblemSet-1.pdf'>Homework 1</a> due at 11:59 PM on <a href="https://markus.teach.cs.toronto.edu/csc2541-2019-01">MarkUs</a><br>
      The code for extracting the data from the MIMIC psql database is <a href="https://github.com/CS2541-ML4H2019/CS2541-ML4H2019.github.io/tree/master/problem_set">here</a>
    </td>
  </tr>
  <tr>
    <td>Feb 14, 2019</td>
    <td>Lecture 6: Clinical Imaging (Radiology/Pathology)<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 6.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://ieeexplore.ieee.org/abstract/document/8217719/">Deep learning assessment of tumor proliferation in breast cancer histological images</a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1711.05225.pdf">CheXNet: Radiologist-level pneumonia detection on chest X-rays with deep learning</a></li>
        <li>[Required] <a href="https://www.nature.com/articles/nature21056.epdf">Dermatologist-level classification of skin cancer with deep neural networks</a></li>      
      </ul>
    </td>
    <td>
      <ol>
        <li>Sapir Labes on Systematic Analysis of Breast Cancer Morphology Uncovers Stromal Features Associated with Survival</li>
        <li>Hong Yue Sean Liu and Yan Li on Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs</li>
        <li>Srinivasan Sivanandan on CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning</li>
        <li>Vineeth Bhaskara Dermatologist-level classification of skin cancer with deep neural networks</li>
      </ol>
    </td>
    <td>
	    Project proposals due at 5PM <a href="https://docs.google.com/forms/d/e/1FAIpQLSfOSqcEhOnDvTmkMlOViUY1YF7i3eZOs6RumhWtiihrdBVVag/viewform?usp=sf_link">here</a>.
	<br><br>
	<b> Reflection Questions on Required Papers</b>: 
	<ul>		      
		<li> What are some cirtical differences between clinical imaging and images found in standard vision datasets?</li>
		<li> Are there standard pre-processing or modelling techniques that don't make sense in clinical images?</li>
	</ul>	    
    </td>
  </tr>
  <tr>
    <td>Feb 21, 2019</td>
    <td>Lecture 7: Clinical NLP and Audio<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 7.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/5b7373cc032be4fab0075363/1534292941994/30.pdf">Multi-Label Learning from Medical Plain Text with Convolutional Residual Models</a></li>
        <li>[Required] <a href="http://people.dbmi.columbia.edu/~chw7007/papers/chapter%2016.pdf">Natural Language Processing, Electronic Health Records, Clinical Research</a></li>
        <li>[Required] <a href="https://academic.oup.com/jamia/article-abstract/17/5/507/830823">Mayo clinical Text Analysis and Knowledge Extraction System (cTAKES): architecture, component evaluation and applications</a></li><li>[Optional] <a href="https://arxiv.org/abs/1808.08485">Deep Probabilistic Logic: A Unifying Framework for Indirect Supervision</a></li>
      </ul>
    </td>
    <td>
      <ol>
        <li>Sumeet Ranka and Vaibhav Saxena on Mayo clinical Text Analysis and Knowledge Extraction System (cTAKES): architecture, component evaluation and applications</li>
        <li></li>
        <li>Yingying Fu and Eric Wan on Multi-Label Learning from Medical Plain Text with Convolutional Residual Models</li>
        <li>Jienan Yao and Matthew Wong on Natural Language Processing, Electronic Health Records, and Clinical Research</li>
      </ol>
    </td>
    <td>
	<b> Reflection Questions on Required Papers</b>: 
	<ul>		      
		<li> How could external knowledge could be added to clinical NLP models and for what tasks might that make sense?</li>
		<li> How could clinical NLP benefit from using structured EHR data?</li>
	</ul>	   	    
    </td>
  </tr>
  <tr>
    <td>Feb 28, 2019</td>
    <td>Lecture 8: Clinical Reinforcement Learning<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 8.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3143507/pdf/nihms266705.pdf">Informing sequential clinical decision-making through reinforcement learning: an empirical study</a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1704.06300.pdf">A Reinforcement Learning Approach to Weaning of Mechanical Ventilation in Intensive Care Units</a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1707.06289.pdf">Meaningless comparisons lead to false optimism in medical machine learning</a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1805.12298.pdf">Evaluating Reinforcement Learning Algorithms in Observational Health Settings</a></li>
	    </ul>
    </td>
    <td>
      <ol>
        <li>Sindhu C M Gowda on A reduced dimension fMRI shared response model</li>
        <li>Daniel Dastoor and Joanna Pineda on Scalable and accurate deep learning with electronic health records</li>
        <li>Brenna Li on Meaningless comparisons lead to false optimism in medical machine learning</li>
        <li>Sneha Desai on A Reinforcement Learning Approach to Weaning of Mechanical Ventilation in Intensive Care Units</li>
      </ol>
    </td>
    <td>
	<b> Reflection Questions on Required Papers</b>: 
	<ul>		      
		<li> What are particular problems with off-policy evaluation in a clinical RL setting?</li>
		<li> What problems can arise with the action and state spaces chosen in the papers?</li>
	</ul>		    
    </td>
  </tr>
  <tr>
    <td id="mar">Mar 7, 2019</td>
    <td>Lecture 9: Missingness and Representations<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 9.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://academic.oup.com/biomet/article-abstract/63/3/581/270932">Inference and missing data</a></li>
        <li>[Required] <a href="http://www.cs.toronto.edu/~zemel/documents/2011-IJCAI-MZRS.pdf">Recommender Systems: Missing Data and Statistical Model Estimation</a></li>
        <li>[Required] <a href="http://www.marzyehghassemi.com/wp-content/uploads/2018/01/semi-supervised-CWR-GAN_Ghassemi.pdf">Semi-supervised Biomedical Translation with Cycle Wasserstein Regression GANs</a></li>
      </ul>
    </td>
    <td>
      <ol>
        <li>Jacob Kelly and Jeevaa Velayutham on Semi-supervised Biomedical Translation with Cycle Wasserstein Regression GANs</li>
        <li>Pulkit Mathur and Zhen Gou on Recommender Systems: Missing Data and Statistical Model Estimation</li>
        <li>Yuyang Liu and Chris Meaney on Recurrent Neural Networks for Multivariate Time Series with Missing Values</li>
        <li>Angeline Yasodhara and Marta Skreta on Why is my Classifier Discriminatory?</li>
      </ol>
    </td>
    <td>
      <b> Reflection Questions on Required Papers</b>: 
      <ul>          
        <li> Briefly discuss the techniques used in these papers to address the missingness/sparsity in electronic medical records.</li>
        <li> How does the current patient state affect the types of data that are collected in the future?</li>
        <li> Discuss if/how the models capture and propogate the patients' previous states for predicting clinical events.</li>
      </ul>	    
    </td>
  </tr>
  <tr>
    <td>Mar 14, 2019</td>
    <td>Lecture 10: Generalization and transfer learning<br> <a href="https://cs2541-ml4h2019.github.io/lectures/CSC2541 - Lecture 10.pdf"> Slides </a> </td> 
    <td>
      <ul>
        <li>[Required] <a href="https://www.sciencedirect.com/science/article/pii/S1532046415002282">Implications of non-stationarity on predictive modeling using EHRs</a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1608.00647.pdf">Multi-task Prediction of Disease Onsets from Longitudinal Lab Tests</a></li>
      </ul>
    </td>
    <td>
      <ol>
        <li>Alex Lu and Amy Lu on Implications of non-stationarity on predictive modeling using EHRs</li>
        <li>Fizza Ahmad Sheikh and Daniel Hidru on Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs</li>
        <li>Sean Segal and Sergio Casas on Multi-task Prediction of Disease Onsets from Longitudinal Lab Tests</li>
        <li>Zhen Yang and Chenzi Qie on Improving Prediction of Suicide and Accidental Death After Discharge From General Hospitals With Natural Language Processing</li>
      </ol>
    </td>
    <td>
      <b> Reflection Questions on Required Papers</b>: 
      <ul>          
        <li> Does multi-task learning inherently create more generalizable models?</li>
        <li>Are there conditions for which non-stationarity could be ignored in model training and deployment?</li>
      </ul>	    
    </td>
  </tr>
  <tr>
    <td>Mar 21, 2019</td>
    <td>Lecture 11: Interpretability / Humans-In-The-Loop / Policies and Politics</td> 
    <td>
      <ul>
        <li>[Required] <a href="http://people.dbmi.columbia.edu/noemie/papers/15kdd.pdf">Intelligible Models for HealthCare: Predicting Pneumonia Risk and Hospital 30-day Readmission</a></li>
        <li>[Required] <a href="https://people.csail.mit.edu/taolei/papers/emnlp16_rationale.pdf">Rationalizing Neural Predictions. </a></li>
        <li>[Required] <a href="https://arxiv.org/pdf/1606.03490.pdf">The Mythos of Model Interpretability.</a></li>
    </td>
    <td>
      <ol>
        <li>Pouria Mashouri on Towards Understanding ECG Rhythm Classification Using Convolutional Neural Networks and Attention Mappings</li>
        <li>Siva Manivasagam and Min Bai on Rationalizing Neural Predictions</li>
        <li>Shagun Gupta and Chun-Hao Chang on Intelligible Models for HealthCare: Predicting Pneumonia Risk and Hospital 30-day Readmission</li>
        <li>Angad Kalra on Why policymakers should care about “big data” in healthcare</li>
      </ol>
    </td>
    <td>
      <b> Reflection Questions on Required Papers</b>: 
      <ul>   	    
	<li> What are possible ways that a model could be verified as interpretable? </li>
        <li> Should machine learning models deployed in healthcare settings be held to a higher standard than other application areas? </li>
        <li> What concerns should policy makers have about deploying models to minimize hospital costs?</li>
    </ul>
    </td>
  </tr>
  <tr>
    <td>Mar 28, 2019</td>
    <td>Course Presentations</td> 
    <td></td>
    <td>
    </td>
    <td></td>
  </tr>
  <tr>
    <td>April 4, 2019</td>
    <td>Course Presentations</td> 
    <td></td>
    <td>
    </td>
    <td></td>
  </tr>
  <tr>
    <td>April 11, 2019</td>
    <td>Projects Due</td> 
    <td></td>
    <td>
    </td>
    <td>Project report due 11:59PM</td>
  </tr>
</table>


</div>
