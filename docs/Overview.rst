Overview
========
The OSIsoft Message Format (OMF) defines a set of message headers and bodies that can be used to generate messages for ingestion into a compliant system.

OMF can be used to develop data acquisition applications on platforms and in languages for which there are no supported OSIsoft libraries.

OMF itself does not define or depend on any particular binary message protocol (HTTP, AMQP, Kafka, etc.) It is instead based on an abstract message type, where a message consists of a set of key / value pairs, called the headers, and a binary payload, called the body. OMF messages can thus be constructed using any message protocol that defines headers and bodies. For up to date information on the specific binary protocols currently supported by OSIsoft systems, consult the OSIsoft Cloud Services and PI Connector Relay documentation.

