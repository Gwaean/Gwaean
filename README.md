
 

- 👋 Hi, I’m @Gwaean, also known as Niki or Nicole
-  I’m interested in gaming, books (specially sci-fi and fantasy!), arts & drawing, UI/UX Design and obviously computing :) 
-  I’m currently working as a Change Management trainee at ExxonMobil and studying information systems at UTFPR.
-  I´m part of a research project @ELLASNetwork, we work with open data, graphs and ontology. And our goal it´s to create an open data portal about women in STEM in Latin America, specially about iniciatives and projects that help attract and/or keep and empower girls for STEM areas.
-  key interests: UX Design, Intelligence Systems & Data Science;

![Studio Ghibli Goodbye GIF - Find   Share on GIPHY](https://user-images.githubusercontent.com/56048874/178127308-d6f1f6f7-9388-429d-9431-2fb7a23ee7f2.gif)

```swift
struct Person: Identifiable {

    let name = "Nicole D. Hildebrand"
    let language: String
}
private var programmingLanguages = [

    Person(language: "C"),
    Person(language: "C++"),
    Person(language: "Java"),
    Person(language: "Swift"),
    Person(language: "Python"),
    Person(language: "Lua"),
    Person(language: "CSS"),
    Person(language: "HTML"),
    Person(language: "SPARQL")
]
var body: some View {

    List(programmingLanguages) {
        Text($0.language)
    }
}
```


