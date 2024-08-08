# Very meaningful title
###### Smol meaninful title

![cilantro](https://github.com/user-attachments/assets/23cda179-07c7-4966-9520-57f7b845b3a9)

```
# "Compiling" a sandwich in Python

class Sandwich:
    def __init__(self):
        self.ingredients = []

    def add(self, ingredient):
        self.ingredients.append(ingredient)
        print(f"Added {ingredient} to the sandwich.")

    def compile(self):
        if not self.ingredients:
            print("Error: Sandwich has no ingredients!")
            return

        print("\nCompiling sandwich...")
        for ingredient in self.ingredients:
            print(f"- {ingredient}")
        print("\nSandwich compilation complete!")

# Usage
my_sandwich = Sandwich()
my_sandwich.add("Bread")
my_sandwich.add("Lettuce")
my_sandwich.add("Tomato")
my_sandwich.add("Cheese")
my_sandwich.add("Ham")
my_sandwich.add("Another slice of Bread")

my_sandwich.compile()

# Result:
# Added Bread to the sandwich.
# Added Lettuce to the sandwich.
# Added Tomato to the sandwich.
# Added Cheese to the sandwich.
# Added Ham to the sandwich.
# Added Another slice of Bread to the sandwich.

# Compiling sandwich...
# - Bread
# - Lettuce
# - Tomato
# - Cheese
# - Ham
# - Another slice of Bread

# Sandwich compilation complete!
```

- [X] Get some bread
- [ ] Make samich
- [ ] Eat samich
