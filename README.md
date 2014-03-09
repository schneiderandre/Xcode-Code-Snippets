#Xcode Code Snippets

A list of Xcode snippets that you can use in your daily work and I backed up here in case I lose my data.
If you only need a certain snippet, just compare the Indentifier with the snippet name and grab the matching.

This collection is work in progress, so please don't be sad if it does not include many snippets right now.

##Using the Snippets
Simply paste the snippets to `~/Library/Developer/Xcode/UserData/CodeSnippets/`.
Then use them with the defined shortcut or via the Code Snippets Library.

##Snippets
###Property declaration for Classes
Declare a strong property for classes with the shortcut `propclass`. The `strong` attribute has been left out, since it is a default attribute for an object.

The Snippet Identifier is B89FB628-39AD-4020-A3E4-377A55DADF04.
```objc
@property (nonatomic) <#class#> *<#name#>;
```

###Property declaration for Primitives
Declare a nonatomic, assigned property for primitives with the shortcut `propprim`. The `assign` attribute has been left out, since it is a default attribute for a primitive.

The Snippet Identifier is BB615F7C-42B4-4D8E-B9DC-E88E67AECF9E.
```objc
@property (nonatomic) <#primitive#> <#name#>;
```
