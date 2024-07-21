# This is Sendiko's commit guide

<br>

there's 3 component for the commit message
---
 - functon name
 - function parameter
 - function body / function message

### example ``` enc(imp): ViewModelFactory ```

``` enc ``` is function name.

``` imp ``` is function parameter.

``` ViewModelFactory ``` is function body / function message.

<br>

and here's list of function name and the purpose:
---
 - ``` init ``` -> for initial commit.
 - ``` enc ``` -> any improvement or addition to the source code.
 - ``` ref ```  -> refactoring the code, like rename fun, variables, or code restructure.
 - ``` del ``` -> deletion of unused files or piece of code.
 - ``` res ``` -> addition for resources files like images, or xmls.
 - ``` gradle ``` -> any changes to gradle files.

<br>

and this is a list for function parameter:
---
 - ``` add ``` -> for adding piece of code.
 - ``` crea ``` -> for creation of important code.
 - ``` imp ``` -> for implementing important code.
 - ``` app ``` -> for applying newly created code.

 <br>

 for function body:
 ---
any name is fine, just don't mention what already mention in the function body and/or parameters.

bad example: ``` enc(add): Adding DaggerHilt ```

the ``` Add ``` inside function body is not neccessary, it's already mention in the parameters.

good example: ``` enc(add): DaggerHilt ```

the function body gives additional information about what's being created, withiout re-stating what's already mentioned in the function body and/or parameter.
