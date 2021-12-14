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
````
