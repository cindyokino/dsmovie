# DSMovie movies catalog - Spring React App

### * Project developed during the Spring React Week from DevSuperior.
___
#### Technologies - frontend:
- React
- Typescript
- HTML
- CSS
- Bootstrap

#### Technologies - backend:
- Java 17
- Spring (API REST)
- NodeJS

#### Technologies - database:
- PostgresSQL
- PgAdmin
- H2 (test database)

#### Technologies - cloud:
- Heroku (hosts the backend Spring Boot project)
- Netlify (hosts the frontend ReactJS project)

#### Technologies - other:
- VS Code
- STS
- Git
- Postman
___

## Steps

#### First steps
- Create ReactJS project
- Create Spring Boot project
- Create Github repository and first commit

#### Static frontend
- Clean ReactJS project
- Add Bootstrap and CSS
- Create routes - install React Router DOM
- Work on frontend - Component navbar, form, pagination, MovieCard, MovieStars, MovieScore, etc

#### Backend
- Security config
- Create entities, database seed
- Create layers
    - Create repository
    - Create DTO
    - Create service
    - Create controller
- Find movies
- Save score
- Validation on local Postgres - commit First homolog
    - Create three project profiles: test, dev, prod
    - Generate SQL script in dev profile
    - Test project on local Postgres database

#### Cloud
- Backend deployment on Heroku
    - Create app on Heroku
    - Provision Postgres database
    - Set APP_PROFILE=prod variable
    - Connect to the database via pgAdmin
    - Create database seed
- Frontend deployment on Netlify
    - Basic Deployment:
        - Base directory: frontend
        - Build command: yarn build
        - Publish directory: frontend/build

#### Integration frontend and Backend
- Three pillars of React
   - Components
   - props
   - State
- React Hooks
  - useState
  - useEffect
  - useParams
  - useNavigate

- Install Axios
    ```bash
    yarn add axios@0.24.0
    ```

- Show score
- Pagination
- Save, useNavigate