## Constraint Reasoning Embedded Structural Prediction
Welcome to the Code part for reproducibility. We summarize our experiment implementations in this pages.

### Vehicle Dispatching Service Planning
[Link the to the code repository](https://github.com/jiangnanhugo/route-planning)

<embed src="/CRISP/images/valid-routes.pdf" type="application/pdf">

### If-then Program Synthesis
[Link the to the code repository](https://github.com/jiangnanhugo/if-then-program-synthesis)

<embed src="/CRISP/images/valid-routes.pdf" type="application/pdf">
|                    | Width | Accuracy | Valid Programs | Width | Accuracy | Valid Programs |
| ------------------ | ----- | -------- | -------------- | ----- | -------- | -------------- |
| LatentAttention    | 1     | 42.17%   | 87.51%         | 1     | 31.74%   | 88.00%         |
| Best Relaxed CRISP | 80    | 44.12%   | 99.19%         | 1200  | 34.28%   | 99.53%         |
| Exact CRISP        | 111   | 43.07%   | 100%           | 1353  | 32.83%   | 100%           |
|                    |       |          |                |       |          |                |




### Text2SQL Generation

[Link the to the code repository](https://github.com/jiangnanhugo/sqlova-with-dataype-constraint)

|             | Execution Accuracy | Logical Accuracy | Valid SQL |
| ----------- | ------------------ | ---------------- | --------- |
| SQLNova     | 85.1%              | 79.1%            | 99.3%     |
| Exact CRISP | 85.8%              | 80.0%            | 100%      |

