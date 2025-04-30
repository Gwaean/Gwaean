
 

- 👋 Hi, I’m _Gwaean_, also known as *Nikki* or Nicole
-  I've always been curious about everything since I was little, I was loved reading and reasearching things :) I've always liked learning things and doing arts,
  and somehow computing found me and I'mm so glad it did!
-  I´m part of a research project @ELLASNetwork, we work with open data, graphs and ontology. And our goal it´s to create an open data portal about women in STEM in Latin America, specially about iniciatives and projects that help attract and/or keep and empower girls for STEM areas.
-  key interests: Game Dev, Distributed Systems & UI/UX Design;

![Studio Ghibli Goodbye GIF - Find   Share on GIPHY](https://user-images.githubusercontent.com/56048874/178127308-d6f1f6f7-9388-429d-9431-2fb7a23ee7f2.gif)

```swift
struct Person: Identifiable {

    let name = "Nicole D. Hildebrand"
    let language: String
}
private var programmingLanguages = [

    Person(language: "C"),
    Person(language: "C#/C++"),
    Person(language: "Ruby"),
    Person(language: "Swift"),
    Person(language: "Python"),
    Person(language: "Lua"),
    Person(language: "HTML5/CSS"),
    Person(language: "JavaScript"),
    Person(language: "SPARQL"),
    Person(language: "SQL")
]
var body: some View {

    List(programmingLanguages) {
        Text($0.language)
    }
}
```


