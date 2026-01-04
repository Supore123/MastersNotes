**Goal**: Maximum grade with efficient time usage **Strategy**: Hybrid approach - use provided code as foundation, customize and deeply understand it, write excellent report

---

## WEEK 1: CODE & EXPERIMENTS (Days 1-7)

### **Day 1 (8 hours): Setup & Understanding**

**Morning (4 hours): Environment Setup**

- ✅ 30 min: Create directory structure (see below)
- ✅ 1 hour: Install all packages, test imports
- ✅ 1 hour: Download BreastMNIST, explore dataset
- ✅ 1.5 hours: Read MedMNIST paper + understand dataset characteristics

**Afternoon (4 hours): Deep Code Review**

- ✅ 2 hours: Read through ALL my provided code
- ✅ 1 hour: Run data_loader.py, understand output
- ✅ 1 hour: Trace through one SVM training cycle manually (with debugger/prints)

**Evening: Make it yours**

- ✅ Rename variables to your preferred style
- ✅ Add extensive comments explaining WHY not just WHAT
- ✅ Create your README.md with detailed notes

**Deliverable**: Working environment, understood codebase

---

### **Day 2 (8 hours): Model A Deep Dive**

**Morning (4 hours): SVM Implementation**

- ✅ 1 hour: Study SVM theory (watch StatQuest video)
- ✅ 2 hours: Run all Model A experiments, take detailed notes
- ✅ 1 hour: Understand each feature extraction method (flatten, HOG, PCA)

**Afternoon (4 hours): Customization & Additional Experiments**

- ✅ 2 hours: Add your own experiment ideas:
    - Try different C values (0.1, 1, 10, 100)
    - Try polynomial kernel
    - Try different gamma values
    - Experiment with different augmentation strengths
- ✅ 2 hours: Create comparison tables, save results systematically

**Evening (2 hours): Analysis**

- ✅ Analyze overfitting: train vs validation accuracy
- ✅ Create visualization: feature importance/decision boundaries
- ✅ Write bullet points on findings

**Deliverable**: Complete Model A results with 8-10 experiments

---

### **Day 3 (8 hours): Model B Deep Dive**

**Morning (4 hours): CNN Understanding**

- ✅ 1 hour: Watch Stanford CS231n CNN lecture (or similar)
- ✅ 1 hour: Draw out CNN architecture on paper
- ✅ 2 hours: Run baseline CNN, understand training loop step-by-step

**Afternoon (4 hours): CNN Experiments**

- ✅ 2 hours: Run all complexity experiments (simple, medium, complex)
- ✅ 2 hours: Run augmentation experiments
- ✅ Track: training time, memory usage, parameter count

**Evening (2 hours): Advanced Experiments**

- ✅ Try different learning rates
- ✅ Try different batch sizes
- ✅ Experiment with dropout rates
- ✅ Save all training curves

**Deliverable**: Complete Model B results with 8-10 experiments

---

### **Day 4 (8 hours): Additional Experiments & Analysis**

**Morning (4 hours): Deep Analysis**

- ✅ Error analysis: which images are misclassified?
- ✅ Plot ROC curves for both models
- ✅ Create confusion matrices with detailed analysis
- ✅ Statistical significance tests (if applicable)

**Afternoon (4 hours): Comparative Analysis**

- ✅ Create side-by-side comparison plots
- ✅ Training time vs accuracy trade-offs
- ✅ Model complexity vs performance
- ✅ Memory usage analysis

**Evening (2 hours): Results Organization**

- ✅ Create Excel/CSV file with ALL results
- ✅ Organize all plots in folders
- ✅ Write bullet points for each finding

**Deliverable**: Complete experimental results, organized data

---

### **Day 5 (8 hours): Literature Review**

**Morning (4 hours): Paper Collection**

