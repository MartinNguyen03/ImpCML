## ImpCML:

- Paper attempts to refute Universal function approximation theorem mby conducting experiments on a limited number of basis expansions (polynomial)
- models used are
    - polynomial basis expanded linea regression
    - GPT basis expansion (?)




Assessment Criteria:

- Writing quality (5 marks / 8.33%)
- Report quality (10 marks / 16.67%)
- valid experimental design (10 marks / 16.67%)
- results communication (10 marks / 16.67%)
- results quality (5 marks / 8.33%)
- theoretical analysis (5 marks / 8.33%)
- sustainability analysis (5 marks / 8.33%)

The above criteria add up to 50 marks out of a potential 60 marks (= 83%)

The remainign 10 marks can be earned by performing any **2** of the following additional analyses:

- Multiple models (5 marks / 8.33%)
    - neural networks
    - k nearest neighbours
    - decision trees


- Results n≥30 (5 marks / 8.33%)
    - changing hyperparameters (e.g. optimisation techniques, layers, mini batching, etc)
- Strong theoretical analysis (5 marks / 8.33%)
- Exceptional sustainability analysis (5 marks / 8.33%)
- Calibrated uncertainty (5 marks / 8.33%) -> martin


## **Report sections:**

### location to be determined:

- The false assumptions made by mock paper which led to the erroneous conclusion

### **Abstract:**

- Short paragraph describing main aims of our paper, method investigated to achiev this, and brief mention of key results

### **Introduction: (setting a broader stage than abstract)**

- Paragraph outlining importance of problem (Kryptonite-n challenge dataset)
- Paragraph on how our paper seeks to solve the problem outlined in previous paragraph
- Paragraph on the details of solution structure (e.g. what experiments are carried out)
- Paragraph summarising main takeaways of experiements

### **Methodology: (mathematical foundations of any models used)**

e.g. If gradient descent is to be described, then writing out the corresponding equation, pointing out hyperparameters interested in such as learning rate, no. of epochs, etc

- Describe any operations performed on data
    - normalisation (why?)
- Describe the mathematical foundations of neural networks
    - MLP equation for nn architecture
    - neural network training (loss function (relating binary cross entropy back to MLE), gradient descent formulation, learning rate, weight initialisation)
    - intuitive explanation linking back to universal approximation
    - hyperparameter search
    - more effective approach for fitting dataset of unknown distribution to a model than basis expanded linear regression due to the elimination of the need to manually search for suitable basis expansion

### **Experimental Design:**

- Outline hypothesis to be tested
- Outline experiment(s) that will be run to test this
- Outline actions taken to ensure results are valid
    - including error bars
    - experimenting with different data splits
    - cross validation
    - training with different random seeds
    - pickling the data after randomising and splitting into train/val/test

### **Experimental Results:**

- Presentation of results using tables and/or figures
    - plot of accuracy against epochs for each n value
    - plot of highest achieved accuracy vs target accuracies provided by mock paper
- Descriptions of how these plots validate/invalidate original hypothesis

### **Discussion:**

- Discuss what was achieved by the completed experiments
- HIghlight experiments that we would have liked to have done
- Paragraph on environmental impact assessment carried out on experiments run (Use this tool: https://mlco2.github.io/impact/)
- For environmental impact (from edstem post):
    - “More advanced analysis would perhaps use the tool in development and do some optimization to try to pick a model that is the most sustainable.”

### Extra marks stuff:

- Multiple models:
    - idk yet
- Results (n≥30)
- strong theoretical analysis
- exceptional sustainability analysis
- calibrated uncertainty


## The Goal ##
![alt text](image.png)


