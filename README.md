# next-js-training

A collection of Next.js projects for training and learning purposes.

## How to Add Your Project

Follow these steps to contribute your project to this repository:

1. **Create a branch** using the naming convention `<your-name-project-name>`:
   ```bash
   git checkout -b your-name-project-name
   ```

2. **Create a folder** with the same name `<your-name-project-name>` at the root of the repository and add your Next.js project files inside it:
   ```bash
   mkdir your-name-project-name
   cd your-name-project-name
   npx create-next-app@latest .
   ```
   At a minimum, your project folder should contain a `package.json` and a `next.config.js` (or `next.config.mjs`).

3. **Commit and push** your changes:
   ```bash
   git add .
   git commit -m "Add your-name-project-name project"
   git push origin your-name-project-name
   ```

4. **Create a Pull Request** on GitHub from your branch into the main branch.