- ✅ Find 15-20 relevant papers:
    - 3-4 papers: SVM for medical imaging
    - 3-4 papers: CNN architectures (ResNet, VGG)
    - 3-4 papers: Data augmentation in medical imaging
    - 2-3 papers: Breast cancer detection
    - 2-3 papers: MedMNIST benchmark papers
    - 2-3 papers: Transfer learning in medical imaging

**Afternoon (4 hours): Reading & Note-taking**

- ✅ Speed-read each paper (15-20 min each)
- ✅ Focus on: abstract, method, results, conclusion
- ✅ Create summary table:
    - Paper | Year | Method | Dataset | Results | Key Finding

**Evening (2 hours): Literature Summary**

- ✅ Write 1-paragraph summary of each paper
- ✅ Group papers by theme
- ✅ Identify gaps your work addresses

**Deliverable**: Annotated bibliography with 15-20 papers

---

### **Day 6 (6 hours): Code Polish & Documentation**

**Morning (3 hours): Code Quality**

- ✅ Add docstrings to every function
- ✅ Add type hints: `def train(X: np.ndarray, y: np.ndarray) -> float:`
- ✅ Clean up commented code
- ✅ Ensure consistent naming conventions
- ✅ Add error handling

**Afternoon (3 hours): Create Additional Utilities**

- ✅ Create results_analysis.py with comparison functions
- ✅ Create visualization.py for all plots
- ✅ Update main.py with clear experiment sections
- ✅ Test that `python main.py` runs end-to-end

**Evening: Repository Setup**

- ✅ Initialize git repository
- ✅ Create meaningful commits (backdate if needed)
- ✅ Push to GitHub (private)
- ✅ Verify submission requirements

**Deliverable**: Production-quality code, GitHub repository

---

### **Day 7 (4 hours): Final Experiments & Validation**

**Morning (2 hours): Sanity Checks**

- ✅ Re-run all experiments fresh
- ✅ Verify results are reproducible
- ✅ Check test set hasn't been touched during development
- ✅ Ensure no data leakage

**Afternoon (2 hours): Create Figures for Report**

- ✅ High-quality plots (300 DPI)
- ✅ Professional styling
- ✅ Clear legends and labels
- ✅ Consistent color scheme
- ✅ Save as vector graphics (SVG/PDF) for report

**Evening: Week 1 Review**

- ✅ List all completed experiments
- ✅ Verify you can explain every result
- ✅ Prepare for report writing

**Deliverable**: All experiments complete, publication-ready figures

---

## WEEK 2: REPORT WRITING (Days 8-14)

### **Day 8 (8 hours): Report Structure & Introduction**

**Morning (4 hours): Setup & Abstract**

- ✅ 1 hour: Download LaTeX template, set up Overleaf
- ✅ 1 hour: Create outline for all sections
- ✅ 2 hours: Write Abstract (150-200 words)
    - Context: Breast cancer classification
    - Problem: Comparing classical ML vs deep learning
    - Methods: SVM and CNN on BreastMNIST
    - Results: Key findings (accuracy numbers)
    - Conclusion: Main takeaway

**Afternoon (4 hours): Introduction**

- ✅ 4 hours: Write Introduction (1-1.5 pages)
    - Background on breast cancer (with citations)
    - Importance of early detection
    - Role of machine learning
    - MedMNIST dataset description
    - Research questions:
        1. How does model capacity affect performance?
        2. How does data augmentation help?
        3. How does training budget impact results?
        4. SVM vs CNN comparison
    - Paper structure overview

**Evening (2 hours): Create Diagrams**

- ✅ System overview flowchart
- ✅ Methodology pipeline diagram

**Deliverable**: Complete abstract and introduction

---

### **Day 9 (10 hours): Literature Review**

**All Day: Writing Literature Review (2-2.5 pages)**

**Section 1: Classical Machine Learning for Medical Imaging (45 min)**

- ✅ SVM theory and applications
- ✅ Feature extraction methods
- ✅ Cite 3-4 papers

**Section 2: Deep Learning for Medical Imaging (1 hour)**

