```mermaid
classDiagram
    class Community {
    Numerous Users
    +sampleFunc()
    }

    class User {
    components
    +sampleFunc()
    }

    class Profile {
    Account
    +sampleFunc()                               
    }
  
    class Workouts {
        Hypertophy
        Strength
        Cardio
        Recovery
        +sampleFunc()
    }

    class Login {
        Username
        Password
        +sampleFunc()
    }

    class Picture {
        components
        +sampleFunc()
    }

    class Messager {
        Match/Pass
        Send texts
        +sampleFunc()
    }

    class Rating {
        Multiple Reviews
        Shown in 5 Star Format
        +sampleFunc()
    }   

    Profile "1" --> "0..*" Rating
    Community "1" --> "1" Messager
    Community "1" --> "0..*" User
    User "0..*" --> "1" Profile
    Profile "1" --> "1..*" Workouts
    Profile "1" --> "1" Login
    Profile "1" --> "1" Picture