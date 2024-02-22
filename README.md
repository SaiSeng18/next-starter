## Project Title

This project is a web application built with Next.js, a popular React framework, and TypeScript, a statically typed superset of JavaScript that adds optional types.

## Features

-   **NextAuth:**  This project uses NextAuth for authentication. The configuration can be found in  `app/api/auth/[...nextauth]/route.ts`.
-   **Shadcn:**  This project uses Shadcn, a library of beautifully designed, accessible, and customizable components. You can find the usage of these components throughout the project.
-   **Prisma:**  Prisma is used as the ORM for this project. The Prisma schema can be found in  `prisma/schema.prisma`  and the MongoDB schema in  `prisma/mongodb_schema.prisma`. The Prisma client is used in  `lib/prismadb.ts`.
-   **Zustand:**  Zustand is used for state management in this project. The specific usage of Zustand is not provided in the current workspace information.
-   **Prettier:**  This project uses Prettier for code formatting. The configuration can be found in  `prettier.config.js`.

## Getting Started

To get started with this project, clone the repository and install the dependencies:

Bash

```
git clone https://github.com/SaiSeng18/next-starter.git
cd next-starter
npm install
```


Then, you can start the development server:

Bash

```
npm run dev
```


Open `http://localhost:3000` with your browser to see the result.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.