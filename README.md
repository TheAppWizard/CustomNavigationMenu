# CustomNavigationMenu
This project can be used for implementation of Custom Navigation Menu with help of SwiftUI

## Concepts Used

### ScrollView
It is used for `scrolling` up / down song list


```
 ScrollView(.vertical, showsIndicators: false) {
                VStack(spacing: 15){
                .
                .
                .
                .
                .
                .
                }
              }
              
```




### Slider
It is used for showing song `seek bar`


```
HStack {
       Text("1.04")
       Slider(value: $sliderValue, in: 0...20, step: 1)
       .accentColor(Color.red)
       Text("3.45")
       }.foregroundColor(Color.red)
       
```

### Creating Views / Screens
It is used for `creating views`

Example of Views / Screens

```
struct Queue : View {
    var body: some View{
        VStack{
            Text("Hello")
        }
    }
}
```









