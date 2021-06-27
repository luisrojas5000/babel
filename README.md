# Babel project 

The objective of the babel project is to create a system of libraries that allow the interconnection of data management, which make up the structure of industrial web applications, using an atomic design system, designed to avoid unnecessary capabilities that add much complexity to development.

The system would consist of three main parts.
- Define basic contracts for the separation of the view and the controller, under the context of the atomic applications.
- CLI generation of npm archetypes, which complies with established contracts, with an archetype that allows easy creation of atomic components.
- Creation by means of a CLI command in vaadin of the mocks entities that represent the atomic components.
- Creation of a ui interface, which allows managing the implemented models to populate the components.

Finally, the user will enter the data through the vaadin user interface and from here he will be able to load the components and choose the ones he wants to use from the existing business logic.

So by keeping the vaadin logic of the components decoupled, they could be used by other systems such as angular, vue, etc.