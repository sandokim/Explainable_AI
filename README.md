# Layer-wise Relevance Propagation (LRP)

#### Relevance Socre : x가 출력에 얼마나 영향을 주는가? -> x의 변화가 y의 변화에 얼마나 영향을 주는가?

Layer들의 영향력을 보려면 Backpropagation의 chain rule을 decomposition해야하며 이는 Taylor series를 사용한다.
