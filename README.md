# Next.js 16 Starter Template

A powerful starter template for Next.js 16 projects, featuring:

- **Better Auth**: Seamless and secure authentication.
- **Drizzle ORM**: Elegant and type-safe database management.
- **Supabase**: Robust backend services for your application.

## Features

- Pre-configured authentication with Better Auth.
- Integrated Drizzle ORM for easy database interactions.
- Ready-to-use Supabase setup.
- Scalable and modern tech stack.
- Self Hostable

## Getting Started

Follow these steps to set up the project:

### 1\. Clone the Repository

```
git clone https://github.com/JabirDev/nextjs-better-auth.git
cd nextjs-better-auth
```

### 2\. Install Dependencies

Make sure you have Node.js installed, then run:

```
bun install
```

### 3\. Configure Environment Variables

Copy the env.example file to create your .env file:

```
cp env.example .env
```

Edit the `.env` file with your project's specific configurations:

- Add your Supabase keys and URLs.
- Configure any required authentication secrets.

### 4\. Setup Drizzle ORM

Generate your Drizzle schema and push into your database:

```
bun db:push
```

### 5\. Start the Development Server

Run the development server:

```
bun dev
```

Your application will be available at [http://localhost:3000](http://localhost:3000).

## Contributing

Contributions are welcome! Feel free to:

- Open issues for bugs or feature requests.
- Submit pull requests to improve the project.

### License

This project is licensed under the MIT License.
