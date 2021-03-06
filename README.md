# Daimler-s-Mercedes-Benz
Daimler’s Mercedes-Benz interesting in optimizing the testing time of their system

Problem statement: To ensure the safety and reliability of each and every unique car configuration before they hit the road, Daimler’s engineers have developed a robust testing system. But, optimizing the speed of their testing system for so many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Daimler’s production lines.

Daimler is interested to deal the curse of dimensionality and reduce the time that cars spend on the test bench.Data scientist will work with a dataset representing different permutations of Mercedes-Benz car features to predict the time it takes to pass testing. Winning algorithms will contribute to speedier testing, resulting in lower carbon dioxide emissions without reducing Daimler’s standards.



Approach: To solve the above businnes problem, many algorithms have been tried to estimate the accurate testing time. The data was studied, preprocessed, visualized and modelled. Several models were formed and deleted when the performance was not upto the mark, the model was compared based on root mean square, mean absolute percentage error and r2 score. 

Conclusion:

Daimler’s engineers can use gradient boosting algorithms with features selected from forward selection technique to calculate the time required for testing of car. 

The best param for gradient boostings are:
learning_rate = 0.015789473684210527,
max_depth = 3,
min_samples_split = 3,
n_estimators = 300

The best 113 features out of 364 are mentioned below.
 'X0',
 'X1',
 'X2',
 'X3',
 'X5',
 'X12',
 'X18',
 'X21',
 'X29',
 'X33',
 'X36',
 'X38',
 'X39',
 'X42',
 'X47',
 'X52',
 'X54',
 'X59',
 'X60',
 'X64',
 'X74',
 'X75',
 'X76',
 'X79',
 'X83',
 'X84',
 'X92',
 'X110',
 'X116',
 'X118',
 'X119',
 'X120',
 'X124',
 'X125',
 'X136',
 'X137',
 'X142',
 'X143',
 'X145',
 'X148',
 'X151',
 'X152',
 'X153',
 'X155',
 'X156',
 'X157',
 'X158',
 'X160',
 'X173',
 'X178',
 'X185',
 'X190',
 'X203',
 'X204',
 'X205',
 'X206',
 'X207',
 'X218',
 'X221',
 'X226',
 'X227',
 'X230',
 'X232',
 'X236',
 'X240',
 'X248',
 'X253',
 'X254',
 'X257',
 'X259',
 'X260',
 'X263',
 'X269',
 'X270',
 'X272',
 'X275',
 'X278',
 'X279',
 'X284',
 'X288',
 'X292',
 'X294',
 'X295',
 'X296',
 'X300',
 'X301',
 'X307',
 'X308',
 'X311',
 'X313',
 'X314',
 'X315',
 'X316',
 'X318',
 'X319',
 'X326',
 'X327',
 'X328',
 'X329',
 'X332',
 'X335',
 'X339',
 'X340',
 'X345',
 'X359',
 'X362',
 'X363',
 'X364',
 'X365',
 'X369',
 'X380',
 and 'X385'
 
 Refernces: The data is taken from the kaggle for practice and learning purpose, the link is mentioned below.
 https://www.kaggle.com/c/mercedes-benz-greener-manufacturing
 
