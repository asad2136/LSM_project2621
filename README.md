# E-Learning-MERN
It is an E- Learning Portal Project created with MERN Technologies

---

## Quick Start

```bash
# clone repository
Clone the repository

# Install dependencies
run npm install 
cd client && npm install


```
Create account in Mongo Atlas and create cluster. Get your MongoURI by following the instructions and add it in keys.js file which is inside the config folder. 

```
secretOrKey=ANY_SECRET
mongoURI: 'YOUR_URI'

```

To run the development server:

```bash
# the development server runs on port 3000
npm run dev
```

To run production build:

```bash
# create code bundle
npm run build

# run production server
npm run prod
```