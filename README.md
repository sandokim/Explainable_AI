# Layer-wise Relevance Propagation (LRP)

#### Relevance Socre : x가 출력에 얼마나 영향을 주는가? -> x의 변화가 y의 변화에 얼마나 영향을 주는가?

Layer들의 영향력을 보려면 Backpropagation의 chain rule을 decomposition하여 편미분값을 봐야하며 decomposition을 위해서는 Taylor series를 사용한다.

--> 한 뉴럴의 출력에 대한 x의 기여도를 분해시킬 수 있다.

<img src="https://github.com/hyeseongkim0/Explainable_AI/blob/main/images/neuron.PNG" width="50%">
