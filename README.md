Roadmap for See-V
=================

- API calls:



- **[<code>GET</code> profile](http://see-v.herokuapp.com/api/v1/profile.json)**
- **[<code>GET</code> educations](http://see-v.herokuapp.com/api/v1/educations.json)**
- **[<code>GET</code> educations/:id](http://see-v.herokuapp.com/api/v1/educations/:id.json)**
- **[<code>GET</code> skills](http://see-v.herokuapp.com/api/v1/skills.json)**
- **[<code>GET</code> cv_as_pdf/:id](http://see-v.herokuapp.com/api/v1/cv_pdf/:id.json)**

- **[<code>POST</code> profile](http://see-v.herokuapp.com/api/v1/profile)**
- **[<code>POST</code> educations](http://see-v.herokuapp.com/api/v1/educations)**
- **[<code>POST</code> skills](http://see-v.herokuapp.com/api/v1/skills)**

# App features

- User should be able to create/populate his profile information.
- User should be able to populate his education information (education -> has_one -> school).
- User can insert his skills (each skills has a corresponding level.)
- User can download his CV as PDF.

# Attribtues

## Profile attributes

- first_name
- last_name
- email
- headline
- description
- phone
- address
- location

## Education attributes

- school name
- start_date
- end_date
- degree
- field_of_study

## Skill attributes

- skill_name
- level