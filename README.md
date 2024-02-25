
## IE Business School Course 💻
This project's main goal is to spot potential biases by using the Synthetic Credit Card and Modcloth databases as examples carried out by Prof. Manoel Gadi from IE Business School.
To further enhance use, performance, and reliability, we have implemented additional modifications to the original FairDetect framework inside the confines of this project. Finally, a second bias framework has been presented in order to compare various bias detection approach elements such as functionality and utility. In order to complete this exercise, we used AEquitas, a framework that was created by the Centre for Data Science and Public Policy at the University of Chicago. Users can easily audit models for various bias and fairness indicators in connection to numerous population sub-groups using this open-source tool.



## Introduction to FairDetect 👓
Congregating the various theoretical concepts into a practical framework, we can follow the “theoretical lens of a ‘sense-plan-act’ cycle”, as described by the HLEG framework (European Commission and Directorate-
General for Communications Networks, Content and Technology, 2019). Applying this concept to the problem of ML fairness, we can break down three core steps in providing robust, and responsible artificial intelligence:
Identify, Understand, and Act (IUA).
1. Identify: The process of exposing direct or indirect biases within a dataset and/or model.
2. Understand: The process of isolating impactful scenarios and obtaining trans parent explanations for outcomes.
3. Act: The process of reporting and rectifying identified disparities within the
By understanding the philosophical forms of unfairness as defined by our review of the literature and categorizing our prominent fairness metrics into the overarching categories of representation, ability, and performance,
we can establish a series of tests to “identify” levels of disparities between sensitive groups at different levels. Merging these findings with the explainability of our models through the use of white-box models, or Shapley
value estimation for black-box models, we can dig deeper into the model’s predictions, “understanding” how classifications were made, and how they varied from the natural dataset exposing both natural biases as well as
added model differences. Finally, by probing further into levels of misclassification, in particular looking at negative outcomes, we can isolate groups most at risk and set up a series of “actions” that can be taken to mitigate
the effects. Given this three-step framework which combines societal, legal, and technical considerations, the paper will then go through a series of cases, and examine the proposed framework
