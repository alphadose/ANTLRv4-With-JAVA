# ANTLRv4-In-Python

## How to use:-

```
python traverse.py <grammar_name> <grammar_rule> <file_path>
```

## Example:-

```
 python traverse.py Java compilationUnit sample.java 
 ```
 
 ## Output:-
 
```
AST output:
(compilationUnit (typeDeclaration (classOrInterfaceModifier public) (classDeclaration class Main (classBody { (classBodyDeclaration (modifier (classOrInterfaceModifier public)) (modifier (classOrInterfaceModifier static)) (memberDeclaration (methodDeclaration (typeTypeOrVoid void) main (formalParameters ( (formalParameterList (formalParameter (typeType (classOrInterfaceType String) [ ]) (variableDeclaratorId args))) )) (methodBody (block { (blockStatement (statement for ( (forControl (forInit (localVariableDeclaration (typeType (primitiveType int)) (variableDeclarators (variableDeclarator (variableDeclaratorId i) = (variableInitializer (expression (primary (literal (integerLiteral 1))))))))) ; (expression (expression (primary i)) <= (expression (primary (literal (integerLiteral 10))))) ; (expressionList (expression (expression (primary i)) ++))) ) (statement (expression (expression (expression (primary System)) . out) . (methodCall println ( (expressionList (expression (primary i))) ))) ;))) }))))) }))) <EOF>)
```

