# [Grad-CAM: Visual Explanations from Deep Networks](https://glassboxmedicine.com/2020/05/29/grad-cam-visual-explanations-from-deep-networks/)

Grad-CAM(Gradient-weighted Class Activation Mapping)

### Ablation Study

Ablation study는 모델이나 알고리즘을 구성하는 다양한 구성요소(component) 중 어떠한 “feature”를 제거할 때, 성능(performance)에 어떠한 영향을 미치는지 파악하는 방법을 말한다. 제안한 요소가 모델에 어떠한 영향을 미치는지 확인하고 싶을 때, 이 요소를 포함한 모델과 포함하지 않은 모델을 비교하는 것을 말한다. 
#### -> 이는 딥러닝 연구에서 매우 중요한 의미를 지니는데, 시스템의 인과관계(causality)를 간단히 알아볼 수 있기 때문이다.

### Grad-CAM Loss

<img src="https://github.com/sandokim/Explainable_AI/blob/main/images/Grad-CAM Loss.PNG" width="50%">

# Deit

[Training data-efficient image transformers & distillation through attention](https://arxiv.org/abs/2012.12877)

# Layer-wise Relevance Propagation (LRP)

#### Relevance Socre : x가 출력에 얼마나 영향을 주는가? -> x의 변화가 y의 변화에 얼마나 영향을 주는가?

Layer들의 영향력을 보려면 Backpropagation의 chain rule을 decomposition하여 편미분값을 봐야하며 미분계수를 decomposition을 위해서는 Taylor series를 사용한다.

--> 한 뉴럴의 출력에 대한 x의 기여도를 분해시킬 수 있다.

<img src="https://github.com/hyeseongkim0/Explainable_AI/blob/main/images/neuron.PNG" width="50%">
