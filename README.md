# Recipe Menu Application

## Overview
This Spring Boot application provides a RESTful API for managing recipes. It allows users to create, read, update, and delete recipes, serving as a foundation for a comprehensive recipe management system.

## Features
- CRUD operations for recipes
- RESTful API endpoints
- H2 in-memory database for development
- Built with Spring Boot 3.3.x
- Uses Gradle with Groovy for build management

## Technologies
- Java 17
- Spring Boot 3.3.x
- Spring Data JPA
- H2 Database
- Gradle (Groovy)

## Getting Started

### Prerequisites
- JDK 17 or later
- Gradle 7.x or later

### Clone the repository
```bash
git clone https://github.com/vinuran/RecipeMenu.git
cd recipemenu
```

### Build the project
```bash
./gradlew build
```

### Run the application
```bash
./gradlew bootRun
```

The application will start running at `http://localhost:8080`.

## API Endpoints

- GET /api/recipes - Get all recipes
- GET /api/recipes/{id} - Get a specific recipe
- POST /api/recipes - Create a new recipe
- PUT /api/recipes/{id} - Update an existing recipe
- DELETE /api/recipes/{id} - Delete a recipe

### Recipe JSON

```json
{
  "name": "Zhunka Bhakar (Maharashtrian Spiced Chickpea Flour with Millet Flatbread)",
  "ingredients": "For Zhunka: 2 cups besan (chickpea flour), 2 onions finely chopped, 2-3 green chilies chopped, 1 tsp cumin seeds, 1/4 tsp turmeric powder, 1 tsp red chili powder, 1 tbsp oil, Salt to taste, Chopped coriander leaves for garnish. For Bhakar: 2 cups jowar flour (sorghum flour), 1 cup warm water, 1/2 tsp salt",
  "instructions": "For Zhunka: 1. Heat oil in a pan. Add cumin seeds and let them splutter. 2. Add chopped onions and green chilies. Sauté until onions turn translucent. 3. Add turmeric powder and red chili powder. Mix well. 4. Gradually add besan, stirring continuously to avoid lumps. 5. Add salt to taste and cook on low flame for 10-12 minutes, stirring occasionally. 6. The mixture will start to leave the sides of the pan when done. Garnish with coriander leaves. For Bhakar: 1. Mix jowar flour and salt in a bowl. 2. Gradually add warm water and knead into a soft dough. 3. Divide the dough into small portions and roll each into a flat circle. 4. Cook on a hot tava (griddle) on both sides until light brown spots appear. Serve hot Zhunka with freshly made Bhakar."
}
```
### Talend API Tester Extension
![Recipe 1 Json](https://github.com/user-attachments/assets/79c6e666-bebf-407d-af06-25f4f92a748f)


## A Note from the Developer

As a learner coder, this project has been a significant step in my journey to understand development and RESTful services. I hope this repository serves as a helpful resource for others who are also learning. 

Feel free to explore the code, contribute, or reach out if you have any questions or suggestions. Learning is a collaborative process, and I believe we can all grow together by sharing knowledge and experiences.

Thank you for visiting, and happy coding! 🚀
