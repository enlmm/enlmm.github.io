---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

<!-- <img src="/images/deep.jpg"> -->
<center>
<h2 class="blackpar_title">Efficient Natural Language and Speech Processing </h2>
<h3 class="blackpar_title">(Models, Training and Inference)</h3>
</center>
<p>

This workshop aims at introducing some fundamental problems in the field of natural language and speech processing which can be of interest to the general machine learning and deep learning community to improve the efficiency of the models, their training and inference. The workshop program offers an interactive platform for gathering experts and talents from academia and industry through different invited keynote talks, panel discussions, paper submissions and reviews, poster and oral presentations and a mentorship program.
This will provide an opportunity to discuss and learn from each other, exchange ideas, build connections, and brainstorm on potential solutions and future collaborations. The topics of this workshop can be of interest for people working on general machine learning, deep learning, optimization, theory and NLP & Speech applications.

<!--	
The workshop will take place on <span class="blackhighlighted">DATE, 2021</span>. 
Due to the pandemic, the workshop will be <span class="blackhighlighted">VIRTUAL</span>. More details will be provided soon. 

Note that to attend the event, a registration on the ICLR website is required. All workshop events (except Poster session and open discussion) can be followed using the ICLR link or use the zoom link by clicking on “join zoom” on the ICLR link. For the Poster session participants should une the Gather.town link. Note that papers id can be found on Accepter papers section.
</p>
<br>
-->
<br><br>
<h2 class="blackpar_title" id="Overview">Overview</h2>
<p>
Despite the great success of deep neural networks due to huge over-parameterization and using very large amount of data in different tasks of natural language processing (NLP) and speech processing, training or deploying these networks on devices or even cloud services with limited memory and computational power can be very expensive and challenging. For instance, pre-trained language models (PLMs) such as GPT-3 have led to a great breakthrough in NLP; but running GPT-3 with more than 170 billion parameters trained with more than 500 GB of data requires more than 10 Tesla V-100 GPUs. That being said, still improving the NLP and Speech models by increasing their number of parameters and incorporating more data is deemed a very common practice in the NLP and Speech domains. Therefore, it is of vital importance to invest on enhancing the efficiency of these models in terms of model architectures, training and inference from different perspectives highlighted in this workshop. In this regard, we would like to share some unique and fundamental challenges with the NeurIPS community to be considered in their future investigations.
</p>
<br><br>

<!-- Call for Papers -->
<h2 class="blackpar_title" id="Call for Papers">Call for Papers</h2>



We encourage the NeurIPS community to submit their solutions, ideas, and ongoing work concerning data, model, training, and inference efficiency for NLP and speech processing. The scope of this workshop includes, but not limited to, the following topics.

<br><br>
<b>Efficient Pre-Training and Fine-Tuning.</b> Pre-training is a very expensive process. Even a small modification to the configuration of the models requires the user to redo pre-training:
<br>

<ul>
	<li>Fast pre-training techniques, avoiding pre-training from scratch</li>
	<li>Multi-domain pre-training/fine-tuning and fast domain adaptation for pre-trained/fine tuned models</li>
	<li>Multimodal pre-trained (e.g., text--speech) models</li>
	<li>Avoiding task-specific fine tuning of pre-trained models</li>
	<li>New efficient architectures for pre-trained models</li>
</ul>

<br>
<b>Model Compression.</b> Neural model compression techniques such as quantization, pruning, layer decomposition and knowledge distillation (KD) aim at reducing the number of parameters of the models, improving their memory requirements or running efficiency:
<br>

<ul>
	<li>Impact of different compression techniques on the inductive biases learned by the original models</li>
	<li>Combined compression techniques for more efficient NLP and speech models</li>
	<li>Efficient KD for NLP and speech, efficient intermediate layer distillation, and teacher-free distillation</li>
	<li>Improving KD for large classification problems (e.g., text generation and machine translation with a very large number of output classes)</li>
	<li>Solving the <i>Capacity Gap</i> problem and the <i>Search Problem</i> associated with finding the best checkpoint of the teacher</li>
	<li>Theory of KD (e.g., how does KD work?) </li>
</ul>

