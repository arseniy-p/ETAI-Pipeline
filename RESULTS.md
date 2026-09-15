# Results

## run_20260915_171210 (logistic_regression) vs run_20260915_171703 (decision_tree)

Both models are tied on accuracy: logistic regression gets 0.674 on test vs 0.668 for the depth-5 tree, and both round to 0.67 overall. The tree overfits slightly more (train-test gap +0.012 vs +0.004) and trades precision on the non-reoffend class for a little more recall on the reoffend class (recall 0.65 vs 0.60, f1 0.64 vs 0.62), so it flags more people as high risk.

