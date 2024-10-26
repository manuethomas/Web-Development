## JavaScript Prototype
In JavaScript, the term prototype is used to refer to a special type of object that is associated with every function and object by default

### Important properties of Prototype

- **Inheritance** : In Js when a function is created, a prototype property for that function (which is an object) is automatically created. All instances of the function will inherit the properties and methods of the prototype

- **Shared methods**: By attaching methods to the functions prototype , all instances of the function share the same methods - memory efficiency

- **Prototype Chain**: JavaScript uses a prototype chain to look up properties and methods. If a property or method is not found on an object, JavaScript will look up the prototype chain to find it

### Example

```
function Person(name) {
    this.name = name;
}

Person.prototype.greet = function() {
    console.log(`Hello, my name is ${this.name}`);
};

const alice = new Person('Alice');
alice.greet(); // Outputs: Hello, my name is Alice

```