## Практика "Игра" | Дизайн-документ

## Основное
- Платформа: PC
- Среда: C# Monogame
- Язык: English
- Жанр: Top-Down , Arcade 
- Оформление: Пиксельная графика

## Сюжет
Главному герою мечнику предстоит найти таинственный артефакт, попутно разбираясь с врагами, стоящими у него на пути.

## Геймплей
Вся игра проходит в минималистичном пространстве, содержащем стены, двери, ключи от дверей, ловушки, лечащие хп или увеличивающие урон предметы.

Концепт прост. Пропустить как можно меньше урона по себе, суметь пройти через врагов и через ловушки в конец уровня и не умереть.

Планируется сделать 3-4 уровней. В самом начале герою в пользование даётся слабейший меч с минимальным уроном, 
по мере прохождения уровней меч можно улучшить, а враги также становятся сильнее.

### Характеристики меча
- Урон
- Скорость атаки
- Площадь атаки


## Враги (названия каждому типу врага пока не дал)

### Характеристики врага
- Урон
- Здоровье
- Скорость передвижения
- Скорость атаки

### Тип врага
 + 1 тип: Урон 1HP, имеет 2HP
 + 2 тип: Урон 1HP, накладывает слабость при атаке, имеет 1HP
 + 3 тип: Урон 1HP, атакует быстрее, имеет 3HP
 + 4 тип: Урон 2HP, имеет 2HP

## Классы
-Sprites.cs
-Player.cs
-Sword.cs
-Obstacle.cs


