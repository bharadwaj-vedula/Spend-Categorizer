# 💰 Spend Categorizer
Automatically categorize bank transactions based on transactions using sentence embeddings.  
Used SetFit to fine tune embeddings with very mininal examples **(4 from each class)**


## ✨ Features
✅ Converts transaction descriptions into meaningful embeddings  
✅ Fine-tuned model for better categorization accuracy  
✅ Fine-Tuned using very small number of examples using SetFit  

## 🛠️ Methodology
- Converts raw transactional data into natural language summary using heuristic methods
- Few shot learning technique like Setfit to fine tune Sentence Transformer

## Before & After Fine-Tuning Embeddings
Before
![newplot (1)](https://github.com/user-attachments/assets/9437a400-7210-4845-9ca1-8f34b0f7ddac)

Fine-Tuned Embedding
![newplot](https://github.com/user-attachments/assets/19b06fa3-835b-4ac7-b82b-c55611eadb13)

## 🚀 Installation & Setup  

### 🔹 Prerequisites  
- Python 3.8+  
- PyTorch  
- Transformers
- Setfit

## 📊 Example Predictions

Transaction : 'UPIOUT/509042621775/wellnessquotien833.rzp@i/7298    260.00'  
Summary : You have sent 260.00 to wellnessquotien833.rzp@i via UPI  
Category : Sports & Fitness  

Transaction : 'UPIOUT/411144932833/BURGERKINGINDIA@ybl/Pa                  178.92'  
Summary : You have sent 178.92 to BURGERKINGINDIA@ybl via UPI  
Category : Food  

## 🔮 Future Improvements
- Add meta data to merchants to classify them better  
- Finetune on some more examples  
- Generate synthetic dataset (currently using authentic bank statements)  

