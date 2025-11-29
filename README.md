# Multi User Journal



## Description

Multi User Journal is a journaling web application that allows multiple users to create anonymous posts and view posts from other users. The application is built using Next.js with JavaScript for the frontend and Prisma ORM for database interactions. It supports multiple types of devices and screens.
The application has been deployed on Render and uses a Postgresql database.

---

## Live site
The deployed app can be found here. Since this was developed as part of an assignment that must remain in a private repository, the code is not publicly accessible. For technical recruiters or hiring managers interested, please submit a request @ keshia@keshiacoriolan.io and I'll be happy to grant you temporary access.

[Multi user journal app](https://userjournal-thx-kxd2.onrender.com/)

## Features

- User can post journal entries anonymously or with their name and/or email
- Anonymous users are considered guests and identified using UUIDs and cookies
- A user can view all the posts from a user by clicking on their name (if the user was not anonymous i.e a name was provided)
- View all the journal entries in a paginated format
- Users can search and filter for journal entries by text
- Users can navigate post results from page to page using the pagination

---

## Usage
View of the journal
<img width="1942" height="1137" alt="image" src="https://github.com/user-attachments/assets/004dcd5c-08e3-49a2-ad53-6ec71971891a" />

Pagination
<img width="1484" height="406" alt="image" src="https://github.com/user-attachments/assets/9e841dc0-2fa0-4fbc-961b-f07da1f50c56" />

Filtered Posts
<img width="1910" height="1280" alt="image" src="https://github.com/user-attachments/assets/dd4b77a4-60ce-42a3-a3e5-5d782fcd40fc" />

Viewing all posts of a user
<img width="2834" height="1296" alt="image" src="https://github.com/user-attachments/assets/397d7409-8ecd-49ea-9964-9793aef1a4f3" />

Adding a post
<img width="1980" height="1166" alt="image" src="https://github.com/user-attachments/assets/c5a3f47d-02fc-4bb2-9243-ca74ed2ac2f6" />



## Important Dependencies

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Prisma ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [dotenv](https://www.npmjs.com/package/dotenv)
## License

This project is licensed under the [MIT License](LICENSE).

## TODO:

- Add a more comprehensive tests (unit, integration, end-to-end)