<br>
<b>Efficient Training.</b> How to improve the training speed of the NLP and speech models:
<br>
<ul>
	<li>Improving the optimizer for faster training</li>
	<li>Accelerated training of different tasks in NLP and speech</li>
	<li>Distributed training,  federated learning and continual learning for NLP and speech tasks </li>
</ul>

<br>
<b>Data Efficiency.</b> Pre-trained models rely on a huge amount of unlabeled data which makes the training very sample inefficient:
<br>
<ul>
	<li>Sample efficient training, training with less data, few-shot and zero-shot learning</li>
	<li>Sample efficient data-augmentation, identifying which training samples should be augmented</li>
	<li>Low-resource NLP and speech, considering training tasks with limited available data</li>
</ul>

<br>
<b>Edge Intelligence.</b>  Running the trained models on edge devices will require a conversion process to match the network with hardware specifications:
<br>
<ul>
	<li>TinyML for NLP and speech on embedded systems</li>
	<li>Efficient conversion versus hardware-aware training</li>
	<li>Training on device</li>
</ul>


<h2 class="blackpar_title">Submission Instructions</h2>

<p>
You are invited to submit your papers in our CMT submission <a href='https://cmt3.research.microsoft.com/ENLSP2021'>portal</a>. All the submitted papers have to be anonymous for double-blind review. We expect each paper will be reviewed by at least three reviewers. The content of the paper (excluding the references and supplementary materials) should not be longer than 6 pages, strictly following the NeurIPS template style (which can be found <a href='https://neurips.cc/Conferences/2021/PaperInformation/StyleFiles'>here</a>). 
<br><br>
Authors can submit up to 100 MB of supplementary materials separately. Authors are highly encouraged to submit their codes for reproducibility purposes. Although original submissions are preferred, submitted papers can be among your already published or ArXiv papers, and your under submission works. Please make sure to indicate the complete list of conflict of interests for all the authors of your paper. To encourage higher quality submissions, our sponsors are offering the Best Paper Award to qualified outstanding original oral and poster presentations (upon nomination of the reviewers). Bear in mind that our workshop is not archival, but the accepted papers will be hosted on the workshop website.
</p>


<br><br>
<h2 class="blackpar_title">Important Dates:</h2>
<ul>
	<li>Submission Deadline: <del>September 18, 2021</del> <b>September 22, 2021 AOE</b></li>
	<li>Acceptance Notification: October 23, 2021 <b>AOE</b></li>
	<li>Camera-Ready Submission: November 1, 2021 <b>AOE</b></li>
	<li>Workshop Date: December 13, 2021</li>
</ul>

<br><br>
<!--Confirmed Spearkers-->
<h2 class="blackpar_title" id="Confirmed Spearkers">Confirmed Spearkers</h2>
<div class="row">
	<div class="card column">
	  <img src="/images/mirella-lapata.jpeg" alt="Mirella Lapata" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Mirella Lapata</b>
			<br>
			University of Edinburgh
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/zettlemoyer.jpg" alt="Luke Zettlemoyer" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Luke Zettlemoyer</b>
			<br>
			University of Washington (Facebook)
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/kevin1.png" alt="Kevin Duh" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Kevin Duh</b>
			<br>
			Johns Hopkins University
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/boxing.jpg" alt="Boxing Chen" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Dr.<br>Boxing Chen</b>
			<br>
			Alibaba
		</h4>
		</center>
	  </div>
	</div>
</div>

<div class="row">
	<div class="card column">
	  <img src="/images/sameer_singh.jpg" alt="Saneer Singh" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Sameer Singh</b>
			<br>
			University of California
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/danqi_2019.jpg" alt="Danqi Chen" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Danqi Chen</b>
			<br>
			Princeton University
		</h4>
		</center>
	  </div>
	</div>	
	<div class="card column">
	  <img src="/images/norouzi.jpg" alt="Mohammad Norouzi" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Dr.<br>Mohammad Norouzi</b>
			<br>
			Google Brain
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/Yejin.jpg" alt="Yejin Choi" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Yejin Choi</b>
			<br>
			University of Washington (Allen Institute for AI)
		</h4>
		</center>
	  </div>
	</div>
</div>


