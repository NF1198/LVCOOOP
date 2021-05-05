# LV Common Objects for Object Oriented Programming (LVCOOP)

LVCOOP is a set of common objects that support building robust object oriented applications with LabVIEW(tm).

## Lookup API

The Lookup API is depenency mangament service that allows you to inject instances of objects into your application at runtime instead of hard-coding them throughout your application. This is a powerful tool that supports building modular, reusable, and testable code.

## State Machine API

The State Machine API allows you to define a state machine as a state table (in text format), then compile this state table into a type-safe interpreted statemachine. As the implementer, you supply "guards" and "actions" VIs by reference. This approach makes is relatively easy to maintain, test, document, and implement small to large state machines with complex networks of transistions.

## Utility API

The Utility API includes a generic Logger implementation. A LabVIEW queue-based logging provider and an NI Error Log provider are also provided.

## How to install

### Building from source

1) Clone this repository
2) Edit the `LVCOOP - user.lib` source distribution to point to your `user.lib` directory
3) Build the `LVCOOP - user.lib` source distribution



\* *LabVIEW is a trademark of National Instruments Corporation*

