# High Performance ML Algorithms (HPMLA) Learner

The HPMLA Learner (SymSGD) is a distributed linear/logistic model trainer for large datasets. SymSGD shred the train data and distributes it among CPU compute nodes 
in BatchAI and trains on different chunks of data concurrently while preserving the semantic and accuracy of sequential SGD algorithm. 
This enables SymSGD users to train a linear model on a large (most likely sparse) training data in parallel efficiently without loss of accuracy.

#### [SymSGD-CPU](./SymSGD-CPU)
This SymSGD-CPU recipe contains information on how to run distributed HPMLA job across multiple CPU nodes with BatchAI.

#### [Data-Sharding](./Data-Sharding)
This SymSGD Data Sharding recipe shows how to use Jupyter Notebook to shred and deploy your training data prior to running a training job.

-----------------------------------------------------
You must agree to the following licenses prior to use:
* [High Performance ML Algorithms License](https://github.com/saeedmaleki/Distributed-Linear-Learner/blob/master/High%20Performance%20ML%20Algorithms%20-%20Standalone%20(free)%20Use%20Terms%20V2%20(06-06-18).txt)
* [TPN Ubuntu Container](https://github.com/saeedmaleki/Distributed-Linear-Learner/blob/master/TPN_Ubuntu%20Container_16-04-FINAL.txt)
* [Microsoft Third Party Notice](https://github.com/saeedmaleki/Distributed-Linear-Learner/blob/master/MicrosoftThirdPartyNotice.txt) 
