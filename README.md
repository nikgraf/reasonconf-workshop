## Feedback form:

https://docs.google.com/forms/d/e/1FAIpQLSduti27Gold0T3WDtSe04Hi3V-yaBG0ChqAbS-t3-qoe4qsbA/viewform

## 1. Data Structures

Create a data-structure for a chess figure with the following attributes: color, position, kind

- The color can be either black / white
- The position has 2 dimensions on a typical chess board
- The kind describes the value of the figure (king, tower, pawn …)

Put your data-structures in action by storing 2 chess figures in a collection called figures:

- Figure 1: Black, King, on position A1
- Figure 2: White, Tower, on position C7

I recommend to use the playground for this example: https://reasonml.github.io/en/try

Alternative playground: https://sketch.sh/

Tip: You may use lists, arrays, tuples, variants for these tasks

## 2. Data Structures II

Create a file Data.re and inside create a list of places with the following properties

- id (generate uuids via https://www.uuidgenerator.net/ and copy & paste them in your code)
- name
- description
- image containing an url, attribution and attributionUrl (optional)
- address
- phone (optional)
- email (optional)
- coordinates containing lat and lng

## 3 Data transformation

1. Create an Array of all the names from your list of places. Print out the names in the end using the console. **Hint**: use `Js.log`.

First use only function calls (like in JavaScript) and then use the pipe first operator to chain the function calls. https://reasonml.github.io/docs/en/pipe-first
You should end up with the same result, but in a more readable manner.

2. Optional pro lesson: Create a search function. It accepts a list of places and a search term and will find all the items based on this term. For simplicity the function should only check against the place name. For an empty string it returns all entries. **Hint**: Use the `Js.String` module whenever you use BuckleScript.

## 4 ReasonReact Intro

1. Setup the editor -> https://reasonml.github.io/docs/en/editor-plugins

2. Create a new ReasonReact BuckleScript project -> https://reasonml.github.io/reason-react/docs/en/installation

```
npm install -g bs-platform
bsb -init my-react-app -theme react-hooks
cd my-react-app && npm install && npm start
# in another tab
npm run webpack
# in another tab
npm run server
```

3. Add your Data.re file

4. Render a list of the place names

5. Optional pro lesson: Render other place properties

