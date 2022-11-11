# WWDC 2022 notes

## ! Most interesting thing !

Dynamic Island (14 Pro and 14 Pro Max)

## Navigation related Updates

Programmatic navigation through 'path'. When you append a value to this path, navigation stack pushes this view to the stack

For Multi column presentation on iPad and Mac, use NavigationSplitView e.g. Mail App

```NavigationSplitView {
  //List
} content: {
  Text("Choose a ca
} detail: {
  Text("Choose a recipe")
}
```
Value presenting [navigation links](https://developer.apple.com/documentation/swiftui/navigationlink/init(_:value:)-kj9v)


new modifiers: .navigationDestination
