## Overview
Cryptocurrency is a relatively new form of digital currency that is used and traded in the digital market. Today there are hundreds of different “coins” available, each with qualities that set them apart, including different algorithms, a different supply of coins, and a different quantity of coins that are actively mined. With such a diverse market, the complex question arises, how might one identify underlying patterns. In this project, python's sklearn library is used to conduct unsupervised machine learning to discover unknown patterns about actively mined cryptocurrencies.  

## Results
The current data set shows there are 532 Cryptocurrencies that are being traded. 
These active cryptocurrencies can be grouped into 4 different categories based on the following graph:

<img width="420" alt="elbow_curve" src="https://user-images.githubusercontent.com/106559768/197100954-465066c5-f399-4589-bf07-3922075d08de.png">

The data is reduced to show 3 principle components that can be used to group cryptocurrencies into 4 groups by their similarities. 
<img width="315" alt="clusters" src="https://user-images.githubusercontent.com/106559768/197102179-094d5e52-fef1-43c3-8a5c-37efaf723fe6.png">

The currencies are graphed in 2 dimensions to show the total coin supply vs. the total coins mined by class
<img width="420" alt="availability_of_coins" src="https://user-images.githubusercontent.com/106559768/197100523-c108ebda-790a-4a79-89a2-891839bd8804.png">
