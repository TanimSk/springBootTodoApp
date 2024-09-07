# CSERU Assignment

App was initialized via:

```
spring init --java-version=22 \
   --build=gradle \
   --packaging=jar \
   --type=gradle-project \
   --artifact-id=todolist \
   --group-id=com.example \
   --dependencies=web,thymeleaf,databind \
   --extract TodoWebApp \
   --name=TodoList
```

# API endpoints

**GET :** `/` `/todos` `/todos/{id}`

**POST :** `/todos`

**DELETE :** `/todos/{id}`

**PUT :** `/todos/{id}`

# To install this project

```
git clone https:
cd TodoWebApp
./gradlew clean build
./gradlew bootRun
```

I am rendering home.html page with thymeleaf, all the above requests can be made with that html page (using fetch with JS to perform requests and DOM operations)

I have also added postman exported json collection, [click here](https://google.com/) to download.
