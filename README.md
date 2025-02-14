TODO: Build the GDP formula from stratch

//chapter 1: Consumption
Situation: You are Chris Wong.\n
You have just been assigned to be the Financial Secretary of Hong Kong.\n
Your task is to improve the GDP of Hong Kong by any means
GDP = C  
C = C1 * C2

//chapter 2: Investment
You realized that Hong Kong people are Constantly Saving.\n 
You believe that their idle money can be better utilized to develop the economy.\n
You proposed some initiatives to encourage citizens to invest their leftover money
GDP = C + I
I = C^0.5 * I1 * I2


//chapter 3: Government Expenditure
With so many consumption and investment,\n
your government has received a huge sum of Consumption Tax and Value-Added Tax (which luckily didnt exist IRL).\n
You look at the overflowing piles of cash and tonnes of precious metals,\n
and wondering if they can also be utilized to boost the economy.
GDP = C + I + G
G = C^0.15 * I^0.2 * G1

//chapter 4: Exports
Your citizens are really good at doing business.\n
Many local companies has been asking you for permission to expend their company overseas'\n
They inspired you to think about business opportunities in overseas market.\n
You can export your overproduced goods and services elsewhere.\n
You started to hate yourself for not realizing this earlier.
GDP = C + I + G + X
X = X1 * X2 * 7.8

//chapter 5: Imports
"Hong Kong businessman are really good at doing business," people always say,\n
"but they are draining our national reserves."\n
You thought of The Opium War over 100 years ago.\n
You better not cause anymore chaos or maybe WW3.\n
Therefore you have to buy something back from foreigners from time to time\n
in order to relieve their trade deficits.
GDP = C + I + G + NX
NX = X1 * X2 * 7.8 - 10^t

//chapter 6: Inflations
You have done everything you can...at least you thought so.\n
One day, you saw Beautiful Country started doing Quantitative Easing,\n
which is just indefinitely printing money in a nutshell.\n
People say this will cause a potentially uncontrollable inflation,\n
but it will surely make the value of GDP grow much bigger...\n
Wait! That would make a bread cost 500 thousand HKD...\n
That's not what you should care. Just sit back and relax,\n
and go to the bar to grab some beer after work.
Nominal GDP = Real GDP * inflation
Real GDP = C + I + G + NX
