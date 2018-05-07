# meteor_1.6.2_break_coffeescript

Version of meteor: 9fc0251eeeaea096113743e9ebd68fe50a714118 - Mon May 7 17:02:25 2018 +0200

Error when adding tap:i18n

➜  test git:(master) ✗ ../meteor/meteor add tap:i18n 
 => Errors while adding packages:             
                                              
While selecting package versions:
error: Conflict: Constraint coffeescript@1.0.4 is not satisfied by coffeescript 2.2.1_1.
Constraints on package "coffeescript":
* coffeescript@=2.2.1_1 <- top level
* coffeescript@1.0.4 <- tap:i18n 1.8.2

