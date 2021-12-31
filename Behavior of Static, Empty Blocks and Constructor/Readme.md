## Static Block 

Inside the static block code is executed only once. the first time the class is loaded into memory. No matter waht is the order of the codes static 
block it executed at first.

## Empty Block

Empty block inside codes are execute after static blocks and before constructor.They run each time when instance of the class is created.
in that  class Application outputs you can see empty blocks are print after static block and before constructors.There are two constructors 
one is default constructor and other one is one argument constructor when both constructors called you can see that empty block execute 
and get the output before constructors.Becuase it run each time when class create and object.

## Constructors

Default constructor execute after static and empty block and one argument constructor execute after static block ,empty block,default constructor 
and again empty block.here empty block execute becuase when to calling this constructor we create an instance that's why it will print again.