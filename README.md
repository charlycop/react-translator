

# To Use
`npm run dev` : becareful, the downloading of models works only if you app is deployed !

# To build
`npm run build`
Then, you take the `index.html` and the `assets` folder found in `dist` folder, and you upload to huggingface repo.

# about the models
See here how to use another remote path (by default it's hugging face), you can see in `workers.js`, I made an example, and I tested it how to use the `.env` variables.

**If remote, the models should be under https AND the model shoud be in `resolve/main` subfolders, for example if your model is declared to be under `https://www.serenitheparis.com/aimodels/onnx-opus-mt-en-eo`, it should actually be in `https://www.serenitheparis.com/aimodels/onnx-opus-mt-en-eo/resolve/main`**


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
