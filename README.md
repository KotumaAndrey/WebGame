# Sea-Battle

Useful link for the history of this game - https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D1%80%D1%81%D0%BA%D0%BE%D0%B9_%D0%B1%D0%BE%D0%B9_(%D0%B8%D0%B3%D1%80%D0%B0)

## Game entities:
Player's and computer's battlegrounds and 4 types of ships(one-deck, two-deck, three-deck, four-deck).

So, this game aldo should include 2 types of ship placement - random and drag and drop. 
Random placement: 

![изображение](https://user-images.githubusercontent.com/73333613/160922134-5ea93e05-4089-4898-b709-02f99893be82.png)

Drag and drop placement: 

![изображение](https://user-images.githubusercontent.com/73333613/160923932-28898185-63a8-4f7f-9395-b585fbe52072.png)

Both battlegrounds: 

![изображение](https://user-images.githubusercontent.com/73333613/160927020-b13625c8-a3e5-411f-b6db-ec9293a146ca.png)

## Rules:

### Placing: 
1 ship - a row of 4 cells ("four-deck") 2 ships - a row of 3 cells ("three-deck") 3 ships - a row of 2 cells ("two-deck") 4 ships - 1 cell ("single-deck"). All ships can e placed randomly. Or you can use the option when you drag the ship with the left mouse button to the available cells of the playing field. After you drop the ship to youw field you can change it's direction by right clicking on it (from vertical to horisontal if it is available or back)ю When placed, ships cannot touch each other by sides and corners.

### Sinking enemy ships:
The winner is the one who first sinks all 10 enemy ships. 
The players take turns. The move consists in choosing a cell that the player has not yet shot at. If the player hits the ship, then he walks again. At the same time, according to hardcore rules, it is not known whether the ship is killed or wounded, so more shots are required. In case of a miss, the turn is transferred to another player. 
When hitting an enemy ship, a cross is placed on a foreign field, with a blank shot - a dot. Also you have an opportunity to mark some fields with the right mouse button.

## Control:

In placement part of the game user can use the left mouse button to drag and drop ships to his field and the right mouse utton to change direction of the ship, no other buttons is used. In the sinking part user can use the left mouse button to do the shot on opponent's field or right mouse button to matk the field as not-a-ship field.

## Technology stack:
- Html
- CSS
- JavaScript
- ES6 Classes
- Webpack
- Webpack 5 Boilerplate Template by WeAreAthlon
- webpack 5.68.0
- Babel 7
- SASS/PostCSS

## Project structure:
images you can find in src/images/content folder,
java-script files you can in src/js and src/js/game folders,
css-files you can find in src/scss folder,
html file you can find in src folder.

![изображение](https://user-images.githubusercontent.com/73333613/160929022-3ea24139-eeaa-4bd3-a684-7f1d9545e97b.png)

## Run and assembly:
To run at the developer mode local server go to "../frontend-webpack-boilerplate" and type into console "npm run dev".
