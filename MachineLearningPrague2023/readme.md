# Measuring Corporate Reputation with BERT-based Transformers

Reputation is an increasingly important asset for companies and reputational risks need to be considered in risk management models. Therefore, it is essential to find methodologies well-suited to track and measure corporate reputation, even in real time, thus identifying communication opportunities and understanding how a brand is perceived by the various stakeholders. 

The web is both a great opportunity and challenge in this respect, given its enormous volume of data and its plurality of sources, such as social media, online newspapers, printed press and blogs. In other words, the possibility to track and recognize potential reputational crisis in near-real time and on a very granular level. In this context, more and more companies need to build and train machine learning models to be used in their analyses and monitoring systems. This allows them to exploit their ability to scale on large volumes of data and enable data-driven strategic decisions. 

The seven reputational drivers model, introduced by Van Riel and Fombrun (2007), provides the theoretical framework to model an intangible asset such as corporate reputation. This model distinguishes conversations into seven macro categories which map 7 distinct ways of connection between the brand and the stakeholders. 

In particular: 
- Products and Services All discussions and comments concerning a product or a service produced and/or provided by the company would fall in this category
- Innovation All contents about new technologies, digitization and new approaches
- Workplace Anything about employment with the company, its culture and anything concerning its employees
- Integrity and transparency All contents about the company's ethical behavior, transparency and fairness.
- Citizenship All contents about the impact of company's activities on the hosting communities
- Leadership All contents about leadership and vision
- Performance All contents about financial performances

In this poster, we demonstrate how fine-tuning a BERT transformer can be used to develop a multilabel text classifier that can classify according to categories of reputational drivers and be employed in production to measure corporate reputation. We will explore how BERT is able to effectively capture the contexts of the seven drivers, yielding better results than other text classifiers with a single model, outperforming and generalising better then other machine learning models.
