# Rice is Nice: Coding with a Grain of Rice

## Introduction to Rice
Rice sustains over half of the global population, with a strong presence in Asian, Latin American, and African cuisines. It comes from the grass species *Oryza sativa* or *Oryza glaberrima*. Not just a staple, rice is nutritionally vital, culturally significant, and versatile in culinary arts.

## Types of Rice
Explore the variety of rice:
- **White Rice:** Milled and polished, removing husk, bran, and germ.
- **Brown Rice:** Only the husk is removed, retaining nutrients in the bran and germ.
- **Basmati Rice:** Known for its unique aroma and long grains.
- **Jasmine Rice:** A long-grain rice with a distinctive sweet scent.
- **Wild Rice:** The seed of water grasses, offering a unique flavor and texture.

## Nutritional Profile
Rice is predominantly a carbohydrate source, with brown rice leading in fiber, vitamins, and minerals due to its whole grain status.

## Cultural Impact
Rice symbolizes prosperity and fertility, playing a central role in various cultural events and traditions.

## Culinary Uses
From savory pilafs and creamy risottos to sweet rice pudding, rice's versatility is unmatched. It's also transformed into flour, vinegar, and oil.

## Rice and JavaScript
Let's draw parallels between the versatility of rice and JavaScript's flexibility.

### Example 1: Basic Operations - Counting Rice Varieties
```javascript
let riceVarieties = ['Basmati', 'Jasmine', 'Arborio', 'Sushi', 'Wild'];

function countRiceVarieties(varieties) { return varieties.length; }

console.log(countRiceVarieties(riceVarieties)); // Outputs: 5
```

Example 2: Array Manipulation - Filtering Rice Types

```javascript
// Array of rice objects with type and if they're whole grain
let riceTypes = [
  { name: 'Basmati', isWholeGrain: false },
  { name: 'Brown', isWholeGrain: true },
  { name: 'Jasmine', isWholeGrain: false },
  { name: 'Wild', isWholeGrain: true }
];

// Function to filter whole grain rice types
function filterWholeGrainRice(types) {
  return types.filter(type => type.isWholeGrain);
}

console.log(filterWholeGrainRice(riceTypes));
// Outputs: [{ name: 'Brown', isWholeGrain: true }, { name: 'Wild', isWholeGrain: true }]
```

Example 3: Object Handling - Calculating Average Protein in Rice

```javascript
// Object containing rice types and their protein content per 100g
let riceProteinContent = {
  'Basmati': 3.5,
  'Brown': 2.6,
  'Jasmine': 3.0,
  'Wild': 4.0
};

// Function to calculate average protein content
function calculateAverageProtein(content) {
  let totalProtein = 0;
  let numberOfTypes = 0;

  for (let type in content) {
    totalProtein += content[type];
    numberOfTypes++;
  }

  return totalProtein / numberOfTypes;
}

console.log(calculateAverageProtein(riceProteinContent)); // Outputs: 3.275
```

These examples are simple yet demonstrate how you can manipulate data in JavaScript, and they can be expanded or combined to handle more complex scenarios involving rice data.

Credit to OpenAI and RiceIsNice GPT 
https://chat.openai.com/g/g-39OE3Y8er-riceisnice


