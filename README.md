# Text prep from scratch

## 📌 Description
This project implements a TF-IDF (Term Frequency-Inverse Document Frequency) computation in Python. The program performs the following steps:

1. **Preprocessing:** Cleans and tokenizes input text documents.
2. **TF Calculation:** Computes the term frequency for each word in a document.
3. **IDF Calculation:** Uses the formula:
   
   \[
   IDF(t) = 1 + \log \left( \frac{\text{Total number of documents}}{\text{Number of documents containing } t} \right)
   \]

4. **TF-IDF Calculation:** Multiplies TF and IDF values to obtain the final TF-IDF score.
