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
	<li>Submission Deadline: <del>September 22, 2021 AOE</del></li>
        <li>Uploading Supplementary Materials: <del>September 26, 2021 AOE</del></li>
	<li>Acceptance Notification: <del>October 23, 2021 AOE</del></li>
	<li>Camera-Ready Submission: <del>November 1, 2021 AOE</del></li>
	<li>Workshop Date: December 13, 2021</li>
</ul>
<div class="alert alert-success d-flex align-items-center" role="alert" style="font-size:20px;">
	<i class="bi bi-exclamation-triangle" style="font-size: 1.5rem; margin-right:10px;"></i>
	<div>
		The accepted papers can be found <a href="./accepted_papers.html">here</a>.
	</div>
</div>
<br><br>
<!--Confirmed Speakers-->
<h2 class="blackpar_title" id="Confirmed Spearkers">Confirmed Speakers</h2>
<div class="row_perso">
	<div class="card_perso column_perso">
	  <img src="/images/mirella-lapata.jpeg" alt="Mirella Lapata" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Mirella Lapata</b>
			<br>
			University of Edinburgh
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/zettlemoyer.jpg" alt="Luke Zettlemoyer" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Luke Zettlemoyer</b>
			<br>
			University of Washington (Facebook)
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/kevin1.png" alt="Kevin Duh" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Kevin Duh</b>
			<br>
			Johns Hopkins University
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/boxing.jpg" alt="Boxing Chen" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Dr.<br>Boxing Chen</b>
			<br>
			Alibaba
		</h6>
		</center>
	  </div>
	</div>
</div>

<div class="row_perso">
	<div class="card_perso column_perso">
	  <img src="/images/sameer_singh.jpg" alt="Saneer Singh" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Sameer Singh</b>
			<br>
			University of California
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/danqi_2019.jpg" alt="Danqi Chen" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Danqi Chen</b>
			<br>
			Princeton University
		</h6>
		</center>
	  </div>
	</div>	
	<div class="card_perso column_perso">
	  <img src="/images/norouzi.jpg" alt="Mohammad Norouzi" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Dr.<br>Mohammad Norouzi</b>
			<br>
			Google Brain
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/Yejin.jpg" alt="Yejin Choi" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Yejin Choi</b>
			<br>
			University of Washington (Allen Institute for AI)
		</h6>
		</center>
	  </div>
	</div>
</div>


<div class="row_perso">
	<div class="card_perso column_perso">
	  <img src="/images/houlu.jpg" alt="Lu Hou" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Dr.<br>Lu Hou</b>
			<br>
			Huawei Noah's Ark Lab
		</h6>
		</center>
	  </div>
	</div>

	<div class="card_perso column_perso">
	  <img src="/images/xu_sun.jpg" alt="Xu Sun" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Xu Sun</b>
			<br>
			Peking University
		</h6>
		</center>
	  </div>
	</div>	
	

	<div class="card_perso column_perso">
	  <img src="/images/barbara.png" alt="Barbara Plank" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Barbara Plank</b>
			<br>
			IT University of Copenhagen
		</h6>
		</center>
	  </div>
	</div>
	
	<div class="card_perso column_perso">
	  <img src="/images/samira_ebrahimi_kahou.jpg" alt="Samira Ebrahimi Kahou" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Prof.<br>Samira Ebrahimi Kahou</b>
			<br>
			ETS & MILA
		</h6>
		</center>
	  </div>
	</div>
	
</div>

<br> <br>
<h2 class="blackpar_title" id="Schedule">Schedule (EST time zone - New York/Montreal/Toronto)</h2>

<!-- insert pop ups here -->

