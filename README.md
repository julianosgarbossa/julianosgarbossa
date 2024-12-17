```swift
struct Developer {
    let name = "Juliano Sgarbossa"
    let role = "iOS Developer"
    let location = "Brazil - RS"
    let skills = [
        "Swift", 
        "UIKit (View Code)", 
        "SwiftUI", 
        "MVVM", 
        "Firebase"
    ]
    let learning = ["Core Data", "Keychain", "Vapor"]
    let hobbies = ["Coding 💻", "Reading 📚", "Soccer ⚽️"]
    
    func introduceYourself() {
        print("""
        Olá! 👋
        
        Eu sou o \(name), um \(role) que mora no \(location).
        
        Algumas das minhas habilidades são:
        \(skills.joined(separator: ", ")).
        
        Estou sempre buscando aprender coisas novas, como:
        \(learning.joined(separator: ", ")).
        
        E nos meus momentos livres, gosto de:
        \(hobbies.joined(separator: ", ")).

        Seja bem vindo ao meu perfil e é um prazer conhecer você!
        --------------------------------------------------------
        """)
    }
}

let me = Developer()
me.introduceYourself()
