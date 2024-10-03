```mermaid
classDiagram
    class Community {
    components
    +sampleFunc()
    }

    class User {
    components
    +sampleFunc()
    }

    class Profile {
    components
    +sampleFunc()                               
    }
  
    class Workouts {
        components
        +sampleFunc()
    }

    class Login {
        components
        +sampleFunc()
    }

    class Picture {
        components
        +sampleFunc()
    }

    Community "1" --> "many" User
    User "0..*" --> "1" Profile
    Profile "1" --> "1..*" Workouts
    Profile "1" --> "1" Login
    Profile "1" --> "1" Picture