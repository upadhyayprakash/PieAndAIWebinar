# PieAndAIWebinar
Short Notes on the Pie & AI | AI Deployment Webinar on 4th April, 2020

### Chris: (Topics discussed)
- CI & CD for ML Deployment
- Docker for Virtualization
- Kubernetes
- Jenkins with GitHub
- GitLab
- Hadoop/Spark for Data Pipeline

### Sebastian: (Topics discussed)
- Articles Suggested:
	- Taking ML from Pilot to Production:
		https://www.industryweek.com/technology-and-iiot/article/22028709/taking-your-ai-projects-from-pilot-to-production
	- Keep revisiting the ML model for any new addition to Data features or requirement.
	- Coursera: "TensorFlow: Data and Deployment Specialization"


### Brian Muhia's: (Topics discussed)
- Class Imbalancing Techniques:
	- Sampling(same no. of samples per class)
	- Play with Loss Functions(check loss functions designed for tackling Class imbalancing)
	- Adding weights to the center pillars to solve problems wit imbalancing issues

- Data Labeling | Tackling Bias-ness:
	- Quatratic Voting
	- Preferential Voting/Labeling
	- Random Foresting

- For Diverse Labeling:
	- Take help from Unsupervised learning + Transfer Learning
	- For Text, we have ULMFit, BERT etc.
	- For Image, SimCLR, MoCo etc.
	- Active Learning(https://researchcode.com/code/2311979016/deep-bayesian-active-learning-with-image-data/)

- Semantic Segmentation using GradCAM:
	- Used in pixel prediction
	- "UNet"

	- Deployment Tools:
		- Ansible
		- Docker/KuberNetes
		- Python, Starlette, Quart

	- Failures in ML Production: Why?
		- Lack of Customer Focus
		- Lacking data diversity
		- Class-Imbalancing: Solved by Oversampling, label Smoothing

### Mia Zhao (Topics discussed)
- Shadow Testing
- MAP
- Open Source Tools:
	- Bighead
	- Zipline
	- Airflow
- Model Metrics vs Business Metrics
- Managing Expectations
- Customer Involvement(Design Thinking)
- User Experience(Reliable Model services, without Breaking)
- Service Monitoring

### Billy (Topics discussed)
- Privacy & Security
- ML Privacy in Production
- Tracking Data Movement
- Data Anonymizing
- Homomorphic Encryption(explaind by Brian), for Model privacy, encryption.
- Multi-party Computation: https://www.openmined.org/ tool.
- Differential Privacy - Google C++ Library
- Doubt: How to create Explainable AI if ML/Data privacy if so critical? What role does GDPR play during ML process?

- Challenges in On-line Inferencing:
	- Near real-time feature generation (Batched Windowing for processing batch of inputs)
	- Online model validation through A/B tests
	- Rolling out model Versions
	- Monitoring Deployments
	- Kibana/Graphana Logging in High frequency scenarios.
- GDPR:
	- App Policy Framework
  
### Scott Clendaniel (Topics discussed)
- Yawning Gulfs
- 85% of Projects never make it.
- Top 10 TIPS for AI Deployment
	SOURCE: https://www.projectmanager.com/blog/10-project-constraints-that-endanger-your-projects-success
	1. BEGIN WITH THE END IN MIND
		- Book, '7 habits of Highly effective people'
		- Project the FUTURE in the PRESENT
	2. IDENTIFY YOUR STAKEHOLDER'S NEEDS AND GOALS
		- Take human as the most critical part of the system. Orient your goals with their GOALS and Concerns.
		- FACT: Any NN is risky for Financial usecases in US.
	3. IDENTIFY MODEL/PROJECT CONTSTRAINTS
		- Clients constraints
	4. RISK
		- "Phase-Gate Model" (https://www.iamip.com/upl/images/604606/phase-gate-model.png)
		- E.g. predicting the 'Monday' forecast for the share market, based on the data of Tuesday forecasts.
	5. PLANNING FOR OBSOLESCENES:
	6. PLAN AROUND THE ANALYTICS MATURITY MODEL:
		https://www.gartner.com/smarterwithgartner/the-cios-guide-to-artificial-intelligence/
	7. VALIDATION OVERKILL:
		- Use Cross-Validation(shuffling the Training and Testing data sets)
	8. SIMLICITY AND FLEXIBILITY ARE YOUR ALLIES:
	9. CREATE A CHAMPION/CHALLENGER TESTING APPROACH
	10. WHAT IS YOUR "UNDO" plan
		- Taking the model out of production without damanging other linked systems.
		- Test the model UNDO.

Thanks to each speakers (Brian, Sebastian, Billy, Mia, Chris, Clendaniel) for covering your insights.
