# Strategy Pattern

We decouple the behaviour from the class. The duck doesn't know implementation details about how to fly. This behaviour lives in a separate class - one that implements this behavior's interface. (IFlyBehavior - FlyWithWings).
This behavior may be changed at runtime!

The key is that a Duck delegates its flying behavior, instead of using defined flying methods inside its class. 
