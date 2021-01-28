# Archive Notice
I have discontinued this project as I have not done any work on it recently, and due to the fact that Matrix does the same as what this spec was intended to do.

# IRCgen2-Specs
Specs for second generation of IRC

# What is IRCgen2?
IRCgen2 is a rewrite of IRC. Currently, IRC is a bunch of RFC's defining specs that are not fully implmented by many clients and servers. IRCgen2 is designed to clean up that mess by combining all of the features that are commonly used into one specfication.

# How the specs are organized.
## Compability Targets
** This section may change without notice. **

A compability target is a set of features that are in a group. The goal is that each client will support one or more compability targets in common with the server and other clients. Each compability target may also group other targets.

# Transport
IRCg2 will use a raw TCP or UDP socket the same as IRC. Extensions may be made that uses other protocols such as HTTP as a transport as well.
