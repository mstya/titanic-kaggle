embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

parch	# of parents / children aboard the Titanic

sibsp	# of siblings / spouses aboard the Titanic

pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd

pclass: A proxy for socio-economic status (SES)
- 1st = Upper
- 2nd = Middle
- 3rd = Lower

sibsp: The dataset defines family relations in this way...
- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
- Parent = mother, father
- Child = daughter, son, stepdaughter, stepson
- Some children travelled only with a nanny, therefore parch=0 for them.