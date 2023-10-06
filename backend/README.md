# Jackie Moon Originals

## Site Description
This will be the back-end and API section for this site. JM-Originals is a passion for creativity and a curiosity for design. This site will be a showcase for  Artwork and clothing products. Items will be created and displayed from a user.  

### Tech
- Mongoose/MongoDB
- Express
- Node.js
- Javascript

## User Story
 As a user i want the ability to...
    - access a signup page 
    - create a login and generate a token
    - gain access to an api once logged in
    - interact with the products listed
    - create a shopping cart 
    - update the shopping cart
    - delete items from the shopping cart

### Current/MVP
 loading...

### Completed
 loading...

## API

### Authentication

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/signup`             | `users#signup`    |
| POST   | `/login`             | `users#login`    |
| PATCH  | `/changepass/` | `users#changepw`  |
| DELETE | `/logout/`        | `users#logout`   |

### Product

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| GET   | `/prod`             | `prod#index`    |
| GET   | `/prod/<prod_id>`    | `prod#show`    |
| POST   | `/prod`             | `prod#create`    |
| PATCH  | `/prod/<prod_id>` | `prod#update`  |
| DELETE | `/prod/<prod_id>`        | `prod#delete` |


## Entity Relationship Diagram
![ERD](https://imgur.com/a/q3uIGrJ)