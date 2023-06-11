# Memory cards

### About project

"Memory cards" is an application for learning English words.

The app allows to:

- **sign in** or **sign up** in an app;
- **choose** a theme for learning words;
- **mark** words as learned;
- **add** new words;

Start page

<img src="https://github.com/BentonFraizer/memory-cards/blob/main/.github/workflows/start_page.png" width="769" />

Choose theme page

<img src="https://github.com/BentonFraizer/memory-cards/blob/main/.github/workflows/choose_theme_page.png1" width="769" />

Learning page

<img src="https://github.com/BentonFraizer/memory-cards/blob/main/.github/workflows/learning_page.png" width="769" />

Add new word page

<img src="https://github.com/BentonFraizer/memory-cards/blob/main/.github/workflows/add_word_page.png" width="769" />

### Stack

- React SSR
- JavaScript (ES6)
- Express
- PostgreSQL
- Sequelize

### ⚙️ How To Run Locally

1. download and install PostgreSQL from [official website](https://www.postgresql.org/download/)

2. clone repo with:

```
git clone git@github.com:BentonFraizer/DA.KOREAN.git
```

3. go into the progect folder with:

```
cd memory-cards/
```

4. install all dependencies with:

```
npm install
```

5.1 copy file .env.example, rename to .env

5.2 change DATABASE_URL. For example:

from

```
DATABASE_URL = postgres://login:password@ip:port/bd_name
```

to

```
DATABASE_URL = postgres://postgres:postgres@localhost:5432/memory_cards
```

6. create a database with:

```
npm run dbr
```

7. run in the **dev** mode with:

```
npm run dev
```
