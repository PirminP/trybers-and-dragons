# :construction: README em construção ! :construction:

# Project Trybers and Dragons
#### This project consists of a class structure for creating characters in a Role Playing Game.

* Developed using Typescript
* Using the principles of OOP and SOLID Architecture

It is possible to create characters with their race (dwarf, elf, halfling or orc) and their archetypes (mage, necromancer, ranger or warrior), along with information on their name, life points, energy type, dexterity and defense, as shown below:

  ```
  src
  ├── Archetypes
      ├── Mage
      ├── Necromancer
      ├── Ranger
      └── Warrior
  ├── Defense
  ├── Dexterity
  ├── Energy
  ├── LifePoints
  ├── MaxLifePoints
  ├── Name
  ├── Race
      ├── Dwarf
      ├── Elf
      ├── Halfling
      └── Orc
  ├── attack()
  ├── levelUp()
  └── receiveDamage()

```


### Instructions
* To run the repository locally, clone the project and use the following commands to initialize Docker & install all dependencies:

  ```
  docker-compose up -d // start application with docker
  docker exec -it trybers_and_dragons bash
  npm install // install dependencies
  docker-compose down // stop application
  ```
`Note:` After installing the dependencies, check the files in the `./src` folder, which contains the classes created to build the characters.
