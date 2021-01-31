# Assignment 2: Hexagonal Architecure
In this assinment you need to migrate the Rooms example from a layered architecture to a Hexagonal one. In doing so you are required to:
* Put each component of the architecture in a separated module. See the TinderHexagonal and the buck-pal examples (links at the end)
* Create separated input ports (interfaces) for the operation that creates a new student and the creation of a new placement of a student to a classroom. Note that 
the former is a simple CRUD operation while the later is an actual use case
* You can keep al the read operations in a single interface for the input port

## Examples
* Example writte by Tom Hombergs author of the book "Get your hands dirty on clean Architecture. **Buckpal**: https://github.com/thombergs/buckpal
+ The Tinder example in Hexagonal architecture: https://github.com/DSI-Tecnocampus/TinderHexagonal. This a very close to what you need to do for this assignement.

## Layered Rooms code
* You can clone the following repository that contains the layered version of the code you need to transform to an Hexagonal Architecture: https://github.com/DSI-Tecnocampus/RoomsLayered
