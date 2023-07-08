# XML Exercises

Exercise 1
Create an XML file with a root element called "employees" and add two employee elements within it. Each employee element should have attributes for "id" and "name".

```xml
<employees>
    <employee id="1" name="Barbara"/>
    <employee id="2" name="Rafael"/>
</employees>
```

Exercise 2:
Extend Exercise 1 by adding child elements within each employee element to represent their information such as "age", "department", and "position".

```xml
<employees>
    <employee id="1" name="Barbara">
        <age>30</age>
        <department>female</department>
        <position>manager</position>
    </employee>
    <employee id="2" name="Rafael"/>
        <age>40</age>
        <department>male</department>
        <position>asistant</position>
    </employee>
</employees>
```

Exercise 3:
Create an XML file to represent a book catalog. Include multiple book elements, each with attributes for "title", "author", and "year". Add additional child elements to represent the book's "genre" and "price".

```xml
<catalog>
    <book title="El duende del siglo XXI" author="Barbara Antelo" year="2011">
        <genre>aventure</genre>
        <price>Bs 50</price>
    </book>
    <book title="Sky Kids, aprendiendo a volar" author="Barbara Antelo" year="2013">
        <genre>Cience ficcion</genre>
        <price>Bs 50</price>
    </book>
   
        
   
</catalog>
```

Exercise 4:
Create an XML file to represent a simple contact list. Include multiple contact elements, each with child elements for "name", "email", and "phone". Add attributes to the contact elements for "id" and "category".

```xml
<contact_list>
    <contact id="1" category="Family">
        <name>Barbara Antelo</name>
        <email>barbaraantelom@gmail.com</email>
        <phone>+59171075969</phone>
    </contact>
    <contact id="2" category="Friend">
        <name>Isai</name>
        <email>isai@gmail.com</email>
        <phone>+591595954</phone>
    </contact>
</contact_list>
```

Exercise 5:
Create an XML file to represent a basic shopping list. Include a root element called "shoppingList" and add multiple item elements within it. Each item element should have a child element for "name" and an attribute for "quantity".

```xml
<shoppingList>
    <item id="1">
        <name>Naranja</name>
        <quantity>5</quantity>
    </item>
     <item id="2">
        <name>banana</name>
        <quantity>6</quantity>
    </item>
     <item id="3">
        <name>apple</name>
        <quantity>3</quantity>
    </item>
</shoppingList>
```

Exercise 6:
Create an XML file to represent a student roster. Include multiple student elements, each with child elements for "name" and "grade". Add attributes to the student elements for "id" and "class".

```xml
<list>
    <student id=0001 class=technicalwriting>
        <name>Barbara Antelo</name>
        <grade>1th</grade>
    </student>
    <student id=0002 class=art>
        <name>Roberto Antelo</name>
        <grade>4th</grade>
    </student>
    <student id=0003 class=history>
        <name>Rafael Terrazas</name>
        <grade>2nd</grade>
    </student>
</list>
```

Exercise 7:
Create an XML file to represent a recipe. Include a root element called "recipe" and add child elements for "title", "ingredients", and "instructions". The "ingredients" element should contain child elements for each ingredient.

```xml
<recipe>
    <title>majadito</title>
    <ingredients>
        <ingredient name=rice quantity=300gr>
        <ingredient name=meat quantity= 250gr>
        <ingredient name=onion quantity= 1>
    </ingredients>
    <intructions>
    <!-- cook the onion and meat, then put the rice, toast it, add some wather, let ir dry and serv. -->
    </intructions>
</recipe>
```

Exercise 8:
Create an XML file to represent a playlist. Include multiple song elements, each with child elements for "title", "artist", and "duration". Add attributes to the song elements for "id" and "genre".

```xml
<playlist>
    <song id=1 genre=pop>
        <title>espacio sideral</title>
        <artist>jessy_y_joy</artist>
        <duration>3minutes_42seconds</duration>
    </song>
    <song id=2 genre=rock>
        <title>we_will_rock_you</title>
        <artist>Queen</artist>
        <duration>2minutes_15seconds</duration>
    </song>
    <song id=3 genre=regae>
        <title>Rude</title>
        <artist>Magic!</artist>
        <duration>3minutes_23seconds</duration>
    </song>
</playlist>
```

Exercise 9:
Create an XML file to represent a simple survey. Include a root element called "survey" and add child elements for "question" and "options". The "options" element should contain child elements for each answer option.

```xml
<survery>
    <question>
    <!--You prefer coffe with...-->
    </question>
    <option>
        <answer>milk</answer>
        <answer>black</answer>
        <answer>sugar</answer>
    </option>
</survery>
```

Exercise 10:
Create an XML file to represent a basic configuration settings file. Include a root element called "settings" and add child elements for different configuration parameters such as "username", "password", and "server".


```xml
<settings>
    <username>Bantelo21</username>
    <password>fghd1234</password>
    <server>Web_server</server>
</settings>
```

Certainly! Here are five advanced exercises to practice structuring XML files:


Exercise 11:
Create an XML file to represent a blog post. Include elements for the post's "title", "author", "content", "tags", and "comments". The "tags" element should contain child elements for each tag, and the "comments" element should have child elements representing individual comments with attributes for "username" and "timestamp".

```xml
<post>
    <title></title>
    <author></author>
    <content></content>
    <tags>
        <tag>
            <name>Barbara antelo</name>
        </tag>
    </tags>
    <comments>
        <comment username="Bantelo" timestamp="10pm">Loved it!</comment>
    </comments>
    
</post>
```

Exercise 12:
Create an XML file to represent a product catalog. Include elements for "categories", "products", and "reviews". The "categories" element should contain child elements representing different product categories. The "products" element should have child elements representing individual products with attributes for "id" and "name". The "reviews" element should contain child elements representing customer reviews with attributes for "productId", "rating", and "comment".

```xml
<catalog>
    <categories>
        <categorie>perfum</categorie>
        <categorie>makeup</categorie>
    </categories>
    <products>
        <product id="perfume001" name="212_Carolina_Herrera"/>
        <product id="makeup002" name="Eyeliner_black"/>
    </products>
    <reviews>
        <review productid="perfume001" rating="5" comment=""/>
    </reviews>

</catalog>
```

Exercise 13:
Create an XML file to represent a geographical map. Include elements for "map", "locations", and "routes". The "map" element should contain attributes for "name" and "scale". The "locations" element should have child elements representing different locations with attributes for "id", "name", "latitude", and "longitude". The "routes" element should contain child elements representing different routes with child elements for "startLocation", "endLocation", and "distance".

```xml

```

Exercise 14:
Create an XML file to represent a music library. Include elements for "library", "artists", "albums", and "songs". The "artists" element should have child elements representing individual artists. The "albums" element should contain child elements representing albums with attributes for "id", "title", and "artistId". The "songs" element should have child elements representing individual songs with attributes for "id", "title", "albumId", and "duration".

```xml

```

Exercise 15:
Create an XML file to represent a sports team roster. Include elements for "team", "players", "positions", and "statistics". The "team" element should contain attributes for "name" and "location". The "players" element should have child elements representing individual players with attributes for "id", "name", and "positionId". The "positions" element should contain child elements representing different positions with attributes for "id" and "name". The "statistics" element should have child elements representing individual player statistics with attributes for "playerId", "matchesPlayed", "goalsScored", and "assists".

```xml

```
