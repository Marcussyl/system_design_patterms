# Design Patterns in TypeScript

This repository contains simple, real-world analogies and implementations of classic software design patterns in TypeScript. Each pattern is demonstrated with clear, concise code and comments to help you understand not just how the pattern works, but also **why** and **when** you might use it.

## Patterns Included

### Behavioural Patterns

- **Strategy Pattern**  
  Select an algorithm's behavior at runtime.  
  _Example: Payment processing system with interchangeable payment methods._  
  See: [`behavioural/strategy_pattern.ts`](behavioural/strategy_pattern.ts)

- **Observer Pattern**  
  Define a one-to-many dependency so that when one object changes state, all its dependents are notified.  
  _Example: Notification system with subscribers and publishers._  
  See: [`behavioural/observer_pattern.ts`](behavioural/observer_pattern.ts)

- **Iterator Pattern**  
  Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.  
  _Example: Book collection with an iterator to traverse books._  
  See: [`behavioural/iterator_pattern.ts`](behavioural/iterator_pattern.ts)

### Structural Patterns

- **Facade Pattern**  
  Provide a simplified interface to a complex subsystem.  
  _Example: Home theater system with a single interface to control multiple devices._  
  See: [`structural/facade_pattern.ts`](structural/facade_pattern.ts)

- **Adapter Pattern**  
  Allow incompatible interfaces to work together.  
  _Example: Charging an old phone with a new USB-C charger using an adapter._  
  See: [`structural/adaptor_pattern.ts`](structural/adaptor_pattern.ts)

---

## How to Use

1. **Clone the repository**
2. **Open any `.ts` file** to explore the pattern and its analogy.
3. **Run the code** using [ts-node](https://typestrong.org/ts-node/) or compile with `tsc` and run with Node.js.
