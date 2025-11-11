# Contributing to Better-T-Stack Template

Thank you for your interest in contributing! This guide will help you get started.

## Development Setup

1. **Fork and clone the repository**

   ```bash
   git clone https://github.com/yourusername/your-fork.git
   cd your-fork
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Set up your environment**

   - Copy `.env.example` to `.env` in both `apps/server` and `apps/web`
   - Update the values with your local development credentials

4. **Set up the database**

   ```bash
   pnpm run db:push
   ```

5. **Start the development server**
   ```bash
   pnpm run dev
   ```

## Making Changes

### Code Style

- We use TypeScript across the entire stack
- Follow the existing code style and conventions
- Use meaningful variable and function names
- Add comments for complex logic
- Avoid type assertions (`as any`) when possible

### Commit Messages

Use clear, descriptive commit messages:

- `feat: add new feature`
- `fix: resolve bug in...`
- `docs: update README`
- `refactor: improve code structure`
- `chore: update dependencies`

### Pull Request Process

1. Create a new branch for your feature/fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and commit them with clear messages

3. Push to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

4. Open a Pull Request with:

   - Clear title and description
   - Reference any related issues
   - Screenshots/recordings for UI changes
   - List of changes made

5. Wait for review and address any feedback

## Areas for Contribution

### Features

- New authentication providers
- Additional UI components
- Database schema improvements
- API endpoints and procedures
- Developer tooling

### Documentation

- Tutorial improvements
- API documentation
- Deployment guides
- Example implementations

### Bug Fixes

- Report bugs via GitHub Issues
- Include steps to reproduce
- Provide system information
- Submit PRs with fixes

## Testing

Before submitting your PR:

1. Ensure the project builds successfully:

   ```bash
   pnpm run build
   ```

2. Check for TypeScript errors:

   ```bash
   pnpm run check-types
   ```

3. Test your changes thoroughly in development mode

## Questions?

Feel free to open an issue for:

- Questions about the codebase
- Feature proposals
- Bug reports
- General discussions

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Keep discussions focused and professional

Thank you for contributing! 🎉
