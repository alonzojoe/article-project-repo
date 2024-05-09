# Bulletin Board with comments, voting, and authentication

![Bulletin Board with comments, voting, and authentication Project](screenshots/list.png)

## Features

- User Registration: Allows users to register and authenticate, generating a JWT Token stored in localStorage.
- Article List: Displays a list of articles in the bulletin.
- CRUD Operations on Articles: Create, Update, and Delete articles.
- Voting: Users can cast votes on articles in the bulletin board.
- Comments: Users can add comments to the articles listed in the bulletin board.
- Logout: Functionality to destroy the token and remove data from localStorage.

## Technologies and Frameworks Used

- HTML5
- CSS3
- Sweetalert
- VueJS
- Laravel

## Screenshots

![Screenshot 1](screenshots/Login.png)
_Screenshot 1: Login Page_

![Screenshot 2](screenshots/validatelogin.png)
_Screenshot 2: Login Page validation_

![Screenshot 3](screenshots/registry.png)
_Screenshot 3: User Registration_

![Screenshot 4](screenshots/validateregistry.png)
_Screenshot 4: User Registration Validation_

![Screenshot 5](screenshots/list.png)
_Screenshot 5: List of Articles Showing Their total number of votes and comments_

![Screenshot 6](screenshots/editarticle.png)
_Screenshot 6: Edit Single Article_

![Screenshot 7](screenshots/deletearticle.png)
_Screenshot 7: Delete Single Article Confirmation_

![Screenshot 8](screenshots/articledetail.png)
_Screenshot 8: Single Article Screen Details showing the comments sorted by date added descending order, other users can add new comments_

![Screenshot 9](screenshots/404page.png)
_Screenshot 9: 404 Page When url entered by the user is not registered in the vue-router_

## Repos in Development Mode

Frontend: [front_end](https://github.com/alonzojoe/article_frontend.git)

Backend: [back_end](https://github.com/alonzojoe/article_backend.git)