<div class="modal fade" id="talk_1" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Opening Speech<br><b>Presenter:</b> Pascal Poupart<br><b>Bio:</b><p class="par_panel_perso">TBD</p><b>Abstract:</b><p class="par_panel_perso">TBD</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_2" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Continual Learning in Large-Scale Pre-Training<br><b>Presenter:</b> Xu Sun<br><b>Bio:</b><p class="par_panel_perso">Xu Sun is an Associate Professor in the Department of Computer Science, Peking University. He got Ph.D from The University of Tokyo (2010), advised by Prof. Jun'ichi Tsujii. From 2010 to 2012, he worked at The University of Tokyo, Cornell University, and The Hong Kong Polytechnic University as research fellows. He was a research intern at MSR-Redmond in 2009. His research focuses on natural language processing and machine learning, especially on natural language generation and deep learning for language. He received COLING Best Paper Award 2018.</p><b>Abstract:</b><p class="par_panel_perso">Large-scale pre-training has enabled break-throughs in natural language processing. However, the underlying large-scale models and data make the studies in the field hard to sustain. In this talk, I will introduce our recent work focusing on continual learning in large-scale pre-training to improve the efficiency of pre-trained language models (from ICML 2021, AAAI 2021, etc.). For data-efficient continual learning for PLMs, this talk includes our work on addressing long-tailed data distribution with definitional data and accurate behavioral modifications with low instance-wise side effects by limiting the changed parameters. For cost-effective searching of PLM architecture, I will introduce our training-free neural architecture search method based on the gram matrix of instance gradients that can find better fine-tuning architecture of PLMs. Continual Learning has vast opportunities in efficient PLMs learning and applications and new challenges are there to be resolved.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_3" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Efficient Multi-lingual Neural Machine Translation<br><b>Presenter:</b> Boxing Chen<br><b>Bio:</b><p class="par_panel_perso">Boxing Chen is a Senior Staff Algorithm Expert at Machine Intelligence Lab of Alibaba Group. He works on natural language processing, mainly focusing on machine translation. Prior to Alibaba, he was a Research Officer at the National Research Council Canada (NRC). He has co-authored more than 80 papers in the NLP conferences and journals and served as area chair for ACL and EMNLP. His teams ranked first place over 20 times in various MT competitions.</p><b>Abstract:</b><p class="par_panel_perso">To support Alibaba’s globalization, we developed a Multi-lingual Neural Machine Translation (MNMT) system to conduct translation between 214 languages with one model. The main challenges of MNMT are model capacity, zero-shot translation, inference speed and energy cost, etc. Therefore, we performed several studies to make the training, inference, and energy more efficient while remaining the competitive translation quality. Which include: 1. Language-aware interlingua-based new MNMT architecture; 2. Improving zero-shot translation via joint training with denoising autoencoding; 3. Speedup decoding with strategies of shallow decoder, decoder attention weights sharing, and shortlist prediction; 4. A new energy-efficient attention mechanism that replaces multiplication operations with binarized selective and addition operations.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_4" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Compression and Acceleration of Pre-trained Language Models<br><b>Presenter:</b> Lu Hou<br><b>Bio:</b><p class="par_panel_perso">Dr. Lu HOU is a researcher at the Speech and Semantics Lab in Huawei Noah's Ark Lab. She obtained Ph.D. from Hong Kong University of Science and Technology in 2019, under the supervision of Prof. James T. Kwok. Her current research interests include compression and acceleration of deep neural networks, natural language processing, and deep learning optimization.</p><b>Abstract:</b><p class="par_panel_perso">Recently, Transformer-based pre-trained models like BERT and GPT have achieved remarkable results on various natural language understanding tasks and even some computer vision and multi-modal tasks. However, these models have many parameters, hindering their deployment on edge devices or the cloud. In this talk, I will introduce some recent progress on how we alleviate the concerns in various deployment scenarios during the inference and training period. Specifically, compression and acceleration methods using knowledge distillation, dynamic networks, and network quantization will be discussed.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_6" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Summarization in Quantized Transformer Spaces<br><b>Presenter:</b> Mirella Lapata<br><b>Bio:</b><p class="par_panel_perso">Mirella Lapata is professor of natural language processing in the School of Informatics at the University of Edinburgh.  Her research focuses on getting computers to understand, reason with, and generate natural language. She is the first recipient (2009) of the BCS and Information Retrieval Specialist Group (BCS/IRSG) Karen Sparck ones award, a Fellow of the Association for Computational Linguistics (ACL), and a Fellow of the Royal Society of Edinburgh (FRESE).  She has also received best paper awards in leading NLP conferences and has served on the editorial boards of the Journal of Artificial Intelligence Research, the Transactions of the ACL, and Computational Linguistics.  She was president of SIGDAT (the group that organises EMNLP) in 2018.</p><b>Abstract:</b><p class="par_panel_perso">Deep generative models with latent variables have become a major focus n of NLP research over the past several years.  These models have been used both for generating text and as a way of learning latent representations of text for downstream tasks. While much previous work uses continuous latent variables, discrete variables are attractive because they are more interpretable and typically more space efficient. In this talk we consider learning discrete latent variable models with Quantized Variational Autoencoders, and show how these can be ported to the task of opinion summarization. We provide a clustering interpretation of the quantized space and a novel extraction algorithm to discover popular opinions among hundreds of reviews, a significant step towards opinion summarization of practical scope. We further demonstrate how this approach enables controllable summarization without further training, by utilizing properties of the quantized space to extract aspect-specific summaries.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_7" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Data-Efficient Cross-Lingual Natural Language Processing<br><b>Presenter:</b> Barbara Plank<br><b>Bio:</b><p class="par_panel_perso">Barbara Plank is Professor in Computer Science and Head of the MSc in Data Science at ITU (IT University of Copenhagen). She received her PhD in Computational Linguistics from the University of Groningen. She is interested in research at the cross-roads of Natural Language Processing, Machine Learning, Cognitive Science and Vision, with a particular interest for learning under limited supervision and language variation (language shift, domain shifts, genre shifts etc). Barbara has co-authored over 90 publications, including four best paper awards. She currently holds a DFF Sapere Aude researcher leader grant from the Independent Research Fund Denmark. She co-organized international workshops and conferences (including EurNLP, NoDaLiDa and workshops on domain adaptation, weak supervision and computational social science). Barbara is currently member of the advisory board of the European Association for Computational Linguistics (EACL), ACL publicity director and vice-president of the Northern European Association for Language Technology (NEALT).</p><b>Abstract:</b><p class="par_panel_perso">NLP today depends on huge amounts of unlabeled data, however, for many scenarios including low-resource languages and language varieties we do not have access to labeled resources and even unlabeled data might be scarce. In this talk, I will focus on data-efficient cross-lingual NLP. On the one side, I will outline methods on how to transfer models to low-resource languages. On the other side, I will argue for broader evaluation in cross-lingual learning to include dimensions of variation of language [1]. I'll showcase this on some of our recent work which includes NLP for Danish [4,2], cross-lingual task-oriented dialogues [2] and exploring genre as weak supervision signal for cross-lingual dependency parsing [3].<br>References:<br>[1] Barbara Plank. What to do about non-standard (or non-canonical) language in NLP. In KONVENS 2016. Bochum, Germany.<br>[2] Rob van der Goot, Ibrahim Sharaf, Aizhan Imankulova, Ahmet Üstün, Marija Stepanović, Alan Ramponi, Siti Oryza Khairunnisa, Mamoru Komachi and Barbara\ Plank. From Masked-Language Modeling to Translation: Non-English Auxiliary Tasks Improve Zero-shot Spoken Language Understanding. In NAACL 2021.<br>[3] Max Müller-Eberstein, Rob van der Goot and Barbara Plank. Genre as Weak Supervision for Cross-lingual Dependency Parsing. In EMNLP 2021.<br>[4] Barbara Plank, Kristian Nørgaard Jensen and Rob van der Goot. DaN+ - Danish Nested Named Entities and Lexical Normalization. In COLING 2020.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_8" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> From model compression to self-distillation: a review<br><b>Presenter:</b> Samira Ebrahimi Kahou<br><b>Bio:</b><p class="par_panel_perso">Samira is an Associate Professor at École de technologie supérieure/Mila, Adjunct Professor at McGill and a Canada CIFAR AI Chair. Before joining ÉTS, she was a postdoctoral fellow working with Professor Doina Precup at McGill/Mila. Before her postdoc, she was a researcher at Microsoft Research Montréal. She received her Ph.D. from Polytechnique Montréal/Mila in 2016 under the supervision of Professor Chris Pal. She worked on model compression applied to deep convolutional neural networks with Rich Caruana and knowledge distillation during her Ph.D. at Mila.</p><b>Abstract:</b><p class="par_panel_perso">In this short talk, she presents some of the major milestones in model compression and knowledge distillation, starting with the seminal work of Buciluǎ et al. She also covers applications of knowledge distillation in cross-modal learning, few-shot learning, reinforcement learning and natural language processing.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_11" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> A versatile and efficient approach to summarize speech into utterance-level representations<br><b>Presenter:</b> Joao B Monteiro<br><b>Authors:</b><p class="par_panel_perso">Joao B Monteiro (Institut National de la Recherche Scientifique)*; Jahangir  Alam (Computer Research Institute of Montreal (CRIM), Montreal (Quebec) Canada); Tiago H Falk (INRS-EMT)</p><b>Abstract:</b><p class="par_panel_perso">Time delay neural networks (TDNN) have become ubiquitous for voice biometrics and language recognition tasks relying on utterance-level speaker- or language-dependent representations. In this paper, we discuss directions to improve upon the conventional TDNN architecture to render it more generally applicable. More specifically, we explore the utility of performing pooling operations across different levels of the convolutional stack and further propose an approach to efficiently combine such set of representations. We show that the resulting models are more versatile, in the sense that a fixed architecture can be re-used across different tasks, and learned representations are more discriminative. Evaluations are performed across two settings: (1) two sub-tasks for spoofing attack detection, and (2) three sub-tasks for spoken language identification. Results show the proposed design yielding improvements over the original TDNN architecture, as well as other previously proposed methods.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_12" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Towards Zero and Few-shot Knowledge-seeking Turn Detection in Task-orientated Dialogue Systems<br><b>Presenter:</b> Di Jin<br><b>Authors:</b><p class="par_panel_perso">Di Jin (Amazon Alexa AI)*; Shuyang Gao (Amazon); Seokhwan Kim (Amazon Alexa AI); Yang Liu (Amazon, Alexa AI); Dilek Z Hakkani-Tur (Amazon Alexa AI)</p><b>Abstract:</b><p class="par_panel_perso">Most prior work on task-oriented dialogue systems is restricted to  supporting domain APIs. However, users may have requests that are out of the scope of these APIs. This work focuses on identifying such user requests. Existing methods for this task mainly rely on fine-tuning pre-trained models on large annotated data. We propose a novel method, REDE, based on adaptive representation learning and density estimation. REDE can be applied to zero/few-shots cases, and quickly learn a high-performing detector that is comparable to the full-supervision setting with only a few shots by updating less than 3K parameters. We demonstrate REDE's competitive performance on DSTC9 Track 1 dataset and our newly collected test set.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_13" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Consistent Accelerated Inference via Confident Adaptive Transformers<br><b>Presenter:</b> Tal Schuster <br><b>Authors:</b><p class="par_panel_perso">Tal Schuster (MIT CSAIL)*; Adam Fisch (MIT); Tommi Jaakkola (MIT); Regina Barzilay (MIT CSAIL)</p><b>Abstract:</b><p class="par_panel_perso">We develop a novel approach for confidently accelerating inference in the large and expensive multilayer Transformers that are now ubiquitous in natural language processing (NLP). Amortized or approximate computational methods increase efficiency, but can come with unpredictable performance costs. In this work, we present CATs---Confident Adaptive Transformers---in which we simultaneously increase computational efficiency, while \emph{guaranteeing} a specifiable degree of consistency with the original model with high confidence. Our method trains additional prediction heads on top of intermediate layers, and dynamically decides when to stop allocating computational effort to each input using a meta consistency classifier. To calibrate our early prediction stopping rule, we formulate a unique extension of conformal prediction. We demonstrate the effectiveness of this approach on four classification and regression tasks.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_14" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Communication-Efficient Federated Learning for Neural Machine Translation<br><b>Presenter:</b> Tanya Roosta <br><b>Authors:</b><p class="par_panel_perso">Tanya G Roosta (Amazon)*; Peyman Passban (Amazon); Ankit R Chadha (Amazon)</p><b>Abstract:</b><p class="par_panel_perso">Training neural machine translation (NMT) models in federated learning (FL) settings could be inefficient both computationally and communication-wise, due to the large size of translation engines as well as the multiple rounds of updates required to train clients and a central server. In this paper, we explore how to efficiently build NMT models in an FL setup by proposing a novel solution. In order to reduce the communication overhead, out of all neural layers we only exchange what we term ``Controller'' layers.  Controllers are a small number of additional neural components connected to our pre-trained architectures. These new components are placed in between original layers. They act as liaisons to communicate with the central server and learn minimal information that is sufficient enough to update clients.   We evaluated the performance of our models on five datasets from different domains to translate from German into English. We noted that the models equipped with Controllers preform on par with those trained in a central and non-FL setting. In addition, we observed a substantial reduction in the communication traffic of the FL pipeline, which is a direct consequence of using Controllers. Based on our experiments, Controller-based models are 6 times less expensive than their other peers. This reduction is significantly important when we consider the number of parameters in large models and it becomes even more critical when such parameters need to be exchanged for multiple rounds in FL settings.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_15" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Dynamic-TinyBERT: Further Enhance the Inference Efficiency of TinyBERT by Dynamic Sequence Length<br><b>Presenter:</b> Shira Guskin<br><b>Authors:</b><p class="par_panel_perso">Shira Guskin (Intel)*; Moshe Wasserblat (Intel); Ke Ding (Intel); Gyuwan Kim ()</p><b>Abstract:</b><p class="par_panel_perso">Limited computational budgets often prevent transformers from being used in production and from having their high accuracy utilized. TinyBERT addresses the computational efficiency by self-distilling BERT into a smaller transformer representation having fewer layers and smaller internal embedding. However, TinyBERT's performance drops when we reduce the number of layers by 50\%, and drops even more abruptly when we reduce the number of layers by 75\% for advanced NLP tasks such as span question answering.  Additionally, a separate model must be trained for each inference scenario with its distinct computational budget.  In this work we present Dynamic-TinyBERT, a TinyBERT model that utilizes sequence-length reduction and Hyperparameter Optimization for enhanced inference efficiency per any computational budget. Dynanic-TinyBERT is trained only once, performing on-par with BERT and achieving an accuracy-speedup trade-off superior to any other efficient approaches (up to 3.3x with <1\% loss-drop). Upon publication, the code to reproduce our work will be open-sourced.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_16" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> CTR-BERT: Cost-effective knowledge distillation for billion-parameter teacher models<br><b>Presenter:</b> TBD<br><b>Authors:</b><p class="par_panel_perso">Aashiq Muhamed (Amazon)*; Iman Keivanloo (Amazon); Sujan Perera (Amazon); James A Mracek (Amazon); Yi Xu (Amazon); Qingjun Cui (Amazon); Santosh Rajagopalan (Amazon); Belinda Zeng (Amazon); Trishul A Chilimbi (Amazon)</p><b>Abstract:</b><p class="par_panel_perso">While pre-trained large language models (LLM) like BERT have achieved state-of-the-art in several NLP tasks, their performance on tasks with additional grounding e.g. with numeric and categorical features is less studied. In this paper, we study the application of pre-trained LLM for Click-through-rate (CTR) prediction for product advertisement in e-commerce. This is challenging because the model needs to a) learn from language as well as tabular data features, b) maintain low-latency (<5 ms) at inference time, and c) adapt to constantly changing advertisement distribution. We first show that scaling the pre-trained language model to 1.5 billion parameters significantly improves performance over conventional CTR baselines. We then present CTR-BERT, a novel lightweight cache-friendly factorized model for CTR prediction that consists of twin-structured BERT-like encoders for text with a mechanism for late fusion for text and tabular features. We train the CTR-BERT model using cross-architecture knowledge distillation (KD) and empirically study the interaction between KD and distribution shift in this setting, by a) experimenting with pre-training, distillation pre-finetuning and fine-tuning strategies b) factorizing features based on their distribution shift time scales, that allows the model to readily adapt and be re-trained. Finally, we show that CTR-BERT significantly outperforms a traditional CTR baseline with a 2.3\% relative ROC-AUC lift in offline experiments and a 2\% CTR lift in an online experiment.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_17" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Cutting Down on Prompts and Parameters:Simple Few-Shot Learning with Language Models<br><b>Presenter:</b> Robert Logan<br><b>Authors:</b><p class="par_panel_perso">Robert L Logan (UC Irvine)*; Ivana Balazevic (University of Edinburgh); Eric Wallace (U.C. Berkeley); Fabio Petroni (Facebook AI Research); Sameer  Singh (University of California, Irvine); Sebastian Riedel ()</p><b>Abstract:</b><p class="par_panel_perso">Prompting language models (LMs) with training examples and task descriptions has been seen as critical to recent successes in few-shot learning. In this work, we show that finetuning LMs in the few-shot setting can considerably reduce the need for prompt engineering. In fact, one can use null prompts, prompts that contain neither task-specific templates nor training examples, and achieve competitive accuracy to manually-tuned prompts across a wide range of tasks. While finetuning LMs does introduce new parameters for each downstream task, we show that this memory overhead can be substantially reduced: finetuning only the bias terms can achieve comparable or better accuracy than standard finetuning while only updating 0.1% of the parameters. All in all, we recommend finetuning LMs for few-shot learning as it is more accurate, robust to different prompts, and can be made nearly as efficient as using frozen LMs.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_18" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Weight, Block or Unit? Exploring Sparsity Tradeoffs for Speech Enhancement on Tiny Neural Accelerators<br><b>Presenter:</b> Marko Stamenovic<br><b>Authors:</b><p class="par_panel_perso">Marko Stamenovic (Bose)*; Li-Chia Yang (Bose); Nils Westhausen (University of Oldenburg); Carl Jensen (Bose); Alex Pawlicki (Bose)</p><b>Abstract:</b><p class="par_panel_perso">We explore network sparsification strategies with the aim of compressing neural speech enhancement (SE) down to an optimal configuration for a new generation of low power microcontroller based neural accelerator (microNPU's). We examine three unique sparsity structures: weight pruning, block pruning and unit pruning; and discuss their benefits and drawbacks when applied to SE. We focus on the interplay between computational throughput, memory footprint and model quality. Our method supports all three sparsity structures above and jointly learns integer quantized weights along with sparsity, alleviating the need for tedious manual fine-tuning. Additionally, we demonstrate offline magnitude based pruning of integer quantized models as a performance baseline. Although efficient speech enhancement is an active area of research, our work is the first to apply block pruning to SE and the first to address SE model compression in the context of microNPU's. Using weight pruning, we show that we are able to compress an already compact model's memory footprint by a factor of 42X from 3.7MB to 87kB while only losing 0.1 dB SDR in performance. We also show a computational speedup of 6.7X with a corresponding SDR drop of only 0.59 dB SDR using block pruning.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_19" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> How to Win LMs and Influence Predictions: Using Short Phrases to Control NLP Models<br><b>Presenter:</b> Sameer Singh<br><b>Bio:</b><p class="par_panel_perso">Dr. Sameer Singh is an Associate Professor of Computer Science at the University of California, Irvine (UCI) and an Allen AI Fellow at Allen Institute for AI. He is working primarily on robustness and interpretability of machine learning algorithms, along with models that reason with text and structure for natural language processing. Sameer was a postdoctoral researcher at the University of Washington and received his PhD from the University of Massachusetts, Amherst. He has received the NSF CAREER award, selected as a DARPA Riser, UCI Distinguished Early Career Faculty award, and the Hellman Faculty Fellowship. His group has received funding from Allen Institute for AI, Amazon, NSF, DARPA, Adobe Research, Hasso Plattner Institute, NEC, Base 11, and FICO. Sameer has published extensively at machine learning and natural language processing venues and received conference paper awards at KDD 2016, ACL 2018, EMNLP 2019, AKBC 2020, and ACL 2020. (https://sameersingh.org/)</p><b>Abstract:</b><p class="par_panel_perso">Current NLP pipelines rely significantly on finetuning large pre-trained language models. Relying on this paradigm makes such pipelines challenging to use in real-world settings since massive task-specific models are neither memory- nor inference-efficient, nor do we understand how they fare in adversarial settings. This talk will describe our attempts to address these seemingly unrelated concerns by investigating how specific short phrases in the input can control model behavior. These short phrases (which we call triggers) will help us identify model vulnerabilities and introduce new paradigms of training models.<br>In the first part of the talk, I will focus on the adversarial setting. I will show how easy it is for adversaries to craft triggers that cause a target model to misbehave when the trigger appears in the input. In the second part of the talk, I will show how these triggers can also be used to “prompt” language models to act as task-specific models, providing a negligible-memory, no-learning way to create classifiers. I will end with a comprehensive study of the interplay between prompting and finetuning, providing some guidelines for effectively performing few-shot learning with large language models.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_20" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Benchmarks for Multi-objective Hyperparameter Optimization<br><b>Presenter:</b> Kevin Duh<br><b>Bio:</b><p class="par_panel_perso">Kevin Duh is a senior research scientist at the Johns Hopkins University Human Language Technology Center of Excellence (JHU HLTCOE). He is also an assistant research professor in the Department of Computer Science and a member of the Center for Language and Speech Processing (CLSP). His research interests lie at the intersection of Natural Language Processing and Machine Learning, in particular on areas relating to machine translation, semantics, and deep learning. Previously, he was assistant professor at the Nara Institute of Science and Technology (2012-2015) and research associate at NTT CS Labs (2009-2012). He received his B.S. in 2003 from Rice University, and PhD in 2009 from the University of Washington, both in Electrical Engineering.</p><b>Abstract:</b><p class="par_panel_perso">The speed, size, and accuracy of deep neural networks often depend on hyperparameters such as network depth and architecture type. Hyperparameter optimization and neural architecture search are promising techniques that help developers build the best-possible network under budget constraints. I will discuss the importance of building benchmarks to evaluate these techniques in a multi-objective way. By incorporating multiple objectives such as training time, inference speed, and model size into hyperparameter optimization, we ensure a more holistic evaluation of the entire model development and deployment process.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_21" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> NLP with Synthetic Text<br><b>Presenter:</b> Mohammad Norouzi<br><b>Bio:</b><p class="par_panel_perso">Mohammad Norouzi is a staff research scientist on the Google Brain team in Toronto. He is interested in self-supervised representation learning, generative models, and the use of generative models in advancing machine learning. He has contributed to several recent work on diffusion probabilistic models and was a co-developer of Google's neural machine translation system and SimCLR for learning visual representations.</p><b>Abstract:</b><p class="par_panel_perso">Synthetic data is successfully used to train powerful machine learning models for computer vision and robotics, thanks to the availability of high-fidelity graphics and physics-based simulation. But, can synthetic data be successfully used to improve natural language processing? In this talk, I will advocate for the use of large language models as a great source of synthetic text. I will review recent work on data augmentation for NLP and describe a general framework for NLP with synthetic text, called “Generate, Annotate, and Learn”. I will highlight a few key results on generating unlabeled text for improving semi-supervised learning and knowledge distillation, in addition to advancing GPT3-style few-shot learning.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_23" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Toward Efficient Training of Large Language Models with Balanced Conditional Compute<br><b>Presenter:</b> Luke Zettlemoyer<br><b>Bio:</b><p class="par_panel_perso">Luke Zettlemoyer is a Professor in the Paul G. Allen School of Computer Science & Engineering at the University of Washington and a Research Scientist at Meta. His research focuses on empirical methods for natural language semantics, and involves designing machine learning algorithms, introducing new tasks and datasets, and, most recently, studying how to best develop self-supervision signals for pre-training. Honors include multiple paper awards, a PECASE award, and an Allen Distinguished Investigator Award. Luke received his PhD from MIT and was a postdoc at the University of Edinburgh.</p><b>Abstract:</b><p class="par_panel_perso">The trend of building ever larger language models has dominated much research in NLP over the last few years. However, we have reached a point where dense compute is difficult to scale further, and there is a need for new, more efficient model architectures. In this talk, I will cover our recent efforts on learning sparse mixtures of experts (MoEs) models, which have new explicitly balanced control mechanisms for allocating conditional compute. This includes BASE Layers, where the routing of experts to tokens is algorithmically assigned to ensure balanced scaling across compute nodes, and DEMix Layers, where we introduce new modular approaches for deterministic expert routing based on metadata that specifies the domain of the input text. Overall, our sparse approaches have significantly reduced cross-node communication costs and could possibly provide the next big leap in performance, although finding a version that scales well in practice remains an open challenge.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_24" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Why We Want Contrastive Learning in Language Models<br><b>Presenter:</b> Danqi Chen<br><b>Bio:</b><p class="par_panel_perso">Danqi Chen is an assistant professor of computer science at Princeton University and co-leads the Princeton NLP Group. Her research focuses on representation learning, knowledge gathering & reasoning, and developing practical systems for question answering and information extraction. Before joining Princeton, Danqi worked as a visiting scientist at Facebook AI Research. She received her Ph.D. from Stanford University (2018) and B.E. from Tsinghua University (2012), both in Computer Science.</p><b>Abstract:</b><p class="par_panel_perso">Contrastive learning aims to learn representations such that similar samples stay close to each other while dissimilar ones are far apart. Recently, it has achieved great success in self-supervised learning of visual representations and even surpassed its supervised counterparts. In this talk, I will argue why contrastive learning may provide new solutions in language model pre-training and fine-tuning. I will first describe our recent work SimCSE on how contrastive learning can be used with pre-trained language models to produce universal sentence representations. And then, I will discuss why contrastive learning can potentially lead to better pre-trained representations. I hope this talk can shed light on some limitations of pre-trained language representations as well as why contrastive learning is a great idea to tackle these problems.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_25" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Battling with Larger Models through Grounding and Searching<br><b>Presenter:</b> Yejin Choi<br><b>Bio:</b><p class="par_panel_perso">Yejin Choi is Brett Helsel professor at the Paul G. Allen School of Computer Science & Engineering at the University of Washington and also a senior research manager at AI2 overseeing the project Mosaic. Her research interests include commonsense knowledge and reasoning, neural language (de-)generation, language grounding with vision and perception, and AI for social good. She is a co-recepient of the ACL Test of Time award in 2021, the CVPR Longuet-Higgins Prize (test of time award) in 2021, the AAAI Outstanding Paper Award (best paper award) in 2020, the Borg Early Career Award (BECA) in 2018, the inaugural Alexa Prize Challenge in 2017, IEEE AI's 10 to Watch in 2016, and the Marr Prize (best paper award) at ICCV 2013. She received her Ph.D. in Computer Science at Cornell University and BS in Computer Science and Engineering at Seoul National University in Korea.</p><b>Abstract:</b><p class="par_panel_perso">Scale appears to be the winning recipe in today's leaderboards. And yet, extreme-scale neural models are still brittle and make errors that are nonsensical or even counterintuitive. In this talk, I will discuss how smaller models developed in academia can still have an edge over larger industry-scale models, if powered with grounding and searching. First, I will present MERLOT (and RESERVE) that can learn neural script knowledge from complex multimodal data and achieve new SOTA over a dozen multimodal benchmarks. Next, I will discuss NeuralLogic (and NeuralLogic A*) search algorithms that can integrate logic constraints to language model decoding so that smaller unsupervised models can win over larger supervised models for various constrained generation tasks.</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_27" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Panel Discussion<br><b>Presenter:</b> Pascal Poupart<br>Ali Ghodsi<br>Luke Zettlemoyer<br>Sameer Singh<br>Kevin Duh<br>Yejin Choi<br>Lu Hou<br><b>Bio:</b><p class="par_panel_perso">TBD</p><b>Abstract:</b><p class="par_panel_perso">TBD</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div><div class="modal fade" id="talk_28" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true"><div class="modal-dialog"><div class="modal-content"><div class="modal-body"><b>Title:</b> Best Papers and Closing Remarks<br><b>Presenter:</b> Pascal Poupart & Ali Ghodsi<br><b>Bio:</b><p class="par_panel_perso">TBD</p><b>Abstract:</b><p class="par_panel_perso">TBD</p></div><div class="modal-footer"><button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button></div></div></div></div>

<!-- -->

<div class="row">
	<table id="customers">
		<tr>
			<th>Time</th>
			<th colspan="2">Title</th>
			<th>Presenter</th>
		</tr>
		
		
		<!-- insert table here -->
		
		
		<tr><td>08:00 AM - 08:10 AM</td><td> Opening Speech</td><td></td><td>Pascal Poupart</td></tr><tr><td>08:10 AM - 08:50 AM</td><td>Continual Learning in Large-Scale Pre-Training</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_2"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Xu Sun</td></tr><tr><td>08:50 AM - 09:30 AM</td><td>Efficient Multi-lingual Neural Machine Translation</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_3"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Boxing Chen</td></tr><tr><td>09:30 AM - 10:10 AM</td><td>Compression and Acceleration of Pre-trained Language Models</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_4"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Lu Hou</td></tr><tr><td>10:10 AM - 10:20 AM</td><td colspan='3'>Break</td></tr><tr><td>10:20 AM - 11:00 AM</td><td>Summarization in Quantized Transformer Spaces</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_6"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Mirella Lapata</td></tr><tr><td>11:00 AM - 11:40 AM</td><td>Data-Efficient Cross-Lingual Natural Language Processing</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_7"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Barbara Plank</td></tr><tr><td>11:40 AM - 12:20 PM</td><td>From model compression to self-distillation: a review</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_8"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Samira Ebrahimi Kahou</td></tr><tr><td>12:20 PM - 01:00 PM</td><td colspan='3'>Break</td></tr><tr><td>12:20 PM - 01:20 PM</td><td>Poster session</td><td></td><td></td></tr><tr><td>01:20 PM - 01:25 PM</td><td>A versatile and efficient approach to summarize speech into utterance-level representations</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_11"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Joao B Monteiro</td></tr><tr><td>01:25 PM - 01:30 PM</td><td>Towards Zero and Few-shot Knowledge-seeking Turn Detection in Task-orientated Dialogue Systems</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_12"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Di Jin</td></tr><tr><td>01:30 PM - 01:35 PM</td><td>Consistent Accelerated Inference via Confident Adaptive Transformers</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_13"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Tal Schuster </td></tr><tr><td>01:35 PM - 01:40 PM</td><td>Communication-Efficient Federated Learning for Neural Machine Translation</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_14"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Tanya Roosta </td></tr><tr><td>01:40 PM - 01:45 PM</td><td>Dynamic-TinyBERT: Further Enhance the Inference Efficiency of TinyBERT by Dynamic Sequence Length</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_15"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Shira Guskin</td></tr><tr><td>01:45 PM - 01:50 PM</td><td>CTR-BERT: Cost-effective knowledge distillation for billion-parameter teacher models</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_16"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>TBD</td></tr><tr><td>01:50 PM - 01:55 PM</td><td>Cutting Down on Prompts and Parameters:Simple Few-Shot Learning with Language Models</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_17"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Robert Logan</td></tr><tr><td>01:55 PM - 02:00 PM</td><td>Weight, Block or Unit? Exploring Sparsity Tradeoffs for Speech Enhancement on Tiny Neural Accelerators</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_18"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Marko Stamenovic</td></tr><tr><td>02:00 PM - 02:40 PM</td><td>How to Win LMs and Influence Predictions: Using Short Phrases to Control NLP Models</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_19"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Sameer Singh</td></tr><tr><td>02:40 PM - 03:20 PM</td><td>Benchmarks for Multi-objective Hyperparameter Optimization</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_20"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Kevin Duh</td></tr><tr><td>03:20 PM - 04:00 PM</td><td>NLP with Synthetic Text</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_21"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Mohammad Norouzi</td></tr><tr><td>04:00 PM - 04:10 PM</td><td colspan='3'>Break</td></tr><tr><td>04:10 PM - 04:50 PM</td><td>Toward Efficient Training of Large Language Models with Balanced Conditional Compute</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_23"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Luke Zettlemoyer</td></tr><tr><td>04:50 PM - 05:30 PM</td><td>Why We Want Contrastive Learning in Language Models</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_24"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Danqi Chen</td></tr><tr><td>05:30 PM - 06:10 PM</td><td>Battling with Larger Models through Grounding and Searching</td><td><center><a href="" data-bs-toggle="modal" data-bs-target="#talk_25"><i class="bi bi-info-circle" style="font-size: 1.4rem;"></i></a></center></td><td>Yejin Choi</td></tr><tr><td>06:10 PM - 06:15 PM</td><td colspan='3'>Break</td></tr><tr><td>06:15 PM - 07:00 PM</td><td> Panel Discussion </td><td></td><td>Pascal Poupart<br>Ali Ghodsi<br>Luke Zettlemoyer<br>Sameer Singh<br>Kevin Duh<br>Yejin Choi<br>Lu Hou</td></tr><tr><td>07:00 PM - 07:10 PM</td><td> Best Papers and Closing Remarks </td><td></td><td>Pascal Poupart & Ali Ghodsi</td></tr><tr><td>07:10 PM - 08:00 PM</td><td>Poster session</td><td></td><td></td></tr>
		
		
		<!-- -->

	</table>
</div>


<br> <br>
<!-- Organizers -->
<h2 class="blackpar_title" id="Organizers">Organizers</h2>
<div class="row_perso">
	<div class="card_perso column_perso" style="margin-left:13%;">
	  <img src="/images/Mehdi_Rezagholizadeh.jpg" alt="Mehdi Rezagholizadeh" class="img_card_perso">
	  <div class="container_perso" >
		<center>
		<h6>
			<b>Mehdi Rezagholizadeh</b>
			<br>
			Huawei Noah's Ark Lab
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/lili_mou.jpg" alt="Lili Mou" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Lili Mou</b>
			<br>
			University of Alberta
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso" >
	  <img src="/images/Yue_Dong.jpg" alt="Yue Dong" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Yue Dong</b>
			<br>
			McGill University & MILA
		</h6>
		</center>
	  </div>
	</div>

</div>
<div class="row_perso">
	<div class="card_perso column_perso" style="margin-left:13%;">
	  <img src="/images/pascal_poupart.jpg" alt="Pascal Poupart" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Pascal Poupart</b>
			<br>
			University of Waterloo
		</h6>
		</center>
	  </div>
	</div>

	<div class="card_perso column_perso" >
	  <img src="/images/ali_ghodsi.jpg" alt="Ali Ghodsi" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Ali Ghodsi</b>
			<br>
			University of Waterloo
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/qun_liu.png" alt="Qun Liu" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Qun Liu</b>
			<br>
			Huawei Noah's Ark Lab
		</h6>
		</center>
	  </div>
	</div>
</div>
<h2 class="blackpar_title" id="Organizers">Volunteers</h2>
<div class="row_perso">
	<div class="card_perso column_perso" style="margin-left:25%;">
	  <img src="/images/khalil_bibi.png" alt="Khalil Bibi" class="img_card_perso">
	  <div class="container_perso" >
		<center>
		<h6>
			<b>Khalil Bibi</b>
			<br>
			Huawei Noah's Ark Lab
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/anderson_avilla.jpg" alt="Anderson Avilla" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Andrson Avilla</b>
			<br>
			Huawei Noah's Ark Lab
		</h6>
		</center>
	  </div>
	</div>


</div>


<br><br>
<!-- Technical Committee -->
<h2 class="blackpar_title" id="Technical Committee">Technical Committee</h2>
<table>
	<tr>
		<td>
			<ul>
				<li>Pascal Poupart (UoWaterloo)</li>
				<li>Kevin Duh (Johns Hopkins University)</li>
				<li>Wulong Liu (Huawei Noah's Ark Lab)</li>
				<li>Bang Liu (UoMontreal)</li>
				<li>Di Jin (Amazon Alexa AI)</li>
				<li>Hamidreza Mahyar (McMaster University)</li>
				<li>Lili Mou (UoAlberta)</li>
				<li>Peyman Passban (Amazon)</li>
				<li>Prasanna Parthasarathi (McGill & MILA)</li> 
				<li>Vahid Partovi Nia (Huawei Noah's Ark Lab)</li>
				<li>Yue Dong (McGill  & MILA)</li>
				<li>Ivan Kobyzev (Huawei Noah's Ark Lab)</li>
				<li>Jad Kabbara (McGill  & MILA)</li> 
				<li>Aref Jafari (UoWaterloo)</li> 
				<li>Ahmad Rashid (Huawei Noah's Ark Lab)</li> 
				<li>Shailza Jolly (TU Kaiserslautern)</li> 
				<li>Md. Akmal Haidar (Nuance Communications)</li> 
				<li>Jingjing Xu (ByteDance)</li> 
				<li>Vasileios Lioutas (UoBritish Colombia (UBC))</li> 
				<li>Anderson R. Avila (Huawei Noah's Ark Lab)</li> 
				<li>Malik H. Altakrori (McGill & MILA)</li> 
				<li>Ali Vahdat (Thomson Reuters)</li> 
				<li>Fattane Zarrinkalam (Thomson Reuters)</li> 
				<li>Makesh S Narsimhan (McGill & MILA)</li> 
				<li>Borna Jafarpour (Thomson Reuters)</li> 
				<li>Shohreh Shaghaghian (Thomson Reuters)</li> 
				<li>Ehsan Kamalloo (UoAlberta)</li>
				<li>Ali Saheb Pasand (UoWaterloo)</li>
			</ul>
		</td>
		<td>
			<ul>
				<li>Abbas Ghaddar (Huawei Noah's Ark Lab)</li>
				<li>Mehrdad Ganjeh (Ernst & Young (EY))</li>
				<li>Mingxuan Wang (ByteDance)</li>
				<li>Tanya Roosta (Amazon)</li>
				<li>Soheila Samiee (BASF)</li>
				<li>Yimeng Wu (Huawei Noah's Ark Lab)</li>
				<li>Marzieh Tahaei (Huawei Noah's Ark Lab)</li>
				<li>Habib Hajimolahoseini (Huawei Technologies)</li>
				<li>Mohammad Salameh (Huawei Technologies)</li>
				<li>Kira Aveline Selby (UoWaterloo)</li>
				<li>Mohammed Senoussaoui (Fluent.ai)</li>
				<li>M. Sarria-Paja (Universidad Santiago de Cali)</li>
				<li>Puneeth Saladi (Huawei Noah's Ark Lab)</li>
				<li>Flávio Ávila (Verisk Analytics)</li>
				<li>Tal Schuster (MIT)</li>
				<li>Irene Li (Yale)</li>
				<li>Shentong Mo (Carnegie Mellon University)</li>
				<li>Alpana Agarwal (Thapar University)</li>
				<li>Vinay Kumar (Thapar University)</li>
				<li>Shivani Malhotra (TIET Patiala)</li>
				<li>Iman Keivanloo (Amazon)</li>
				<li>Aashiq Muhamed (Amazon)</li>
				<li>Robert L. Logan IV (UCI University)</li>
				<li>Patrick Xia (Johns Hopkins University)</li>
				<li>Moshe Wasserblat (Intel)</li>
				<li>Guy Boudoukh (Intel)</li>
				<li>Ankit Chadha (Amazon)</li>
				<li>Khalil Bibi (Huawei Noah's Ark Lab)</li>
				<li>David Alfonso Hermelo (Huawei Noah's Ark Lab)</li>
			</ul>
		</td>
	</tr>
</table>


<!--
<ul>
	<li>Ali Ghodsi (University of Waterloo)</li>
	<li>Bang Liu (University of Montreal (UDM))</li>
	<li>Di Jin (Amazon Alexa AI)</li>
	<li>Hamidreza Mahyar (McMaster University)</li>
	<li>Kevin Duh (Johns Hopkins University)</li>
	<li>Lili Mou (University of Alberta)</li>
	<li>Pascal Poupart (University of Waterloo)</li>
	<li>Peyman Passban (Amazon)</li>
	<li>Prasanna Parthasarathi (McGill University & MILA)</li> 
	<li>Vahid Partovi Nia (Huawei Noah's Ark Lab)</li>
	<li>Wulong Liu (Huawei Noah's Ark Lab)</li>
	<li>Yue Dong (McGill University & MILA)</li>
	<li>Ivan Kobyzev (Huawei Noah's Ark Lab)</li>
	<li>Jad Kabbara (McGill University & MILA)</li> 
	<li>Aref Jafari (University of Waterloo)</li> 
	<li>Ahmad Rashid (Huawei Noah's Ark Lab)</li> 
	<li>Shailza Jolly (TU Kaiserslautern)</li> 
	<li>Md. Akmal Haidar (Huawei Noah's Ark Lab)</li> 
	<li>Jingjing Xu (ByteDance)</li> 
	<li>Vasileios Lioutas (University of British Colombia (UBC))</li> 
	<li>Anderson R. Avila (Huawei Noah's Ark Lab)</li> 
	<li>Malik H. Altakrori (Mc Gill University & MILA)</li> 
	<li>Ali Vahdat (Thomson Reuters)</li> 
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
	<li>Yimeng Wu (Huawei Noah's Ark Lab)</li>
	<li>Omar Mohamed Awad (Huawei Technologies)</li>
	<li>Marzieh Tahaei (Huawei Noah's Ark Lab)</li>
	<li>Habib Hajimolahoseini (Huawei Technologies)</li>
	<li>Mohammad Salameh (Huawei Technologies)</li>
	<li>Kira Aveline Selby (University of Waterloo)</li>
	<li>Mohammed Senoussaoui (Fluent.ai)</li>
	<li>M. Sarria-Paja (Universidad Santiago de Cali)</li>
	<li>Puneeth Saladi (Huawei Noah's Ark Lab)</li>
	<li>Flávio Ávila (Verisk Analytics)</li>
	<li>Tal Schuster (MIT)</li>
	<li>Irene Li (Yale)</li>
	<li>Rongsheng Zhang</li>
	<li>Shentong Mo (Carnegie Mellon University)</li>
	<li>Alpana Agarwal (Thapar Institute of Engineering & Technology)</li>
	<li>Vinay Kumar (Thapar Institute of Engineering & Technology)</li>
	<li>Shivani Malhotra (Thapar Institute of Engineering & Technology)</li>
	<li>Iman Keivanloo (Amazon)</li>
	<li>Aashiq Muhamed (Amazon)</li>
	<li>Robert L. Logan IV (UCI University)</li>
	<li>Patrick Xia (Johns Hopkins University)</li>
	<li>Moshe Wasserblat (Intel)</li>
	<li>Guy Boudoukh (Intel)</li>
	<li>Ankit Chadha (Amazon)</li>
	<li>Khalil Bibi (Huawei Noah's Ark Lab)</li>
</ul>
-->
<br><br>
<h2 class="blackpar_title">Sponsor</h2>
<center>
	<img src="/images/logos.png">
	
</center>