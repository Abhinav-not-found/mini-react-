# Mini React Project

### Folder Structure

```text
.
├── README.md
├── tsconfig.json
├── package.json
├── index.html
├── src
│   ├── main.ts
│   └── components
│       └── button.ts
└── dist
```

## Naming Conventions

### Folder Names

Use **kebab-case** for folder names.

**Example:**

```text
hello-world
user-profile
auth-service
```

### File Names & Variables

Use **camelCase** for file names and variables.

**Examples:**

```js
authController.js;
userService.js;
getUserProfile();
```

### Class Names

Use **PascalCase** for class names.

**Example:**

```js
class KnowledgeTransfer {}
class UserService {}
```

---

## Git Workflow

### Commit Message Convention

Follow the Conventional Commits standard.

#### New Feature

```text
feat: add user authentication
feat: implement dark mode
```

#### Bug Fix

```text
fix: resolve login redirect issue
fix: handle null user response
```

### Pull Request Rules

1. Always create a Pull Request before merging code.
2. Do not push directly to the `main` branch.
3. Ensure all checks and reviews pass before merging.
4. Keep Pull Requests focused on a single feature or fix whenever possible.

## Codebase Setup

The project is configured with the following tools and development practices:

### Build & Development

- **Bundler** — Configure the project bundler and build pipeline.
  - npx tsc --init
  - npm init
- **Tailwind CSS** — Set up Tailwind CSS for styling.
- **Auto Restart Dev Server** — Automatically restart the development server when required.
  - serve, tailwindcss cli, EDBuild, browser-sync, tsc, concurrently

### GitHub

- **GitHub Setup** — Initialize the repository and configure the remote.
- **Branch Protection** — Protect the `main` branch from direct pushes and require Pull Requests for merges.
