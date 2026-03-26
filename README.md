Here is the clean version without emojis, suitable for a markdown cell:

Why Boosting Works Differently from Bagging

This tutorial explains the difference between bagging and boosting, two widely used ensemble learning methods. Bagging reduces variance by training models independently on bootstrap samples and averaging their predictions, while boosting builds models sequentially to correct previous errors, making it more adaptive.

This notebook demonstrates these ideas using synthetic and real datasets. It compares a decision tree, a bagging-based model (Random Forest), and a boosting-based model (AdaBoost), and visualises their behaviour through decision boundaries and performance analysis.

How to Run

Install required packages:

pip install -r requirements.txt

Open the notebook:

jupyter notebook

Run all cells in:

nithin_ml_code.ipynb

All figures and results will be generated automatically.

Summary of Results

Bagging improves stability through averaging

Boosting improves adaptivity by focusing on errors

Boosting performs well when meaningful patterns remain

Bagging remains more stable as ensemble size increases

Accessibility

Clear labels and readable fonts

Colour-blind friendly plots

Descriptive figure captions

References

Breiman (1996, 2001), Freund & Schapire (1997), Hastie et al. (2009), Pedregosa et al. (2011)