<div class="row">
	<div class="card column">
	  <img src="/images/xinjiang.jpg" alt="Xin Jiang" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Dr.<br>Xin Jiang</b>
			<br>
			Huawei Noah's Ark Lab
		</h4>
		</center>
	  </div>
	</div>

	<div class="card column">
	  <img src="/images/xu_sun.jpg" alt="Xu Sun" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Xu Sun</b>
			<br>
			Peking University
		</h4>
		</center>
	  </div>
	</div>	
	

	<div class="card column">
	  <img src="/images/barbara.png" alt="Barbara Plank" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Barbara Plank</b>
			<br>
			IT University of Copenhagen
		</h4>
		</center>
	  </div>
	</div>
	
	<div class="card column">
	  <img src="/images/samira_ebrahimi_kahou.jpg" alt="Samira Ebrahimi Kahou" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Samira Ebrahimi Kahou</b>
			<br>
			ETS & MILA
		</h4>
		</center>
	  </div>
	</div>
	
</div>

<br> <br>
<h2 class="blackpar_title" id="Schedule">Schedule (coming soon!)</h2>


<!--
<div class="row">
	<table id="customers">
	  <tr>
		<th>Time</th>
		<th>Title</th>
		<th>Presenter</th>
	  </tr>
	  <tr>
		<td>08:20 - 08:30</td>
		<td>Opening Speech</td>
		<td>Pascal Poupart</td>
	  </tr>
	  <tr>
		<td>08:30 - 09:10</td>
		<td>Invited Speaker</td>
		<td>Mirella Lapata</td>
	  </tr>
	  <tr>
		<td>09:10 - 09:50</td>
		<td>Invited Speaker</td>
		<td>Luke Zettlemoyer</td>
	  </tr>
	  <tr>
		<td>09:50 - 10:00</td>
		<td>Break</td>
		<td></td>
	  </tr>
	  <tr>
		<td>10:00 - 10:40</td>
		<td>Invited Speaker</td>
		<td>Yejin Choi</td>
	  </tr>
	  <tr>
		<td>10:40 - 11:20</td>
		<td>Invited Speaker</td>
		<td>Mohammad Norouzi</td>
	  </tr>
	  <tr>
		<td>11:20 - 12:00</td>
		<td>Invited Speaker</td>
		<td>Xin Jiang</td>
	  </tr>
	  <tr>
		<td>12:00 - 12:30</td>
		<td><b>Panel Discussion and Open QA</b></td>
		<td>Morning Keynote Speakers</td>
	  </tr>
	  <tr>
		<td>12:30 - 13:30</td>
		<td>Lunch Break and <b>First Poster Session</b></td>
		<td></td>
	  </tr>
	  <tr>
		<td>13:30 - 14:00</td>
		<td><b>Paper Spotlight Session</b></td>
		<td></td>
	  </tr>
	  <tr>
		<td>14:00 - 14:40</td>
		<td>Invited Speaker</td>
		<td>Boxing Chen</td>
	  </tr>
	  <tr>
		<td>14:40 - 15:20</td>
		<td>Invited Speaker</td>
		<td>Barbara Plank</td>
	  </tr>
	  <tr>
		<td>15:20 - 16:00</td>
		<td>Invited Speaker</td>
		<td>Kevin Duh</td>
	  </tr>
	  <tr>
		<td>16:00 - 16:10</td>
		<td>Break</td>
		<td></td>
	  </tr>
	  <tr>
		<td>16:10 - 16:50</td>
		<td>Invited Speaker</td>
		<td>Danqi Chen</td>
	  </tr>
	  
	  <tr>
		<td>16:50 - 17:30</td>
		<td>Invited Speaker</td>
		<td>Sameer Singh</td>
	  </tr>
	  <tr>
		<td>17:30 - 18:10</td>
		<td>Invited Speaker</td>
		<td>Xu Sun</td>
	  </tr>
	  <tr>
		<td>18:10 - 18:40</td>
		<td><b>Panel Discussion and Open QA</b></td>
		<td>Afternoon Keynote Speakers</td>
	  </tr>
	  <tr>
		<td>18:40 - 18:50</td>
		<td><b>Announcing Best Paper and Best Poster Award</b></td>
		<td></td>
	  </tr>
	  <tr>
		<td>18:50 - 19:00</td>
		<td>Closing Speech</td>
		<td>Pascal Poupart</td>
	  </tr>
	</table>
</div>
-->

