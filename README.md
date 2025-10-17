# ethereum-risk-ai
1. **Wallet Sampling** – Collect random Ethereum wallet addresses using RPC or Etherscan tags  
2. **Data Collection** – Fetch ETH, Token, and Internal transactions via Etherscan API  
3. **Preprocessing** – Clean, normalize, remove duplicates and invalid entries  
4. **Labeling** – Assign risk labels using seed + heuristic rules  
5. **Feature Engineering** – Build transaction & wallet-level features  
6. **Model Training & Evaluation** – Train Logistic Regression / XGBoost and evaluate ROC-AUC  
