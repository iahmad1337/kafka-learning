# Learning kafka
- Quick reads:
  - https://medium.com/@taapasagrawal/installing-and-running-apache-kafka-on-macos-with-m1-processor-5238dda81d51
  - https://www.redhat.com/en/blog/apache-kafka-10-essential-terms-and-concepts-explained
- Full glossary: https://docs.confluent.io/glossary.html
- Zookeeper terminology: https://data-flair.training/blogs/zookeeper-terminologies/
- Exercises (use in-browser translator from spanish): https://github.com/ogomezso/kafka-exercises/tree/main
- Full one-page documentation: https://kafka.apache.org/documentation

## Installation
```bash
brew install java
brew install kafka
```

## Start kafka
```bash
# Start kafka
/opt/homebrew/opt/kafka/bin/kafka-server-start /opt/homebrew/etc/kafka/server.properties
# or start it as a daemon
brew services start kafka
```