<br> <br>
<!-- Organizers -->
<h2 class="blackpar_title" id="Organizers">Organizers</h2>
<div class="row">
	<div class="card column" style="margin-left:13%;">
	  <img src="/images/Mehdi_Rezagholizadeh.jpg" alt="Mehdi Rezagholizadeh" class="img_card">
	  <div class="container" >
		<center>
		<h4>
			<b>Mehdi Rezagholizadeh</b>
			<br>
			Huawei Noah's Ark Lab
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/lili_mou.jpg" alt="Lili Mou" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Lili Mou</b>
			<br>
			University of Alberta
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column" >
	  <img src="/images/Yue_Dong.jpg" alt="Yue Dong" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Yue Dong</b>
			<br>
			McGill University & MILA
		</h4>
		</center>
	  </div>
	</div>

</div>
<div class="row">
	<div class="card column" style="margin-left:13%;">
	  <img src="/images/pascal_poupart.jpg" alt="Pascal Poupart" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Pascal Poupart</b>
			<br>
			University of Waterloo
		</h4>
		</center>
	  </div>
	</div>

	<div class="card column" >
	  <img src="/images/ali_ghodsi.jpg" alt="Ali Ghodsi" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Ali Ghodsi</b>
			<br>
			University of Waterloo
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/qun_liu.png" alt="Qun Liu" class="img_card">
	  <div class="container">
		<center>
		<h4>
			<b>Qun Liu</b>
			<br>
			Huawei Noah's Ark Lab
		</h4>
		</center>
	  </div>
	</div>
</div>

<br><br>
<!-- Technical Committee -->
<h2 class="blackpar_title" id="Technical Committee">Technical Committee</h2>

<ul>
	<li>Kevin Duh (Johns Hopkins University)</li>
	<li>Bang Liu (University of Montreal (UDM))</li>
	<li>Wulong Liu (Huawei Noah's Ark Lab)</li>
	<li>Vahid Partovi Nia (Huawei Technologies)</li>
	<li>Peyman Passban (Amazon)</li>
	<li>Ivan Kobyzev (Huawei Noah's Ark Lab)</li>
	<li>Jad Kabbara (McGill University & MILA)</li> 
	<li>Aref Jafari (University of Waterloo)</li> 
	<li>Ahmad Rashid (Huawei Noah's Ark Lab)</li> 
	<li>Shailza Jolly (TU Kaiserslautern)</li> 
	<li>Md. Akmal Haidar (Huawei Noah's Ark Lab)</li> 
	<li>Jingjing Xu (ByteDance)</li> 
	<li>Vasileios Lioutas (University of British Colombia (UBC))</li> 
	<li>Anderson R. Avila (Huawei Noah's Ark Lab)</li> 
	<li>Malik H. Altakrori (McGill University & MILA)</li> 
	<li>Ali Vahdat (Thomson Reuters)</li> 
	<li>Prasanna Parthasarathi (McGill University & MILA)</li> 
	<li>Fattane Zarrinkalam (Thomson Reuters)</li> 
	<li>Makesh S Narsimhan (McGill University & MILA)</li> 
	<li>Nasrin Taghizadeh (University of Tehran)</li> 
	<li>Borna Jafarpour (Thomson Reuters)</li> 
	<li>Shohreh Shaghaghian (Thomson Reuters)</li> 
	<li>Ehsan Kamalloo (University of Alberta)</li>
	<li>Ali Saheb Pasand (University of Waterloo)</li>
	<li>Abbas Ghaddar (Huawei Noah's Ark Lab)</li>
	<li>Mehrdad Ganjeh (Ernst & Young (EY))</li>
	<li>Mingxuan Wang (ByteDance)</li>
	<li>Tanya Roosta (Amazon)</li>
	<li>Soheila Samiee (BASF)</li>
	<li>Hamidreza Mahyar (McMaster University)</li>
	<li>Yimeng Wu (Huawei Noah's Ark Lab)</li>
	<li>Omar Mohamed Awad (Huawei Technologies)</li>
	<li>Marzieh Tahaei (Huawei Noah's Ark Lab)</li>
	<li>Habib Hajimolahoseini (Huawei Technologies)</li>
	<li>Mohammad Salameh (Huawei Technologies)</li>
	<li>Kira Aveline Selby (University of Waterloo)</li>
</ul>
