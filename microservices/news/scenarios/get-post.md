# Получение постов

## Получение всех постов

POST GraphQL запрос на поле news. Пример:

query{
    news{
        <параметры>
    }
}

<a href="../schema.json">структура полей для запроса ( Переведи из snake_case В camelCase! )</a>

## Получение конкретного поста по его id

POST GraphQL запрос на поле news. Пример:

query{
    news(postId: "postId"){
        <параметры>
    }
}

<a href="../schema.json">структура полей для запроса ( Переведи из snake_case В camelCase! )</a>

## Получение всех постов конкретного автора по id автора

POST GraphQL запрос на поле news. Пример:

query{
    news(userId: "userId"){
        <параметры>
    }
}

<a href="../schema.json">структура полей для запроса ( Переведи из snake_case В camelCase! )</a>