# JSON Exercises

1. Create a JSON structure to represent a person with the following attributes: name, age, and isStudent.

```json
{
 "name": "Barbara Antelo",
 "age": 34,
 "isStudent": true   
}
```

2. Create a JSON structure to represent a book with the following attributes: title, author, and publication year.

```json
{
    "book": {
        "title": "Eufi, el secreto mejor guardado",
        "author": "Barbara Antelo",
        "publication year": 2016
    }
}
```

3. Create a JSON structure to represent a car with the following attributes: make, model, and mileage.

```json
"car": {
    "Brand": "Suzuki",
    "Model": "Alto 2022",
    "Mileage": 20000
}
```


4. Create a JSON structure to represent a shopping list with the following items: apples, bread, milk, and eggs.

```json
{
"Shopping list": ["apples", "bread", "milk", "eggs"]
}
element = shopping_l[2]
car.Brand = "Ford"
```


5. Create a JSON structure to represent a movie with the following attributes: title, director, releaseYear, and isPopular.

```json
{
"movie": {
    "title": "Harry Potter",
    "director": "blabla",
    "releaseYear": 2015,
    "isPopular": true
}
}
```


6. Create a JSON structure to represent a playlist with a list of songs.

```json
{
    "playlist": ["song1", "song2", "song3"]
}
```

7. Create a JSON structure to represent a restaurant with the following attributes: name, rating, and isOpen.

```json
{
    "restaurant": {
        "name": "Pollos Kiki",
        "rating": 10,
        "isOpen": true
    }
}
```


8. Create a JSON structure to represent a student with the following attributes: name, age, grade, and a list of subjects.

```json
{
    "student": {
        "name": "Barbara Antelo",
        "age": 34,
        "grade": "A",
        "Subjects": ["math", "art", "music"]
            }
}
```


9. Create a JSON structure to represent a music album with the following attributes: title, artist, releaseYear, and a list of songs.

```json
{
    "album": {
        "title": "Pininos del corazon",
        "artist": "Barbara Antelo",
        "releaseYear": 2014,
        "songs": ["song1", "song2", "song3"]
            }
}
```



10. Create a JSON structure to represent a social media post with the following attributes: username, content, likes, and isPublic.

```json
{
    "post": {
        "username": "Bantelo21",
        "content": "picture",
        "likes": 25,
        "isPublic": true
            }
}
```

11. Create a JSON structure to represent a company with the following attributes: name, revenue, isPubliclyTraded, and a nested object for the CEO.

```json
{
    "Company": {
        "name": "microsoft",
        "revenue": 15000000,
        "isPubliclyTraded": true,
        "CEO":{
            "name": "Satya Nadella",
            "email": "snadella@hotmail.com",
            "phone": "+59171075969"
                }
              }
}
```

12. Create a JSON structure to represent a recipe with the following attributes: title, ingredients, servings, and a nested object for dietary information.

```json
{
    "recipe": {
        "title": "majadito",
        "ingredients": ["300gr. rice", "250gr. meat", "1 onion", "1 tea spon of urucu", "oil"], 
        "servings": 4,
        "dietary information": {
            "carbs": true, 
            "protein": true, 
            "fat": true,
            "fibre": false,
            "vitamins": false,
            "minerals": false,
            "water": false
                                }
             }
}
```

13. Create a JSON structure to represent a music festival with the following attributes: name, location, and a list of stages. Each stage should have attributes like name, start time, end time, and a nested object for the headlining artist.

```json
{
    "festival": {
        "name": "Pacena Fest",
        "location": "Santa Cruz de la Sierra",
        "stages":
        [
            {
            "name": "Andres Barba",
            "start time": "9.00 pm",
            "End time": "9.50 pm"
            },
            {
            "name": "Los salmones",
            "start time": "10.00 pm",
            "End time": "10.50 pm"
            },
            {
            "name": "Animal de ciudad",
            "start time": "11.00 pm",
            "End time": "12.30 pm",
            "artist": {
                "guitars": 2,
                "bajo": 1,
                "acoustic drum set": 1, 
                "sure microphone": 3 
                      }
            }
        ]
             }
}
```

14. Create a JSON structure to represent a university with the following attributes: name, location, and a list of departments. Each department should have attributes like name, head, and a list of courses offered.

```json
{
    "university": {
        "name": "UPSA",
        "location": "Santa Cruz",
        "departments":[ 
        {
            "name": "Art",
            "head": "Lic. Arteaga",
            "courses": ["photography", "digital designe", "music"]
        },
         {
            "name": "computer science",
            "head": "Ing. Aponte",
            "courses": ["operating systems", "programing", "security information"]
        }
        ]
                 }
}
```

15. Create a JSON structure to represent a store with the following attributes: name, location, and a list of departments. Each department should have attributes like name, manager, and a list of products.

```json
{
"Store": {
    "Name": "Lollypop",
    "Location": "Santa Cruz",
    "departments": 
        [
        {
        "name": "ladys",
        "manager": "Barbara Antelo",
        "list of products": ["perfum", "makeup"]
        },
        {    
        "name": "ladys",
        "manager": "Barbara Antelo",
        "list of products": ["perfum", "makeup"]
        }
        ]
    }
}

   list: [{}, {}, {}] 
   store.departments[0].lop[1]
```