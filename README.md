# Фичи разметки

## Спойлер

Часть текста можно убрать под спойлер:

```html
<details>

  <summary>
    Это заголовок спойлера
  </summary>

  Эта часть будет под спойлером
  
<details>
```

## Разрыв страницы

Если предполагается экспорт в PDF, то можно вставить принудительные разрывы страниц:

```html
<div style="page-break-after: always;"></div>
```

## Emoji

В текст можно вставлять [иконки](https://gist.github.com/rxaviers/7360908) (emoji). 

:exclamation: В VSCode они не показываются, а на гитхабе вполне.




