# VeraDemo.NET - Blab-a-Gag

## About

Blab-a-Gag is a fairly simple forum type application which allows:
* Users can post a one-liner joke.
* Users can follow the jokes of other users or not (listen or ignore).
* Users can comment on other users messages (heckle).

### URLs

* `/feed` shows the jokes/heckles that are relevant to the current user.
* `/blabbers` shows a list of all other users and allows the current user to listen or ignore.
* `/profile` allows the current user to modify their profile.
* `/login` allows you to log in to your account
* `/register` allows you to create a new user account
* `/tools` shows a tools page that shows a fortune or lets you ping a host.
 
## Run

If you don't already have Docker this is a prerequisite.

```
docker run --rm -it -p 127.0.0.1:8080:8080 antfie/verademo-dotnet
```

Navigate to: http://127.0.0.1:8080

## Exploitation Demos

See the `docs` folder.

## Technologies Used

* ASP.NET Core MVC on .NET Core 3.1
* Sql Server 2017 Express

## Building

docker build .