## Constraint Reasoning Embedded Structural Prediction
Welcome to the Code part for reproducibility. We summarize our experiment implementations in this pages.

### Vehicle Dispatching Service Planning

#### Problem Descriptions

A route planning problem which recommends routes to drivers to meet the service needs while satisfying the drivers' preferences. Such preferences are learned from the historical traveling data. The input of this problem are the daily service requests. The output are the permutations of the service locations, representing the order that the locations should be visited. This task requires a tight integration of machine learning to capture drivers' preferences, and constraint reasoning to ensure the satisfaction of service requests. 

#### Neural Network Structure and Implementations

We use the same neural network as the Xue et. al. paper (Embedding Decision Diagrams into Generative Adversarial Networks), which is shown in the following figure. Check the detailed implementation at: [Link the to the code repository](https://github.com/jiangnanhugo/route-planning)

![routing-exp](./figures/routing-neural-network.png)



![routing-exp](./figures/routing-valid-routes.png)


### If-then Program Synthesis
[Link the to the code repository](https://github.com/jiangnanhugo/if-then-program-synthesis)







| Dataset |IFTTT|IFTTT|IFTTT|Zapier|Zapier|Zapier|
| ------------------ | ----- | -------- | -------------- | ----- | -------- | -------------- |
| Metrics | Width | Accuracy | Valid Programs | Width | Accuracy | Valid Programs |
| ------------------ | ----- | -------- | -------------- | ----- | -------- | -------------- |
| LatentAttention    | 1     | 42.17%   | 87.51%         | 1     | 31.74%   | 88.00%         |
| Best Relaxed CRISP | 80    | 44.12%   | 99.19%         | 1200  | 34.28%   | 99.53%         |
| Exact CRISP        | 111   | 43.07%   | 100%           | 1353  | 32.83%   | 100%           |





### Text2SQL Generation

[Link the to the code repository](https://github.com/jiangnanhugo/sqlova-with-dataype-constraint)

|             | Execution Accuracy | Logical Accuracy | Valid SQL |
| ----------- | ------------------ | ---------------- | --------- |
| SQLNova     | 85.1%              | 79.1%            | 99.3%     |
| Exact CRISP | 85.8%              | 80.0%            | 100%      |

