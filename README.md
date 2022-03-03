# swift-clean-code

## Table of Content

1. [Single Responsibility Principle](#single-res)
2. [Open Close Principle](#open-close)
3. [Liskov Substitution Principle](#liskov-sub)
4. [Interface Segregation Princile](#interface-seg)
5. [Dependency Inversion](#dependency-inversion)


## Single Responsibility Principle

Separate the responsibility into multiple classes and function 

```swift
  Class CalorieManager {
    init() {}
    
    private func calculateCalorie() {
      var calorie = ...
      ...
      ...
      
      if (calorie > 1000) {
        //Inform the user
        print("You exceedes todays calorie limit")
      }
    }
  }
```


## Open Close Principle
## Liskov Substitution Principle
## Interface Segregation Princile
## Dependency Inversion
