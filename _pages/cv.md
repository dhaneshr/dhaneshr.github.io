---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links" markdown="0" style="margin-bottom: 2em;">
  <a href="{{ base_path }}/files/Dhanesh_Ramachandram_CV.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>

Professional Profile
======
I am a seasoned machine learning researcher and applied scientist with a strong focus on healthcare AI: clinical dataset design, interpretable/explainable modeling, and translating research into deployed clinical systems. I have a proven track record in machine learning and medical image analysis research, having achieved an h-index of 17 with over 1,900 citations to date. My expertise spans applied machine learning and deep learning for healthcare, including clinical dataset curation and evaluation, deep survival analysis for competing clinical risks, interpretable/explainable AI (concept bottleneck models, neural additive models), LLM- and RAG-based clinical systems, and biomedical image analysis (semantic/instance segmentation, object detection, image classification). I have led clinical AI deployments at hospital sites, large-scale healthcare data annotation and extraction pipelines, and system-level interpretability research for agentic AI.

Experience
======
* **Aug 2023 &ndash; Present: Applied Machine Learning Scientist &mdash; Health Lead**
  * [Vector Institute for AI](https://www.vectorinstitute.ai), Toronto, ON
  * Designed and deployed **CRISPNAM-FG**, an intrinsically interpretable Fine-Gray competing-risks deep survival model, into production at St. Michael's Hospital to flag diabetic patients at high risk of post-discharge foot complications; built on a retrospective cohort of 107,000+ patients across 29 Ontario hospitals (GEMINI database) and packaged the full deployment stack (Python wrapper around an R model, Flask UI, Docker containerization).
  * Led an end-to-end document data-extraction pipeline (OLTCA project) combining Python PDF parsers (PyPDF2, pdfplumber, PyMuPDF) with LLM/OCR APIs (GPT-4, Google Document AI, DeepSeek OCR) to structure 37,000+ Ontario long-term-care inspection reports into a query-able dataset at &ge;90% target accuracy; delivered the codebase, searchable database, technical report and handoff.
  * Led Vector's Interpretability Bootcamp (Apr&ndash;May 2025): organized 40+ participants across 12 teams, delivered lectures and hands-on mentorship, and produced 16 reference implementations of post-hoc and intrinsically interpretable models across tabular, NLP and imaging modalities; co-authored the resulting white paper (arXiv:2507.23535).
  * Co-lead of Vector's Interpretability Focus Area; scoped and directed research projects on interpretable deep survival modeling and vision-language model interpretability, including concept bottleneck models for radiology grounded via retrieval-augmented citation and verification.
  * Scientific advisor for an LLM-based classification system for long-context clinical conversations (CAMH), advising on deployment infrastructure, data security, licensing, labeling tooling and data readiness.
  * Technical lead for an ultrasound lymph-node detection/segmentation project: extended a 2D object detection model to a 2.5D volumetric pipeline and applied positive-unlabeled learning to address limited ground truth.
  * Scientific advisor for a clinical Text-to-SQL system: conducted cohort evaluation and literature review, and built a reference LightRAG-based implementation adopted by the delivery team.
  * Scientific advisor for a surgeme classification and needle tracking project: building a model of action classification for surgical video and tracking needle-keypoints for robot-assisted surgery.
  * Contributed statistical process control-based drift/monitoring methods to Cyclops, Vector's open-source healthcare ML monitoring toolkit.
  * Technical lead on an EHR comorbidity analytics collaboration (CVD + T2D) with Boehringer-Ingelheim and Diabetes Action Canada, built a survival analysis model, resolving data and HPC infrastructure issues to enable model feature discovery.
  * Mentored 6+ research associates, interns and engineers on interpretable ML, survival analysis and LLM-based systems; supervised delivery of reference implementations and co-authored resulting papers/preprints.
  * Reviewed healthcare AI deployments as technical consultant for the Sunnybrook Vector AI Initiative.

* **Aug 2023 &ndash; Present: Adjunct Professor, School of Engineering**
  * [University of Guelph](https://www.uoguelph.ca), Guelph, ON
  * Co-taught UNIV\*6990 AI and Society (graduate course), developing and delivering lecture content on the AI-in-healthcare landscape across the US/Canada.
  * Covered topics including development and deployment of AI in healthcare domains, bias and fairness in AI, and regulatory/governance aspects of AI deployment in healthcare.
  * Ongoing University of Guelph&ndash;Vector Institute research collaborations for interpretable concept-bottleneck models for biodiversity (fine-grained species) classification.

* **Jan 2018 &ndash; Aug 2023: Staff Machine Learning Scientist**
  * [Swift Medical Inc.](https://www.swiftmedical.com), Toronto, ON
  * Led the research and development of the earliest known commercial implementation of a deep learning-based chronic wound segmentation model for Swift Medical's Skin & Wound app, currently deployed to over 4,100 healthcare facilities in all states of the US and Canada, used on approx. 400,000 wound assessments per week.
  * Led a project to annotate over 55,000 chronic wound tissue images and subsequently developed a mobile-friendly wound tissue segmentation model to aid clinicians in objectively reporting tissue proportions in wound assessments.
  * Implemented a deep learning model to detect Personal Health Information (PHI) in wound images, ensuring HIPAA compliance for imaging data used for building AI models.
  * Led a project to annotate over 100k Pressure Injury Wound images and implemented a multitask deep learning model for Pressure Injury staging, wound depth and skin loss classification.
  * Implemented a Mamdani-type fuzzy inference system for automatic Pressure Injury staging.
  * Researched and implemented self-supervised methods for learning representations using large unlabeled chronic wound image datasets for later fine-tuning on various downstream tasks.
  * Implemented a real-time object detection model for wound and fiducial detection, enabling automatic wound image capture.
  * Formulated the research roadmap for the Clinical AI stream at Swift Medical and managed R&D projects within the stream.
  * Collaborated with cross-functional teams including infrastructure, product, engineering and clinical success teams to ensure successful integration of R&D outputs into products and monitoring model performance metrics post-deployment.
  * Published core research findings in peer-reviewed journals and wound care conferences.

* **Mar 2017 &ndash; Dec 2017: Scientist in Residence**
  * [NextAI](https://www.nextcanada.com/next-ai/), Toronto, ON
  * Provided scientific mentoring and support for machine learning and deep learning challenges for startups in the NextAI startup incubator program.
  * One supported startup, *IntuitiveAI*, won the best-startup award for the 2017 cohort.

* **Dec 2016 &ndash; Nov 2017: Research Fellow, Machine Learning Research Group**
  * [University of Guelph](https://www.uoguelph.ca), Guelph, ON
  * Principal investigator: deep learning for wound and skin lesion segmentation and classification.
  * Developed a novel skin lesion segmentation model based on deep hypercolumn descriptors, leading to a journal publication and Best Paper Award at CVIS 2017.
  * Placed among the top-5 teams in the 2017 ISIC Skin Lesion Classification Challenge.
  * Mentored engineering undergraduates on a web-based super-pixel segmentation tool.

* **Jun 2015 &ndash; Sep 2016: Research Fellow, Machine Learning Research Group**
  * [University of Guelph](https://www.uoguelph.ca), Guelph, ON
  * Research focused on multimodal deep learning involving video, audio and skeletal pose modalities.
  * Conducted performance benchmarking and optimization for 3D-convolutional neural network-based multimodal deep learning architectures.
  * Wrote a highly cited review paper on deep multimodal learning with over 500 citations to date.
  * Co-developed a novel structure optimization method for deep multimodal fusion networks using Bayesian optimization.
  * Implemented various CNN architectures using Theano, Lasagne, and was an early adopter of TensorFlow. Experience using the SharcNet GPU clusters.

* **Sep 2003 &ndash; Jun 2015: Associate Professor**
  * [Universiti Sains Malaysia](https://www.usm.my), Penang, Malaysia
  * Conducted fundamental and applied research in computer vision, medical image analysis and image understanding, leading to numerous high-impact conference and peer-reviewed journal publications.
  * Successfully secured and managed numerous grants to support research.
  * Supervised student research at undergraduate and postgraduate level.
  * Provided technical consultation for the university and industry on computer vision and image processing.
  * Taught linear algebra, programming, research methodology and computer vision courses at undergraduate and postgraduate levels.

* **Jun 2001 &ndash; Dec 2001: Vision Systems Engineer**
  * [Ismeca Semiconductor](https://cohu.gcs-web.com/news-releases/news-release-details/cohu-completes-acquisition-ismeca), Malacca, Malaysia
  * Performed integration, testing and performance tuning of vision inspection systems for various back-end semiconductor assembly equipment.
  * Provided on-site and e-mail technical support on customer issues related to vision-based inspection systems installed on Ismeca products.
  * Conducted systems buy-off and validation of accuracy and repeatability of vision-based inspection systems prior to product shipment.
  * Conducted in-house and customer training particularly related to vision-based inspection systems.

Education
======
* Ph.D., Universiti Sains Malaysia, Penang, Malaysia, 1997&ndash;2003. Research focused on artificial neural networks, structured lighting and sensory perception for robotic manipulators.
* B.Tech in Industrial Technology, Universiti Sains Malaysia, Penang, Malaysia, 1993&ndash;1997.

Technical Skills
======
* **Programming Languages:** Python, SQL, R, MATLAB, Swift, C/C++ (in order of proficiency)
* **Deep Learning and ML Development:** PyTorch, TensorFlow, Scikit-Learn, WEKA
* **LLM / GenAI Tooling:** Agentic coding (Cursor, Claude Code, Codex), Google Document AI, RAG (LightRAG), LLM-as-judge evaluation, Text-to-SQL, prompt engineering
* **Clinical Data & Statistical Methods:** EHR/GEMINI data, competing-risks survival analysis, Neural Additive Models, statistical process control, HIPAA/PHI-compliant data handling
* **Cloud Technologies and HPC:** Amazon AWS, Snowflake, Sigma, SLURM clusters
* **Software Engineering & Deployment:** Git, JIRA, Docker, Flask
* **Digital Image Processing:** OpenCV, Scikit-Image, PIL
* **Data Visualization:** Seaborn, Matplotlib, Pandas, Sigma
* **Large-Scale Image Annotation:** Labelbox, Sama
* **Typesetting:** LaTeX

Honours and Awards
======
* 2017: **Best Paper Award** &mdash; Annual Conference on Computer Vision and Intelligent Systems, Waterloo, ON.
* 2010: **Best Paper Award** &mdash; International Workshop on Advanced Future Multimedia Services, GwangJu, Korea.
* 2010: **3rd rank** (as at Mar 2011) in the Multiple Sclerosis Lesion Segmentation Challenge 2008.
* 2010: **Winner, E-Health category** &mdash; *ENDEAVOR* Extensible Medical Image Analysis and Visualization Platform, Asia Pacific ICT Awards (APICTA Malaysia).
* 2009: **Silver Medal** &mdash; *ENDEAVOR* Extensible Medical Image Analysis and Visualization Platform, ITEX 2009 Invention, Innovation and Technology Exhibition, Kuala Lumpur.
* 2009: **Bronze Medal** &mdash; *WML-Endeavor* Collaborative Medical Image Analysis Software for White Matter Lesion Detection in MRI, PECIPTA Exhibition for Malaysian Science and Technology Inventions, Kuala Lumpur.
* 2009: Excellent Service Award, Universiti Sains Malaysia.
* 2007: **Silver Medal** &mdash; *DVTRS* Software for Tumour Delineation and 3D Visualization, PECIPTA Exhibition for Malaysian Science and Technology Inventions, Kuala Lumpur.
* 1997&ndash;2001: Postgraduate Scholarship Award, Universiti Sains Malaysia.

Publications
======
Please see the [Publications](/publications/) page for a complete, categorized list of journal articles, conference papers, books/chapters and technical reports, or refer to my [Google Scholar profile](https://scholar.google.com/citations?user=0nVlbNgAAAAJ&hl=en) for citation metrics.

References
======
Available upon request.
