Script
------

The beginning of the demo can be found at tag demo-start-state
The end of the demo can be found at tag demo-done-state

+ Groups
Show Order and NoDelay on Customer and Country
Show StraigntToOrderValidation on Customer

+ Write
AnnotationProcessor
  Add and Show @Min( value = 2) on Order#getCustomer => AnnotationProcessor error
Composition:
  show getOrderNumber(), replace with @OrderNumber
  show how to write OrderNumber (@OverridesAttribute)
Complex constraint:
  show @ZipCode
  finish coding it
  show how to set a customizable message (intl or properties or both)
