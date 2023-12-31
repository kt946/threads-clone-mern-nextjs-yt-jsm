# Threads Clone with Next.js, React, Clerk, UploadThing, Tailwind CSS, TypeScript, MongoDB

![homepage_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/24f5c057-aab6-434c-ae69-673ebd35695b, 'Homepage Screenshot')

## Description

This project is a clone of the Threads platform. It was built using a YouTube tutorial by [JavaScript Mastery](https://www.youtube.com/watch?v=O5cmLDVTgAs).

Welcome to the Full Stack Threads Clone! Developed with Next.js, React, Clerk, UploadThing, Tailwind CSS, TypeScript, and MongoDB, this project offers a social networking experience where users can sign in with their email, create posts, reply to others' posts, explore user profiles, join communities, and perform various social interactions. The application also provides features like deleting posts, a search page for discovering users and communities, and the ability to customize user profiles by editing profile images, usernames, and bios.

⭐ Note: The database may become inactive if the app is not used for a while. If this happens, please contact me and I will reactivate the database.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Links](#links)
- [License](#license)

## Installation

1. To get started, clone the repository or download the zip file.
2. Install the dependencies by running the following command in the terminal:

```
npm install
```

3. Create a .env file in the root directory and add the following environment variables:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY
NEXT_CLERK_WEBHOOK_SECRET
NEXT_PUBLIC_CLERK_SIGN_IN_URL
NEXT_PUBLIC_CLERK_SIGN_UP_URL
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL
MONGODB_URL
UPLOADTHING_SECRET
UPLOADTHING_APP_ID
```

4. Run the development server by running the following command in the terminal:

```
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the project.

⭐ Note: The project may require some additional configuration and services to run properly. Please refer to the youtube tutorial for more information.

## Features

This project includes the following features:

- User authentication using email
- Posting and sharing content with other users
- Reply functionality for engaging with posts
- User profile exploration
- Community joining and participation
- Delete posts
- Search for users and communities
- User profile customization (profile image, username, bio)

## Screenshots

![profile_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/ba23b943-9f03-4b15-89b9-7ba5835405c1, 'Profile Screenshot')

![edit_profile_form_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/b4eceda8-9070-4c31-ab94-6822c356f9f0, 'Edit Profile Screenshot')

![create_thread_form_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/e30f8ee3-776e-4244-aa52-6aed01169b6e, 'Create Thread Form Screenshot')

![thread_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/d238b219-f8d2-43ff-b876-132ee1540481, 'Thread Screenshot')

![searchpage_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/53abf3bc-2101-49f0-8601-90e69b2aac25, 'Searchpage Screenshot')

![communities_screenshot](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm/assets/103476893/6d639b6e-6c4f-45f7-948a-061fe2c75466, 'Communities Screenshot')

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Clerk](https://clerk.dev/)
- [UploadThing](https://uploadthing.com/)
- [MongoDB](https://www.mongodb.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vercel](https://vercel.com/)

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Links

- [Link to deployed application](https://threads-clone-mern-nextjs-yt-jsm.vercel.app/)

- [Link to GitHub repository](https://github.com/kt946/threads-clone-mern-nextjs-yt-jsm)

- [Link to original GitHub repository by JavaScript Mastery](https://github.com/adrianhajdin/threads)

- [Link to youtube tutorial by JavaScript Mastery](https://www.youtube.com/watch?v=O5cmLDVTgAs)

## License

This project is licensed under the MIT License.
