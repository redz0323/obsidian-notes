- The implementation of an [[Object]] having different manifestations/forms.

## Method Overriding
- Method overriding is a run-time polymorphism.
- The derived class provides the specific implementation of the method that is already provided by the base class or parent class
- It is used to grant the specific implementation of the method which is already provided by its parent class or superclass.
- It is performed in two classes with inheritance relationships.
- Method overriding always needs [[Inheritance]].
- Methods must have the same name and same signature.
- The return type must be the same or co-variant.
- It gives better performance. The reason behind this is that the binding of overridden methods is being done at runtime.
- Argument list should be same in method overriding.

## Method Overloading
- Method overloading is a compile-time polymorphism.
- More than one method shares the same method name with a different signature in the class
- It helps to increase the readability of the program.
- It occurs within the class.
- Method overloading may or may not require [[Inheritance]].
- Methods must have the same name and different signatures.
- The return type can or can not be the same, but we just have to change the parameter.
- Poor Performance due to compile time polymorphism.
- Argument list should be different while doing method overloading.