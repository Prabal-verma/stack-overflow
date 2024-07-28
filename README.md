# StackOverflow Clone

This project is a Stack Overflow clone built with Next.js and TypeScript for the frontend, and Appwrite for the backend services. The goal of this project is to create a robust platform where users can ask questions, provide answers, and engage with the community.

## Features

- User Authentication (Signup, Login, Logout)
- Post Questions
- Answer Questions
- Vote on Questions and Answers
- Comment on Questions and Answers
- Search Functionality
- User Profiles

## Tech Stack

- **Frontend**: Next.js, TypeScript
- **Backend**: Appwrite
- **Styling**: CSS Modules / Styled Components
- **State Management**: Context API / Redux
- **Database**: Appwrite Database

## Getting Started

### Prerequisites

- Node.js (>=14.x)
- npm (>=6.x) or yarn (>=1.x)
- Appwrite account

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Prabal-verma/stack-overflow.git
cd stack-overflow
```

2. **Install dependencies**

```bash
# using npm
npm install

# or using yarn
yarn install
```

3. **Set up Appwrite**

- Sign up for an account at [Appwrite](https://appwrite.io/).
- Create a new project.
- Create a new database and collection for questions, answers, and users.
- Create the necessary attributes for each collection.
- Set up authentication.

4. **Create a `.env.local` file in the root directory**

```env
NEXT_PUBLIC_APPWRITE_HOST_URL=yourUrl
NEXT_PUBLIC_APPWRITE_PROJECT_ID=yourProjectid
APPWRITE_API_KEY=yourApiKey
```

5. **Run the development server**

```bash
# using npm
npm run dev

# or using yarn
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `pages/`: Contains the Next.js pages.
- `components/`: Contains the React components.
- `styles/`: Contains the CSS Modules / Styled Components.
- `contexts/`: Contains the Context API providers and hooks.
- `utils/`: Contains utility functions.
- `services/`: Contains the Appwrite service functions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Prabal Verma - [your-email@example.com](mailto:dev@prabalverma.me)

Project Link: [https://github.com/Prabal-verma/stack-overflow.git](https://github.com/Prabal-verma/stack-overflow.git)

---
