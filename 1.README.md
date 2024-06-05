MDD is a neuropsychatric disorder that affects 12% of thw owrd population. Diagnosis of this disorder is through clinical interviews, which requires the paitent to show a miminum history of symptoms of atlest  2 weeks.
Diagnosis methods researched for MDD using machine learning and gene expression has not resulted in devlopment of any new clinical diagnosis tool. 

Aim:-This study was done to check by ensembling multiple machine learning models can create a more precise model for diagnosis .

The data was first subjected to preprocessing , in this study we used 4 datsets from 3 platforms. one of the datasets was kept aside as independent dataset.

After preprocessing the data was processed by first merged and then samples were shuffled and then split in to train and test with the raio of 9:1 , this sampling was done 10 times for 10 iterations.

After processing the samples the train and test data were normalised and batch corrected (This was done for 10 iterations)

After normalisation and batch correction the train data was used to train and test the models .this was followed by testing and threshold optimisation with test.(This was done for 10 iterations)

After the model were trained they were subjected to ensemble and the results were obtained using test data. (This was done for 10 iterations)

validation of the ensemble was done by processing the independent dataset. there were some questions this part was meant to solve but was not completely possible. The independent dataset has 3 verisons which were run ten times on the ten versions of the ensembled model , so a total of 30 times.
