
## Backend Installation
### Clone the backend for local use
```
git clone https://github.com/wilson-vulse/vulse_backend
```
<br>

### Install necessary packages for the backend
```
npm install
```

<br>

### Create a .env file in the backend root folder
```
mkdir .env
```

<br>

### Config environment variable in .env
```
HOST=0.0.0.0
PORT=1337
APP_KEYS=
API_TOKEN_SALT=
ADMIN_JWT_SECRET=
TRANSFER_TOKEN_SALT=
# Database
DATABASE_CLIENT=postgres
DATABASE_HOST=
DATABASE_PORT=5432
DATABASE_NAME=postgres
DATABASE_USERNAME=postgres
DATABASE_PASSWORD=
DATABASE_SSL=true
JWT_SECRET=
```

<br>


### Run the backend
```
npm run develop 
```
or

```
sudo run develop
```

<br>