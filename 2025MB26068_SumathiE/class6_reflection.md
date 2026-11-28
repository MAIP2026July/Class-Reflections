# Class 6 Reflections
## Session 6: Data Fundamentals for AI Product Managers

### 1. Why Data Matters
- Data is used by a model to learn patterns.
- The model uses the learned patterns to generate a prediction or output.

**Flow:**  
Data → Model learns patterns → Prediction / Output

### 2. Signal Capture: Data Collection Strategies
Key questions:
- What data should we collect?
- Where should we collect it from?
- How should we collect it?

### 3. Supervised Machine Learning
- Supervised ML systems require labelled data.
- A label tells the model what the correct outcome was.

### 4. Label Quality Problems
1. **Ambiguous labels**
2. **Incorrect labels**
3. **Missing labels**
4. **Class imbalance**
   - Can cause poor detection of rare events.
   - Example: emergency case detection.

### 5. Pipeline Reality: Data Pipeline
A data pipeline moves data from its source to the place where it is needed.

**Typical flow:**

Source → Ingestion → Cleaning → Transformation → Storage → Feature / Model Pipeline → Model

### 6. Fragility Map: Data Risks
AI systems are fragile when real-world data differs from the assumptions made during training.

Key data risks:

- **Missing data:** Important information may not be available.
- **Data leakage:** Information that would be available at prediction time accidentally enters the training data.
- **Data drift:** Incoming data changes over time.
- **Concept drift:** The relationship between inputs and the target changes.
- **Label bias:** Labels may reflect human bias or inconsistent decisions.
- **Sampling bias:** Training data does not represent the actual population.

### 7. Features and Target
- **Features:** Inputs given to the model.
- **Target:** What we want the model to predict.
