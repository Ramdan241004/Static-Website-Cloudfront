## How to generate the static webpage

Make sure you have yarn or npm.

Create .env.local file with the following variables:

```sh
NEXT_PUBLIC_API_BASE_URL=YOUR_MODUL1_URL
NEXT_PUBLIC_API_KEY=YOUR_MODUL1_API_KEY
```

For Install Dependencies :

```sh
$ npm install
# or
$ yarn install
```

To run the application Production :

```bash
$ npm run build
# or
$ yarn build
```

To Generate Static Web :

```bash
$ npm run export
# or
$ yarn export
```

Check the out/ directory.

## To run the application locally

```bash
$ npm run dev
# or
$ yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.
