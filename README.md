# Lyfy Rentals Back-end Development Program

## Description
Lyft Rentals provides vehicles for riders who are looking to rent a vehicle for personal use such as a weekend vacation!
I inherited an urgent project from a fellow colleague at Lyft who had to make a pivot to a different project. The colleague was in the process of developing a component that is used by the rental fleet’s new logistics system. 
Unfortunately that component was only partially completed and my responsibility is to now finalize that component and make it functional.The component itself is responsible for determining whether cars in Lyft’s new rental fleet should be serviced when they are returned.

## Tasks
1. Come up with a clean design for an existing, unfinished component
2. Refactor a messy codebase
3. Write unit tests for your newly refactored system
4. Add new functionality to your system using Test-Driven Development!


## Software Architecture

According to the new requirements, I refactored the codebase from using Inheritance to Composition, since composition has several benefits, including:
1. Flexibility: With composition, you can easily change the behavior of an object by swapping out one of its components, without affecting the rest of the object's functionality. This makes your code more flexible and easier to maintain.
2. Code Reuse: Composition allows you to reuse code more effectively, since you can create a library of small, reusable components that can be used in multiple contexts. This helps to reduce the amount of duplicate code in your application, making it easier to maintain.
3. Reduced Coupling: Composition reduces the coupling between objects, making your code more modular and easier to test. Since each component has its own interface, it's easier to test each component in isolation, without affecting the rest of the application.
4. Improved Abstraction: Composition allows you to create more abstract and generic components, since they are not tied to any specific implementation details. This makes your code more flexible and easier to adapt to changing requirements.

<img width="1114" alt="Screen Shot 2023-05-08 at 16 01 06" src="https://user-images.githubusercontent.com/95588190/236955471-a70bc852-b172-46b8-abf5-da897868d6af.png">





