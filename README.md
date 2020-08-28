<h2 align="center">
  ViteJS ESLint Import
</h2>

<p align="center">
  A demonstration of an <a>issue</a> raised in ViteJS.
</p>

---

#### The problem
ESLint's https://github.com/benmosher/eslint-plugin-import plugin throws errors when unknown files (in the repository filesystem) are imported into a file. This shows up in particular with `react` and `react-dom` - but I assume any of the other 'aliased modules' (like with the Preact template) will be similar.

In this repository, you will find a fresh install of Vite using the Create Vite App (React) template, as well as ESLint and the ESLint plugin.

You can run the linting step in the repository using `yarn lint`.

#### Logs

![image](https://user-images.githubusercontent.com/37649155/91564876-a582f780-e984-11ea-8878-5e759b59425b.png)
