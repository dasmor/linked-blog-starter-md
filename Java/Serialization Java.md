Used for store and sending object, makes possible to represent object as bytes.

Common use cases include **saving object states to files, sending objects over a network, and storing objects in databases** and **CACHE**.


The serialization runtime associates with each serializable class a version number, called a **serialVersionUID**, which is used during deserialization to verify that the sender and receiver of a serialized object have loaded classes for that object that are compatible with respect to serialization.