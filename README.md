# demo-widget

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
            name: "verticalWidget-1", // уникальное название среди остальных виджетов,
            additionalFrame:"button" // "button" | "badge" 
        }).init()
    </script>
</body>
```