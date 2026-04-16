# Campus Events

Campus Events is a 5-page static web project for team-based DevOps practice.

## Pages

- Home
- Destination
- Packages
- Gallery
- Contact

## Local Development

```bash
npm install
npm run start
```

## Production Build

```bash
npm run build
```

The built files are generated in `dist/`.

## Docker

```bash
docker build -t <dockerhub-username>/campus-events:v1 .
docker run -d -p 8080:80 --name tourism-app <dockerhub-username>/campus-events:v1
```

Open `http://localhost:8080` to test.
