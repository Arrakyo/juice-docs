# directory

Contract: [`JBControllerUtility`](/protocol/api/contracts/or-abstract/jbcontrollerutility/README.md)​‌

Interface: [`IJBControllerUtility`](/protocol/api/interfaces/ijbcontrollerutility.md)

**The directory of terminals and controllers for projects.**

#### Definition

```
/** 
  @notice 
  The directory of terminals and controllers for projects.
*/ 
IJBDirectory public immutable override directory;
```

* Once set the value cannot be changed.
* The resulting view function can be accessed externally by anyone.
* The resulting function overrides a function definition from the [`IJBControllerUtility`](/protocol/api/interfaces/ijbcontrollerutility.md) interface.