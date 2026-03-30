# Temporal-Graph-Neural-Network

## 📊 Key Findings

This study demonstrates that modeling **inter-firm dependencies** plays a crucial role in improving stock price prediction. Unlike traditional approaches that treat firms independently, our Temporal Graph Neural Network (TGNN) framework captures both **relational** and **temporal** dynamics in financial markets.

### 🔹 Inter-Firm Relationships Improve Prediction
By constructing a dynamic graph based on **news co-occurrence**, the model captures how information flows across related firms. Incorporating these relationships significantly enhances predictive accuracy compared to models that ignore cross-firm interactions.

### 🔹 Graph-Based Models vs. Sequential Models
Experimental results show that graph neural network architectures, including **ST-GCN** and **TGCN**, achieve stronger predictive performance than conventional temporal models such as **GRU**, **LSTM**, and **Transformer**. This indicates that relational structure provides additional predictive signals beyond temporal patterns alone.

### 🔹 Multi-Modal Feature Integration
Combining **textual sentiment**, **historical prices**, and **volatility** as node features allows the model to learn richer representations of each firm. This multi-modal integration improves the model’s ability to capture complex market dynamics.

### 🔹 Importance of Temporal Modeling
While graph structure is essential, temporal modeling remains critical. The best results are obtained when **spatial (graph)** and **temporal** components are jointly modeled, highlighting the importance of capturing time-dependent patterns.

### 🔹 Information Propagation Across Firms
The findings provide empirical evidence that **market information propagates across firms**, especially those frequently co-mentioned in financial news. This confirms the presence of **network effects** in financial markets.

---

## 💡 Takeaway

**Temporal Graph Neural Networks (TGNNs)** provide an effective framework for stock price prediction by uncovering hidden dependencies between firms. This approach opens new directions for future research, including:
- Multi-relational graph modeling  
- Cross-market interactions  
- Multi-modal financial learning  
