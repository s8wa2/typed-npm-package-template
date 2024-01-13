# NPM package template
- 📝 Fully typed
- 🚀 TS bundled using [tsup](https://npmjs.com/package/tsup)
- ✅ Strict type checking with tsc (no-emit)
- 🛠️ Easy CI/CD with github actions
- 📦 Automatic deployment to npm
- 🏷️ Easy versioning with [changeset](https://www.npmjs.com/package/@changesets/cli)
- ⚡ Performance gains thanks to [pnpm](https://pnpm.io)
- 🌟 Inspired by [@mattpocock](https://github.com/mattpocock) and his [example repo](https://github.com/mattpocock/pkg-demo)

## Requirements
- [pnpm](https://pnpm.io/installation)
- [node](https://nodejs.org/en/download)

## Usage
1. Add a repository secret named NPM_TOKEN and set it to your npm access token
2. Check the `Allow GitHub Actions to create and approve pull requests` box in repository settings, actions/general category
3. Make some changes
4. Run `pnpm changeset` and describe your changes
5. Commit and push your changes
6. Approve the pull request github actions made
7. If actions succeed, check npm for published package