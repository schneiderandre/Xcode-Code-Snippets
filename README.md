#Xcode Code Snippets

A collection of some useful Xcode Code Snippets.

This collection is work in progress, so please don't be sad if it does not include many snippets right now.

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
