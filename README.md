# Saikou

This is a special project on Azobu Mentorship program.

---

## Ideas

This project is decided to be the creation of **social media for pop culture fans and communities**.
It will be the place for fans to share their interests each other.
It can be in the form of private chat, public discussion, reviews, recommendations, etc.

### Research

Research to reverse engineer every essential elements for a social community site.

Join these communities to identify the pros and cons from each of them.

- [MyAnimelist](https://myanimelist.net)
- [LINE OpenChat](https://line.me/ti/g2/d1YUYNUZ_tJDH0ywSe3VyQ)
- [Anime Planet](https://anime-planet.com)
- [YourStack](https://yourstack.com)
- [Anilist](https://anilist.co/)

Database:

- [Jikan](https://jikan.moe)
  - [Documentation](https://jikan.docs.apiary.io)

Misc:

- [Jurnal Otaku](http://jurnalotaku.com)
- [KAORI Nusantara](https://www.kaorinusantara.or.id)

References:

- [viz](https://www.viz.com/)
- [Anime Planet](https://anime-planet.com)
- [Anichart](https://anichart.net)
- [Anilist](https://anilist.co/)

## Features

### Features List

- User can register, login, and logout.
- User can have roles such as Regular or Admin.
- Admin credentials will be created once.
- Admin can add new anime/manga.
- Admin can edit anime/manga details.
- Admin can delete one or more anime/manga details.
- User can see available anime/manga collection.
- User can get generated profile picture and username.
- User can read the details about one anime/manga.
- User can favorite and unfavorite one anime/manga.
- User can see other user's favorites of anime/manga.
- User can interact with other user through user profile and anime review.
- User can review a certain anime/manga.
- User can search an anime or manga.
- User can create anime recommendation list.

### Not Features List

- User cannot watch anime episodes.
- User cannot read manga chapters.
- Anime cannot separated into multiple seasons. So only one franchise being shown or reviewed.

### Future Features List

- User have to confirm their email after registration.
- User can reset their password with reset link via email.
- User can show their amount of likes based on their published reviews and lists.
- User can see the list of characters or voice actors in the anime/manga.
- User can follow other users.

---

## UI/UX Design

### Mockup/Prototype

Figma: https://www.figma.com/file/j4lco2gQyoGtrY47DnzoTl/Saigo-no-Azobu

### Pages

| Page                                 | Component       |
| ------------------------------------ | --------------- |
| `/`                                  | Home            |
| `/about`                             | About           |
| `/anime`                             | AnimeCollection |
| `/anime/:id/:slug`                   | Anime           |
| `/anime/:id/:slug/reviews`           | AnimeReviews    |
| `/manga`                             | MangaCollection |
| `/manga/:id/:slug`                   | Manga           |
| `/manga/:id/:slug/reviews`           | MangaReviews    |
| `/search`                            | Search          |
| `/register`                          | Register        |
| `/login`                             | Login           |
| `/logout`                            | Logout          |
| `/users/:id/:username`               | UserProfile     |
| `/users/:id/:username/reviews`       | UserReviews     |
| `/users/:id/:username/reviews/:slug` | UserReview      |
| `/users/:id/:username/lists`         | UserLists       |
| `/users/:id/:username/lists/create`  | UserListCreate  |
| `/users/:id/:username/lists/:slug`   | UserList        |
