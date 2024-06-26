# CSS-Grid

## 1. Властивість display

У цьому розділі ми розглянемо властивість `display`, її роль у **CSS Grid** і ключові відмінності між значеннями `grid` і `inline-grid`.

Знайомство з цими поняттями допоможе ефективно створювати універсальні та адаптивні макети з використанням **CSS Grid**.

1.  Створимо **div** з класом **_.container_** (робимо запис "Emmet"):
    `.container`

```html
<body>
  .container
</body>
```

Отримаємо:

```html
<body>
  <div class="container"></div>
</body>
```

2. Пропишемо властивості для класів

```css
.container {
  display: grid;
}

.container-inline {
  display: inline-grid;
}
```

`display: inline-grid;` - розміщують елементи в ряд

### Висновки

Властивість `display` використовується для визначення елемента як сіткового контейнера шляхом встановлення його значення `grid`.

`"grid"` створює блочний контейнер, який займає всю доступну ширину. У той же час `"inline-grid"` створює інлайн контейнер, який займає лише ширину, необхідну для розміщення його вмісту.

## 2. Створення колонок і рядків в CSS Grid

А тепер розглянемо властивості `grid-template-columns` і `grid-template-rows` у **CSS Grid**, які визначають кількість та розміри стовпців і рядків.

Комбінуючи обидві властивості, можна створювати широкий спектр сіток, які відповідають вимогам будь-якого дизайну.
