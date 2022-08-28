# To Run

Run `npm start` in the project root and the app will be available on port 3000.

# State

The app's state is totally normalized, with slices for topics, quizzes, and cards.

# Routes

- `/new-topic` – form to create a new topic
- `/topics` – index of all topics
- `/topics/:topicId` – page for an individual topic
- `/new-quiz` – form to create a new quiz
- `/quizzes` – index of all quizzes
- `/quizzes/:quizId` – page for an individual quiz

# To Test

1. Create topics
2. Create quizzes
3. Visit the page for an individual quiz and flip the cards over

# Questions

Is this appropriately scoped? Does it have too many features? Too few?




At a high level, your application will be able to handle the following URL routes, each with their own functionality:

On the '/topics/new' page:

    Users can create topics

On the '/topics' page:

    Users can view all topics
    Users can click on an individual topic and be redirected to the page for that topic

On the /topics/:topicId page:

    Users can view an individual topic and all quizzes for that topic
    Users can click on a quiz associated with a topic and be redirected to that quiz’s page

On the 'quizzes/new' page:

    Users can create quizzes that are associated with topics and contain lists of flashcards
    Users can add and remove card fields in the new quiz form

On the '/quizzes' page:

    Users can view all quizzes
    Users can click on an individual quiz and be redirected to that quiz’s page

On the '/quizzes/:quizId' page:

    Users can view an individual quiz and flip cards over

