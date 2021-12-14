## GeneratingTitlesWithText

* Python3 textgenrnn
* https://www.datainmotion.dev/2021/08/building-bad-titles-for-talks.html
* https://github.com/minimaxir/textgenrnn

````

####################
Temperature: 0.5
####################
BUILDING EVENT AND PULSAR

Streaming SQL and Stack for Cloud Data Trying

Using the FLaNK Streaming in Accessing with Pulsar

####################
Temperature: 1.0
####################
Using Apache MoDeen with FliP

Apache NiFi : Ingesting the Bad words Processing

Using Apache MXNet anything

Pulsar Streaming in Pulsar

FLiP Stack for Cloud Data DevOps

FLiP Into ScyllaDB Pipelines

Processing a Stream into AI as Apache  Pulsar

Real-Time Streaming Pipelines with Apache NiFi

FLINK Everywhere

BUILDING EVENT STREAMING WITH WEBSOCKETS AND PULSAR

````

### Ran 12 Epochs

````
from textgenrnn import textgenrnn

textgen = textgenrnn()

textgen.train_from_file('tim.txt', num_epochs=12)
textgen.generate()

# Once you have trained

from textgenrnn import textgenrnn

textgen = textgenrnn()

textgen_2 = textgenrnn('textgenrnn_weights.hdf5')
textgen_2.generate(3, temperature=1.0)

````
#### Some real winners

````
Cracking the NiFi Data Lakes

Let's Stop Social Microservices and FLiP

Codeless Streaming with Apache Pulsar for Cloud Data Lake

Let's Build A Simple Ingest To Pulsar

2021-12-14 09:21:17.804904: I tensorflow/compiler/mlir/mlir_graph_optimization_pass.cc:176] None of the MLIR Optimization Passes are enabled (registered 2)
Data DevOps

 33%|███████████████████▋                                       | 1/3 [00:00<00:01,  1.04it/s]Autimation AI:  Build Real-time for Edge and Apache Pulsar

Build an event-driven art for Edge as Apache Pulsar

 33%|███████████████████▋                                       | 1/3 [00:01<00:03,  1.88s/it]Streaming in Azure

 67%|███████████████████████████████████████▎                   | 2/3 [00:02<00:01,  1.04s/it]Building Real-Time Weeses from you Social Computing
 
 Automating tiill with Let Pulsar, Deep Divent Streaming, Streaming with Pulsar and Flink, As Apache Pulsar Functionsits Apache NiFi
 
 Continous DevOck NiFi DevOck

 33%|███████████████████▋                                       | 1/3 [00:01<00:02,  1.47s/it]Driven into ScyllaDB

 67%|███████████████████████████████████████▎                   | 2/3 [00:02<00:00,  1.06it/s]Driven Microservices with NiFi and Real-tips
 
````
