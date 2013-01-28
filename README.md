syrinx - A Programmable Network Relay
(c) 2013 - Chris Kennelly (chris@ckennelly.com)

Overview
========

Syrinx serves as a programmable proxy for network connections.

Injecting faults into network connections can be a useful approach to debugging and testing distributed sytems.    Servers under test direct traffic towards a syrinx instance.  According to rules set by a simple Lua script, this traffic is relayed onwards.  For fault testing, connections and chunks of data can be delayed or dropped altogether according to precise rules.