- ✅ CNN architectures
- ✅ Why CNNs work for images
- ✅ Cite 4-5 papers

**Section 3: Data Augmentation (45 min)**

- ✅ Augmentation techniques
- ✅ Medical imaging considerations
- ✅ Cite 2-3 papers

**Section 4: Breast Cancer Detection (45 min)**

- ✅ Ultrasound imaging
- ✅ Previous ML approaches
- ✅ Cite 2-3 papers

**Section 5: MedMNIST Benchmark (30 min)**

- ✅ Dataset description
- ✅ Previous results
- ✅ Cite 1-2 papers

**Afternoon/Evening (6 hours): Polish & Citations**

- ✅ Ensure every claim is cited
- ✅ Smooth transitions between sections
- ✅ Critical analysis (don't just summarize)
- ✅ Identify gap: "However, limited work compares..."
- ✅ Format all references properly

**Deliverable**: Complete literature review with 15+ citations

---

### **Day 10 (10 hours): Methodology - Model A**

**Morning (5 hours): SVM Methodology**

- ✅ 1 hour: SVM Theory
    - Mathematical formulation
    - Optimization problem: min ||w||² subject to...
    - Kernel trick explanation
    - RBF kernel equation: K(x,x') = exp(-γ||x-x'||²)
- ✅ 1.5 hours: Feature Extraction Pipeline
    - Diagram showing image → features → SVM
    - Flatten method: 28×28 → 784 dimensions
    - HOG method: gradient histograms
    - PCA method: dimensionality reduction
    - Normalization: StandardScaler
- ✅ 1.5 hours: Data Augmentation
    - Why augmentation for classical ML
    - Techniques: rotation (±15°), flips, noise, blur
    - Impact on training set size
- ✅ 1 hour: Experimental Setup
    - Hyperparameters tested
    - Train/val/test split
    - Evaluation metrics

**Afternoon (5 hours): Create Figures & Tables**

- ✅ Architecture diagram (flowchart)
- ✅ Feature extraction visualization
- ✅ Augmentation examples (before/after)
- ✅ Hyperparameter table
- ✅ Write detailed captions

**Deliverable**: Complete Model A methodology (2-3 pages)

---

### **Day 11 (10 hours): Methodology - Model B**

**Morning (5 hours): CNN Methodology**

- ✅ 1.5 hours: CNN Theory
    - Convolutional layers: feature maps
    - Equation: output[i,j] = Σ(input * kernel)
    - Pooling layers: dimensionality reduction
    - Fully connected layers: classification
- ✅ 1.5 hours: Architecture Description
    - Simple model: layer-by-layer breakdown
        - Conv1: 1→16 channels, 3×3 kernel
        - MaxPool: 2×2
        - Conv2: 16→32 channels
        - FC: 32×7×7 → 2 classes
    - Medium model: add Conv3
    - Complex model: add batch norm
- ✅ 1 hour: Training Procedure
    - Loss function: CrossEntropyLoss
    - Optimizer: Adam (why?)
    - Learning rate: 0.001
    - Batch size: 32
    - Early stopping strategy
- ✅ 1 hour: Data Augmentation
    - PyTorch transforms
    - Rotation, flip, brightness, contrast
    - Why each augmentation is valid for medical images

**Afternoon (5 hours): Create Figures & Tables**

- ✅ CNN architecture diagram (boxes and arrows)
- ✅ Show feature maps after each layer
- ✅ Augmentation examples
- ✅ Training hyperparameters table
- ✅ Model complexity comparison table (params, layers)

**Deliverable**: Complete Model B methodology (2-3 pages)

---

### **Day 12 (10 hours): Results & Analysis**

**Morning (5 hours): Results - Model A**

- ✅ 1 hour: Baseline Results
    - Table: different kernels, C values
    - Best configuration
- ✅ 1 hour: Feature Extraction Comparison
    - Table: flatten vs HOG vs PCA
    - Why HOG performs better/worse
- ✅ 1 hour: Augmentation Impact
    - Before/after table
    - Overfitting reduction analysis
- ✅ 1 hour: Model Complexity
    - Linear vs RBF comparison
    - Training time vs accuracy
- ✅ 1 hour: Training Budget
    - Plot: % training data vs accuracy
    - Learning curve analysis

**Afternoon (5 hours): Results - Model B**

- ✅ 1 hour: Baseline CNN Results
    - Training curves (loss and accuracy)
    - Overfitting analysis
- ✅ 1 hour: Augmentation Impact
    - With/without augmentation curves
    - Regularization effect
- ✅ 1 hour: Model Complexity
    - Simple vs Medium vs Complex
    - Parameter count vs performance
    - Diminishing returns discussion
- ✅ 1 hour: Training Budget
    - Different epochs: 10, 20, 30, 50
    - Convergence analysis
- ✅ 1 hour: Comparative Analysis
    - SVM vs CNN table
    - Training time comparison
    - When to use which model

**Deliverable**: Complete results section (3-4 pages)

---

### **Day 13 (8 hours): Discussion & Conclusion**

**Morning (4 hours): Discussion**

- ✅ 1 hour: Key Findings
    - CNN outperforms SVM by X%
    - Augmentation helps more for CNN than SVM
    - Complex models show marginal gains
- ✅ 1 hour: Analysis of Results
    - Why does augmentation help?
    - Why do CNNs work better for images?
    - Overfitting patterns
    - Feature learning vs hand-crafted features
- ✅ 1 hour: Comparison to Literature
    - How do your results compare to papers?
    - State-of-the-art on BreastMNIST?
    - Your contribution
- ✅ 1 hour: Limitations
    - Small dataset (28×28 images)
    - Binary classification only
    - Limited augmentation exploration
    - No ensemble methods
    - Computational constraints

**Afternoon (4 hours): Conclusion & Polish**

- ✅ 2 hours: Write Conclusion
    - Summary of work
    - Answer research questions
    - Main contributions
    - Future work:
        - Try ResNet architecture
        - Explore attention mechanisms
        - Test on full-resolution images
        - Multi-class extension
        - Transfer learning
- ✅ 2 hours: Create Supplementary Material (optional)
    - Additional experiments
    - Extended results tables
    - Code snippets
    - Hyperparameter sensitivity analysis

**Deliverable**: Complete discussion and conclusion (2 pages)

---

### **Day 14 (8 hours): Final Polish & Submission**

**Morning (4 hours): Report Polish**

- ✅ 1 hour: Read entire report aloud (find awkward phrasing)
- ✅ 1 hour: Check all citations are formatted correctly
- ✅ 1 hour: Verify all figures are referenced in text
- ✅ 1 hour: Check equations, tables, formatting

**Afternoon (3 hours): Final Checks**

- ✅ 30 min: Spell check and grammar check
- ✅ 30 min: Ensure page limit (8 pages + 4 supplementary)
- ✅ 30 min: Check all section numbers
- ✅ 30 min: Verify all captions are descriptive
- ✅ 30 min: Check figure quality (300 DPI)
- ✅ 30 min: Test all equations render correctly

**Evening (2 hours): Submission**

- ✅ 30 min: Export to PDF: `Report_AMLS_25-26_SNXXXXXX.pdf`
- ✅ 30 min: Final code test: `python main.py` runs successfully
- ✅ 30 min: Update README.md with final instructions
- ✅ 30 min: Make GitHub repo public, verify link works
- ✅ Submit on Moodle

**Evening: Celebrate!** 🎉

**Deliverable**: Submitted assignment!

---

## Daily Schedule Template (Intensive Mode)

**Typical Day Structure:**

```
09:00-10:30 | Deep work session 1 (90 min)
10:30-10:45 | Break
10:45-12:15 | Deep work session 2 (90 min)
12:15-13:15 | Lunch + walk
13:15-14:45 | Deep work session 3 (90 min)
14:45-15:00 | Break
15:00-16:30 | Deep work session 4 (90 min)
16:30-17:00 | Break
17:00-18:30 | Deep work session 5 (90 min)
18:30-19:30 | Dinner
19:30-21:00 | Evening session (optional for Day 8-13)
```

**Total: 7.5-9 hours productive work per day**

---

## Quality Checkpoints

### End of Week 1 Checklist:

- [ ] All experiments run successfully
- [ ] Results organized and saved
- [ ] Can explain every experimental choice
- [ ] 15+ papers collected and summarized
- [ ] All figures created at high quality
- [ ] GitHub repository ready

### End of Week 2 Checklist:

- [ ] Report is 8 pages (excluding references)
- [ ] All sections complete
- [ ] 15+ citations properly formatted
- [ ] All figures have descriptive captions
- [ ] Math equations properly formatted
- [ ] Code runs from `python main.py`
- [ ] README is comprehensive
- [ ] Submitted on time

---

## Priority Matrix

**Must Have (Critical for grade):**

- ✅ Working code for both models
- ✅ Complete results with tables/figures
- ✅ Literature review with 15+ papers
- ✅ Clear methodology with diagrams
- ✅ Thorough results analysis

**Should Have (Important for high grade):**

- ✅ Multiple experiments per model (8-10)
- ✅ Statistical analysis of results
- ✅ Comparison to state-of-the-art
- ✅ Discussion of limitations
- ✅ Professional code documentation

**Nice to Have (Extra credit):**

- ✅ Supplementary material
- ✅ Additional visualizations
- ✅ Error analysis
- ✅ Computational cost analysis
- ✅ Extended future work section

---

## Expected Grade Breakdown

**With this intensive 2-week approach:**

```
Abstract:                    4-5/5    (well-written)
Introduction:                4-5/5    (clear motivation)
Literature Survey:           4-5/5    (15+ papers)
Model A Description:         8-9/10   (detailed + diagrams)
Model B Description:         8-9/10   (detailed + diagrams)
Implementation A:            8-9/10   (working + documented)
Implementation B:            8-9/10   (working + documented)
Results A:                   7-9/10   (comprehensive experiments)
Results B:                   7-9/10   (comprehensive experiments)
Conclusion:                  4-5/5    (clear summary)
Code A:                      10/10    (perfect)
Code B:                      10/10    (perfect)
                            ________
TOTAL:                      76-88/100
```

**Target Grade: 78-85% (High 2:1 to First)**

---

## Efficiency Tips

**Time Savers:**

1. Use LaTeX template - don't fiddle with formatting
2. Write in Overleaf - auto-compiles PDF
3. Use Mendeley/Zotero for citations
4. Keep running notes document
5. Create figures as you experiment (don't leave to end)

**Common Time Wasters to Avoid:**

- ❌ Perfectionism on code (it works = move on)
- ❌ Reading entire papers (abstract + conclusion often enough)
- ❌ Tweaking figure colors for hours
- ❌ Re-running experiments unnecessarily
- ❌ Procrastinating with "research" (watching YouTube)

**Focus Techniques:**

- 🎯 Pomodoro: 90 min work, 15 min break
- 🎯 No social media during work blocks
- 🎯 Phone on airplane mode
- 🎯 One task at a time (no multitasking)
- 🎯 Track daily progress

---

## Backup Plan

**If running behind schedule:**

**End of Week 1 - Code not done:**

- Use my provided code as-is
- Focus on understanding deeply
- Add 2-3 custom experiments
- Move to report writing

**Day 11 - Report not started:**

- Skip supplementary material
- Shorter literature review (10 papers)
- Combined Model A+B methodology
- Focus on results and analysis

**Day 13 - Still not done:**

- Minimal discussion (1 page)
- Focus on completing all core sections
- Ensure code runs perfectly
- Submit on time (even if not perfect)

---

**Remember**: Perfect is the enemy of done. **Target**: 80% quality on everything beats 100% on half the assignment.

Good luck! You've got this! 💪