---
layout: post
title: "Syntax Highlighting Example"
---

This post demonstrates the syntax highlighting feature that has been added to the blog.

## Ruby Example

```ruby
def hello_world
  puts "Hello, World!"
end

# A class example
class Person
  attr_accessor :name, :age
  
  def initialize(name, age)
    @name = name
    @age = age
  end
  
  def greet
    puts "Hello, my name is #{@name} and I am #{@age} years old."
  end
end

person = Person.new("John", 30)
person.greet
```

## JavaScript Example

```javascript
// Function declaration
function calculateSum(a, b) {
  return a + b;
}

// Arrow function
const multiply = (a, b) => a * b;

// Class example
class Counter {
  constructor(initialValue = 0) {
    this.count = initialValue;
  }
  
  increment() {
    this.count += 1;
    return this.count;
  }
  
  decrement() {
    this.count -= 1;
    return this.count;
  }
}

const counter = new Counter(5);
console.log(counter.increment()); // 6
console.log(counter.increment()); // 7
console.log(counter.decrement()); // 6
```

## Python Example

```python
def fibonacci(n):
    """Return the nth Fibonacci number."""
    if n <= 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)

# Class example
class Animal:
    def __init__(self, name, species):
        self.name = name
        self.species = species
        
    def make_sound(self):
        pass
        
class Dog(Animal):
    def __init__(self, name, breed):
        super().__init__(name, species="Dog")
        self.breed = breed
        
    def make_sound(self):
        return "Woof!"

# Create an instance
dog = Dog("Rex", "German Shepherd")
print(f"{dog.name} says: {dog.make_sound()}")
```

## HTML Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .highlight {
            background-color: yellow;
            padding: 2px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <p>This is a <span class="highlight">highlighted</span> text example.</p>
    </main>
    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>
</body>
</html>
```

## CSS Example

```css
/* Basic styles */
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

/* Header styles */
header {
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 5px;
  margin-bottom: 20px;
}

/* Responsive grid */
.container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
}

.card {
  border: 1px solid #ddd;
  border-radius: 4px;
  padding: 20px;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

/* Media query */
@media (max-width: 768px) {
  .container {
    grid-template-columns: 1fr;
  }
}
```

The syntax highlighting should now be working with different color schemes for different programming languages!
