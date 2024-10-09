```mermaid
classDiagram
    class User {
        username
        password
        email
        location
        experienceLevel
        profilePicture
        +updateProfile()
        +sendMessage()
    }

    class PersonalTrainer {
        certificationLevel
        experienceOnJob
        cost
        +changeCost()
    }

    class Message {
        send
        receiver
        content
        timestamp
        +send()
        +receive()
        +delete()
    }
  
    class Workout {
        workoutType
        time
        location
        +findWorkout()
    }

    class MatchCriteria {
        workoutType
        experienceLevel
        location
        trainerOrNot
        +filterUsers()
    }

    class Review {
        rating
        comment
        timestamp
        +addReview()
        +updateReview()
        +deleteReview()
    }

    User <-- PersonalTrainer
    User "1" -- "1" MatchCriteria
    User "1" -- "0..*" Message 
    User "1" -- "0..*" Workout 
    User "1" -- "0..*" Review 