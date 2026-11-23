# Message Me – Real-Time Chat Application

A Ruby on Rails chat application with a chatroom landing page, login/logout routes, message creation and an Action Cable WebSocket endpoint for real-time communication.

## Features represented in the application

- Chatroom page
- Login and logout routes
- Message submission
- Action Cable mounted at `/cable` for WebSocket communication

## Technology

- Ruby 2.7.7
- Ruby on Rails 5.2
- SQLite
- Action Cable
- Semantic UI
- jQuery
- BCrypt
- Puma

## Run locally

1. Install Ruby 2.7.7 and Bundler.
2. Clone the repository and enter the project directory.
3. Install dependencies: `bundle install`.
4. Prepare the database: `bin/rails db:create db:migrate`.
5. Start Rails: `bin/rails server`.

Open the local Rails URL shown in the terminal. Real-time messaging uses the Action Cable endpoint configured by the application.

## Learning focus

Rails MVC, WebSockets, Action Cable, real-time messaging concepts, session-based authentication routes and front-end integration with Semantic UI.

See the source code for the current message-broadcasting and connection implementation.
