# Object-Oriented Programming Study Guide

---

## Learning Objectives

- To understand the concept of Object Orientation.
- To gather information about Object-Oriented Software Development.
- To identify elements of an object model.
- To identify classes and objects.
- To specify attributes.

---

## 4.1 What is Object Orientation? - Introduction

In object-oriented terms, the **"object"** is a general concept defined as "a thing presented to or capable of being presented to the senses."

### Features of Object Orientation

- **System Modeling:** Considers objects as basic building blocks.
- **Instance of Class:** An object is an instance of a class. All objects in a class share state and behavior.
  - **Example:** If `Student` is a class, specific students (e.g., John, Mary) are its objects.

---

### Principles of Object Orientation

1. **Abstraction:** Focuses on the essential details while ignoring the rest.
2. **Modularity:** Divides complex systems into manageable, self-contained parts.
3. **Hierarchy (Inheritance):** Represents relationships using a tree-like structure:
   - **Single Inheritance**
   - **Multiple Inheritance**
   - **Multilevel Inheritance**
   - **Hybrid Inheritance**
4. **Encapsulation:** Separates implementation details from the user.
5. **Polymorphism:** Allows an entity to take multiple forms (e.g., overloading `+` for numbers and strings).

---

## 4.1.1 Reasons to Use Object Orientation

1. **Higher Level of Abstraction:** Encapsulates data and functions within objects.
2. **Continuous Transition:** Uses consistent terminology across all development phases.
3. **Good Programming Techniques:** Classes maintain tight relationships with their attributes and interfaces.
4. **Reusability:** Objects modeled from real-world problems are reusable.
5. **Adaptability and Maintenance:** Systems are easier to adapt to changing requirements.

---

## 4.1.2 Object-Orientation Terminology

| **Term**         | **Definition**                                                                       |
|-------------------|---------------------------------------------------------------------------------------|
| **Object**        | Basic runtime entity with identity, state, and behavior.                             |
| **Class**         | A collection of objects of similar type.                                             |
| **Attribute**     | Describes characteristics of an object (e.g., color, height).                        |
| **Field**         | A named value within an object.                                                      |
| **Operation**     | A function belonging to an object.                                                   |
| **Method**        | Synonym for operation.                                                               |
| **Instance**      | An actual object of a class.                                                         |
| **Message**       | A request sent from one object to another.                                           |
| **Association**   | Connection between two objects.                                                     |
| **Aggregation**   | A strong association implying a part-to-whole hierarchy.                             |
| **Composition**   | A stronger aggregation where parts are created and destroyed by the whole.           |

---

## 4.1.3 Object

- **Definition:** An object is "an abstraction of something of interest to the program."
- **Components:**
  - **Identity:** Unique name distinguishing it from other objects.
  - **State:** The current properties of the object.
  - **Behavior:** Actions the object can perform.

---

## 4.1.4 Classes and Instances

- **Class:** A blueprint describing attributes and behaviors.
  - **Example:** A `Tree` class can represent Palm, Mango, or Tamarind trees.
- **Instance:** A concrete object created from a class.
  - **Example:** A Mango Tree is an instance of the `Tree` class.

---

## 4.1.5 Polymorphism

- **Definition:** "Many forms." Allows different objects to respond to the same operation.
  - **Example:** A `Shape` class may have a `Draw()` method implemented differently for circles and rectangles.

---

## Types of Inheritance

1. **Single Inheritance:** A class derives from one base class.
2. **Multiple Inheritance:** A class derives from multiple base classes.
3. **Multilevel Inheritance:** A class derives from a derived class.
4. **Hierarchical Inheritance:** Multiple classes derive from a single base class.
5. **Hybrid Inheritance:** Combines multiple types of inheritance.

---

## 4.2 Object-Oriented System Development

- Encourages building self-contained modules or objects that can be reused and replaced easily.
- **Phases:** Analysis → Design → Implementation.
- Focuses on integrating data and functions.

---

## 4.2.3 Object-Oriented Analysis (OOA)

- **Purpose:** Understanding functional requirements by identifying objects and their relationships.
- **Tasks:**
  - Finding objects.
  - Organizing objects into classes.
  - Defining operations on objects.

---

## 4.4 Identifying Classes and Objects

- Classes define the template for objects.
- Objects are real-world entities identified in the application domain.
  - Example: For a banking system, `Customer`, `Account`, and `Bank` are relevant objects.

---

## 4.5 Specifying Attributes

- **Definition:** Represents data associated with an object.
  - Example: A `Customer` class has attributes like `Name`, `Address`, and `Phone Number`.

---

## 4.6 Defining Operations

- **Definition:** Functions that define the behavior of an object.
- **Syntax Example:**
  ```text
  +display() // Public visibility
  -calculateTax() // Private visibility
