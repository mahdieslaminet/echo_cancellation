# echo cancellation 
A brief of this paper :

The paper introduces a novel approach called "Auto-DSP" that aims to automatically learn optimal update rules for adaptive filtering algorithms, particularly in the context of acoustic echo cancellation.
Rather than relying on hand-derived, expert-designed update rules, the Auto-DSP method frames the adaptive filtering process as a differentiable operation that can be optimized using a learned optimizer. This learned optimizer is trained directly on data, without the need for external labels or manual tuning.
The key idea is to train a neural network-based optimizer that can output gradient-based update rules for the adaptive filter parameters. By using backpropagation through time, the optimizer can be meta-learned to produce high-performing update rules for a variety of adaptive filtering architectures, including both linear and nonlinear models.
The authors demonstrate the effectiveness of this approach on acoustic echo cancellation tasks, showing that the learned optimizers can outperform traditional hand-tuned baselines in terms of convergence speed, robustness to nonlinearities, and adaptation to unseen acoustic environments. This suggests that the Auto-DSP method has the potential to revolutionize how adaptive filters are designed and optimized in the future . 
# run the codes : 
you can find the codes of paper in codes directory and run them . 
# video explanation of paper and codes : 
for better understanding you find video explanation of paper and code from google drive : https://drive.google.com/drive/folders/1mPThK9E37d_YGdSLbODfr2cMlw_OcjKK?usp=drive_link 
