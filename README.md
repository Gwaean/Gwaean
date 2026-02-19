
 

- 👋 Hi, I’m **Gwaean**, also known as *Nikki* or Nicole
-  I've always been curious about everything since I was little, I was loved reading and reasearching things :) I've always liked learning things and doing arts,
  and somehow computing found me and I'm so glad it did!
-  I´m part of a research project @ELLASNetwork, we work with open data, graphs and ontology. And our goal it´s to create an open data portal about women in STEM in Latin America, specially about iniciatives and projects that help attract and/or keep and empower girls for STEM areas.
-  I'm also part of a team of girls who develop games - Code Siren :)
-  key interests: Game Dev, HCI & Cybersecurity;


![Zara Larsson Summer GIF](https://github.com/user-attachments/assets/d86b4ac4-459d-47f3-af44-9d6c9359383c)


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


