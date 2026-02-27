# Sashwat Bilvesh Desai

[![LinkedIn](https://img.shields.io/badge/in_LINKEDIN-0077B5?style=for-the-badge)](https://www.linkedin.com/in/sashwat-d/)
[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:desai.sas@northeastern.edu)
[![Resume](https://img.shields.io/badge/RESUME-4CAF50?style=for-the-badge&logo=readdotcv&logoColor=white)](https://drive.google.com/file/d/1unjuk5Lg1AKFi5R9aVEwKmi82i-gwsbk/view?usp=drive_link)
[![Website](https://img.shields.io/badge/WEBSITE-FF6B35?style=for-the-badge&logo=googlechrome&logoColor=white)](https://desai-sashwat.github.io/portfolio-website/)

## 👨‍🎓 Education
**Northeastern University's College of Science, Boston, USA**  
*Master of Science in Applied Mathematics* | Sep 2024 – Dec 2026  
- Relevant Coursework: Probability | Introduction to Mathematical Modelling | Applied Statistics | Introduction to Machine Learning I, II | Analysis I | Foundations of Statistical Learning and Probability

## 💻 Technical Skills

### Programming Languages
Python | MATLAB | R | C++ | SQL

### Mathematical Expertise
Differential Equations | Fourier Analysis | Linear Algebra | Calculus | Probability | Matrix Algebra | Vector Calculus | Statistical Inference | Numerical Methods | Stochastic Processes | Time Series Analysis | Multivariate Analysis | Graph Theory | Complex Analysis 

### Data Analysis
Panda | Matplotlib | PySpark | D3.js | Plotly Dash | Data Assimilation Techniques | SciPy Ecosystem | SymPy | JAX | Autograd | Alteryx | Statistical Hypothesis Testing | Markov Chain Methods | Hierarchical Bayesian Models | Functional Data Analysis | Tableau | Power BI | Causal Inference | Big Data Technologies | Docker | Kubernetes

### Machine Learning
 Deep Learning | Regression | Classification | Optimization Techniques | Clustering | PyTorch | TensorFlow | OpenCV | Keras | Reinforcement Learning | Neural Networks | Natural Language Processing | Computer Vision | Generalized Additive Models | Transfer Learning

### Tools & Practices
Jupyter Notebooks | LaTeX | VS Code | Git | Design Patterns in Scientific Computing | Test-Driven Development | Reproducible Research Practices | Experimental Design | Object-Oriented Design | Documentation Tools | High-Performance Computing | Parallel Programming | Research Paper Writing | Grant Proposal Preparation | Mentoring | Grading | Academic Assistance

## 🔬 Research Projects

### Barista Bench
*Feb 2026*
- Implemented a multi-provider LLM pipeline for the BaristaBench Kaggle competition, benchmarking Gemini Flash Lite, GPT-4o-mini, and GPT-4.1 across 3,500 natural language coffee orders to identify the optimal model for structured JSON extraction with agentic state tracking.
- Developed a deterministic price validation engine that recalculates order totals from official menu rules, overriding LLM arithmetic errors and achieving near-100% pricing accuracy on 500 training samples — eliminating the top source of scoring penalties in the competition.
- Engineered post-processing modules for item deduplication and modifier normalization, resolving structural inconsistencies in LLM outputs where duplicate entries and uncollapsed quantities caused exact-match failures against ground truth.
- Achieved a 0.76 exact-match accuracy on the public leaderboard, parsing complex multi-item orders with mid-sentence corrections, cancellations, and filler words into strictly formatted JSON with constraint satisfaction across 23 menu items, 5 sizes, and 20 modifiers.

### Premier League Prediction
*Dec 2025 - Feb 2026*
- Implemented a real-time web scraping pipeline using Selenium and BeautifulSoup to extract comprehensive Premier League statistics from FBRef, including standings, expected goals (xG), shooting, passing, defensive, and possession metrics for all 20 teams.
- Developed an ensemble machine learning model combining XGBoost, LightGBM, Random Forest, AdaBoost, and Ridge Regression with weighted averaging, alongside Monte Carlo simulation (10,000 iterations) to generate win probabilities and confidence intervals for title race predictions.
- Engineered a multi-source feature extraction system integrating current season statistics, 5 years of historical performance data, and fixture difficulty analysis weighted by opponent strength—totaling 30+ predictive features across offensive, defensive, form, historical, and scheduling categories.
- Deployed the prediction system as a production REST API using FastAPI and Docker, hosted on Render with automated weekly model retraining via GitHub Actions, enabling real-time access to predictions through documented API endpoints.

### Netflix Show Clustering Using K-Means
*Nov 2025*
- Implemented K-means clustering algorithm to segment 8,807 Netflix titles into distinct content groups, utilizing multiple clustering validation metrics (Silhouette, Davies-Bouldin, Calinski-Harabasz) to determine optimal cluster count
- Developed a content-based recommendation system using Euclidean distance calculations within cluster spaces, enabling personalized content suggestions based on feature similarity scores
- Engineered 106 comprehensive features from raw Netflix metadata through multi-modal processing including TF-IDF vectorization for text descriptions, multi-label binarization for genres, and one-hot encoding for categorical variables
- Achieved 97.17% clustering stability with clear content segmentation between international TV shows (30.4%) and mainstream movies (69.6%), validated through PCA visualization and extensive exploratory data analysis across 12 different analytical dimensions

### Shakespearean Text Generator Using Recurrent Neural Networks
*Nov 2025*
- Implemented word-level LSTM architecture with 512-unit recurrent layer to model Shakespearean language patterns, processing 5.7MB corpus of complete works through comprehensive text normalization pipeline removing 50+ special characters and handling UTF-8 encoding
- Developed sliding window sequence generation with 20-word context windows and one-hot encoding for vocabulary representation, creating training dataset from processed corpus with configurable minimum word frequency thresholds for optimal vocabulary size
- Engineered temperature-based sampling algorithm using multinomial distribution for controllable text generation, implementing softmax probability scaling to balance between conservative predictions and creative variations in generated Elizabethan prose
- Achieved coherent generation of 600+ word passages maintaining Shakespearean style including archaic vocabulary, poetic phrasing, and dramatic dialogue patterns, with model checkpoint system saving best weights across 100 training epochs using categorical crossentropy loss optimization

### Bach Chorale Generator Using Recurrent Neural Networks
*Nov 2025*
- Implemented LSTM-based sequence-to-sequence architecture with 64-unit recurrent layer to model four-part harmony in Bach chorales, utilizing TensorFlow/Keras for neural network approximation of musical patterns and voice leading rules
- Developed sliding window data pipeline with 16-timestep sequences to process JSB Chorales dataset, featuring min-max normalization and automated train/validation/test splitting across 382 Bach compositions for robust generalization
- Engineered autoregressive generation algorithm with temperature-controlled sampling to produce 100-timestep chorales from seed sequences, incorporating clipping mechanisms and denormalization
- Achieved audio synthesis capability through custom sine wave generation mapping MIDI notes to frequencies at 22050 Hz sampling rate, enabling real-time playback of generated four-part harmonies with documented test loss of 0.0089 MSE and 0.0677 MAE

### Tic-Tac-Toe Using Reinforcement Learning
*May 2025*
- Implemented Deep Q-Network (DQN) architecture with experience replay buffer to train an autonomous Tic-Tac-Toe agent using PyTorch, featuring neural network approximation of Q-functions for state-action value estimation
- Developed epsilon-greedy exploration strategy with dynamic decay scheduling to balance exploration and exploitation during training, enabling the agent to discover optimal strategies through self-play
- Engineered complete Tic-Tac-Toe environment with support for agent vs. agent and human vs. agent gameplay, including state representation, reward structure, and action validation mechanisms
- Achieved robust performance evaluation framework testing against multiple opponent strategies including random players and minimax algorithms, with documented win rates, draw frequencies, and average moves to victory

### Impact of the COVID-19 Pandemic on Students' Behavior and Well-being
*Feb 2025 - April 2025*
- Analyzed comprehensive survey data from 1,182 students during COVID-19 lockdown examining time allocation patterns, digital behaviors, health outcomes, and online learning experiences across multiple demographic segments
- Employed multiple statistical methodologies including chi-square tests, ANOVA, logistic regression, and correlation analysis to identify significant relationships between student wellness indicators and behavioral patterns
- Established significant negative correlation (r = -0.16, p < 0.001) between self-study time and social media usage, revealing competition for student attention during remote learning periods
- Identified critical protective factors for student health including physical activity time and sleep duration through regression modeling, with findings showing healthier students reported more effective time utilization patterns

### Studying the Interconnections Between the Economic Growth of Two Regions Based on Capital and Labor Flow
*Oct 2024 - Dec 2024*
- Developed a mathematical framework integrating Solow Growth Model with Malthusian Population Model to analyze economic dynamics between interconnected regions
- Constructed a system of four differential equations capturing interplay between capital accumulation, labor force growth, and inter-regional mobility
- Established existence of unique equilibrium points and analyzed stability properties through mathematical proof and numerical simulations
- Identified critical threshold phenomenon in capital-induced labor movement affecting regional convergence and economic inequality

### Detection of Diabetic Retinopathy Using Deep Learning
*Mar 2024 – Aug 2024*
-	Augmented a dataset to 703 fundus images using image processing techniques like flipping, rotation, and brightness adjustment to enhance model training.
-	Developed and optimized deep learning models (CNN, DenseNet, ResNet), achieving up to 97.17% testing accuracy with DenseNet 169, setting a performance benchmark for Diabetic Retinopathy detection and grading.
- Published in IEEE 3rd World Conference on Applied Intelligence and Computing (AIC)

### Cost Optimization Solutions for E-commerce Vendors
*Apr 2022 – May 2023*
- Developed a cost optimization model using real-world data from Vasudhara Dairy, reducing total operational costs by 15% through cost function optimization. 
-	Applied Differential Evolution (DE) algorithm to optimize cost functions, achieving a 20% improvement in processing efficiency and cost reduction, validated by testing with the Rosenbrock Function.
- Published in International Journal of Innovative Science and Research Technology

### Image Processing Techniques (Review Paper)
*Feb 2023 – May 2023*
- Conducted comprehensive review of image processing techniques and applications
- Published in International Journal of Innovative Science and Research Technology

## 📝 Publications

1. S. Desai and S. Dodani, ["Detection of Diabetic Retinopathy Using Deep Learning Techniques,"](https://doi.org/10.1109/AIC61668.2024.10731034) 2024 IEEE 3rd World Conference on Applied Intelligence and Computing (AIC), Gwalior, India, 2024, pp. 898-904

2. Sashwat Desai, ["Cost Optimization Solutions for E-Commerce Vendors,"](https://doi.org/10.5281/zenodo.8397926) International Journal of Innovative Science and Research Technology (IJISRT), Volume 8 Issue 9, September 2023, pp. 1317-1337

3. Desai Sashwat Bilvesh, ["Image Processing Techniques: A Review,"](https://doi.org/10.5281/zenodo.7691869) International Journal of Innovative Science and Research Technology (IJISRT), Volume 8 Issue 2, February 2023, pp. 1302-1308

## 📊 GitHub Stats

![Sashwat's GitHub stats](https://github-readme-stats.vercel.app/api?username=desai-sashwat&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=desai-sashwat&layout=compact&theme=radical)

---

### 📫 Contact Me
- Email: desai.sas@northeastern.edu
- Phone: +1 (857) 209-1220
- Location: Boston, MA - 02119
