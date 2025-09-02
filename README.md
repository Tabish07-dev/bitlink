# bitlink
"A modern, self-hosted URL shortener built with passion using Next.js, TailwindCSS, and MongoDB. I built this to be fast, sleek, and powerful – a project I'm truly proud of."



# My Awesome Link Shortener

Hey there! 👋 Welcome to my project. This isn't just any app; it's a full-fledged **URL shortener** (like Bitly) that I built from the ground up using some of the coolest modern web technologies. I poured my heart and soul into this project to make it fast, sleek, and functional.

I'm really proud of how it turned out, and I hope you find it useful!

## 🚀 What's Inside the Tech Stack?

I built this thing to be fast and modern. Here’s a breakdown of the powerful tools I used:

*   **Next.js 15.5.2**: The core framework. I used it for its amazing React-based structure, super-fast server-side rendering, and simple page-based routing. It makes the whole app feel incredibly snappy.
*   **React 19.1.0**: For building all the interactive and dynamic components you see on the frontend. The latest React makes everything smooth and efficient.
*   **TailwindCSS v4**: For styling. I chose this because it lets me quickly design a modern and responsive UI without ever leaving my HTML/JSX. It's like having a design toolkit right at my fingertips.
*   **MongoDB (via `mongodb` driver 6.19.0)**: This is the database where all the shortened links and their original URLs are stored. It's a powerful and flexible NoSQL database that fits perfectly with a JavaScript-based app like this.
*   **Turbopack (`--turbopack` flag)**: This is the secret sauce for speed! It's a super-fast bundler and development tool that makes my code changes appear in the browser almost instantly. It makes the development experience buttery smooth.

## ⚙️ How to Get It Running on Your Machine

Love the project and want to run it yourself? It's easy! Just follow these steps:

1.  **Clone the project** to your local machine.
    ```bash
    git clone <your-repo-url>
    cd my-app
    ```

2.  **Install all the necessary dependencies.** This will grab Next.js, React, Tailwind, and everything else the project needs.
    ```bash
    npm install
    ```

3.  **Set up your environment variables.** You'll need to create a `.env.local` file in the root of the project and add your MongoDB connection string so the app can talk to the database. It should look something like this:
    ```
    MONGODB_URI="your_mongodb_connection_string_here"
    ```

4.  **Fire up the development server!**
    ```bash
    npm run dev
    ```

5.  Open your browser and go to [`http://localhost:3000`](http://localhost:3000). You should see the app live and ready to go!

### Other Useful Commands

*   `npm run build`: Creates an optimized production build of the app.
*   `npm start`: Starts the production server (run `npm run build` first).

## 🤝 Want to Contribute?

I think it's awesome that you'd want to help improve this project! Feel free to fork the repo, create a new branch for your feature, and open a Pull Request. Let's build something great together.

## ❓ Ran into a Problem?

I've tried my best to make everything work smoothly, but sometimes things happen. If you bump into any errors or something just doesn't seem right, please don't hesitate to reach out to me directly.

**Just drop me an email at [tabisoomro12@gmail.com](mailto:tabisoomro12@gmail.com).**

Please describe the issue you're facing, and I'll do my best to help you out. This project is my baby, and I'm always happy to help fix any problems.

---

Thanks for checking out my work! I hope you like it.

- Tabi
