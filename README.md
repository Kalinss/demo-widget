# demo-widget

## Виджет бейджик

```angular2html
// Добавить в конец тега body
<body>
    ...
    ...
    ...
    <script src="https://myreviews.dev/widget/dist/index.js"></script>
    <script>
        new window.myReviews.BadgeWidget({
            id: 323, // id вашей коммпании на сервисе
            name: "badgeWidget-1" // уникальное название среди остальных виджетов
        }).init()
    </script>
</body>
```

## Вертикальный виджет
```angular2html
// Добавить в конец тега body
<body>
    ...
    ...
    ...
    <script src="https://myreviews.dev/widget/dist/index.js"></script>
    <script>
        new window.myReviews.VerticalWidget({
            id: 323, // id вашей коммпании на сервисе
            name: "verticalWidget-1" // уникальное название среди остальных виджетов
        }).init()
    </script>
</body>
```