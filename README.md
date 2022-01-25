Resumeflex is a resume-sharing platform that allows users to sign up and create a profile based upon skills, projects, education, and past experiences. Users can log in to edit their profile as well as share a public URL which will serve as a shareable resume on the web and can be shared with prospective employers. Resumeflex also provides the option to download a short CV in PDF format generated using the information entered in the profile. This application was made with Ruby on Rails and the frontend was styled using Tailwind CSS then deployed on the web hosting platform Heroku.

## Tech stack for this app

- Ruby on Rails
- PostgreSQL
- Tailwindcss

## Setup

This project uses ruby '2.7.5' in case you are on a diffrent version please change things in your gemfile accordingly then hit [bundler install].

Run following command to create first user after migrating database.

```
rake db:seed
```

Email: `johndoe@example.com`
Password: `password`

URL of the live app: resumeflex.herokuapp.com
