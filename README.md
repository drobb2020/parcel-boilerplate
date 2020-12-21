# Vanilla JS Parcel Boilerplate

This is a boilerplate workflow for building vanilla JavaScript applications utilizing Parcel, Babel, and Sass.\
This boilerplate uses the randomuser api to display a random user in HTML.

Thanks goes to Tranversy Media. Check out the [YouTube Video](https://www.youtube.com/watch?v=8rD9amRSOQY&t=1165s) here.

## Setup and Install Dependencies

```js
npm Install
```

### Custom Scripts in package.json

```js
"dev": "rm -rf ./development && rm -rf ./cache && parcel public/index.html --out-dir development -p 3000"
```

and

```js
"build": "parcel build public/index.html --out-dir dist --public-url ./
```

## Usage

Run dev server on [localhost](http://localhost:3000)

```js
npm run dev
```

Build for production

```js
npm run build
```
