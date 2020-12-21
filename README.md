# GSOC-assist

Aim of this project is to reduce the efforts of GSOC aspirants and help them to find organisations that interests them. 

### App flow
(different components of the app)

App :-
  - Home Page
    - Navbar
      - logo ...maybe
      - GSOC-assist (name of the website... dummy)
      - Login, Signup (if not auth) and Logout, Username (if auth)
    - apply filters and search
      - tech stack
      - year
      - rating
    - toggle for orgs and projects view
    - For Orgs
      - List of orgs(According to the selected year/technologies)
        - logo
        - name
        - list of years
        - number of times
      - Add orgs to preference list
      - trending orgs
        - name
        - stars
      - recommended orgs
        - name
        - stars
    - For projects
      - List of projects(According to the selected year/technologies)
      - Add project to preference list
      - trending projects
        - name
        - stars
      - recommended projects
        - name
        - stars
  - login/signup :
    - appbar
    - login/signup form 
        - name
        - github handle
        - password / confirm password etc
        - forgot password etc.
    - oAuth from github
    - footer
- profile page 
    - Navbar
    - name
    - photo
    - Email /  github profile link
    - tech stacks
    - reset password
    - footer
 - wishlist page 
   - Orgs preference list
   - Projects preference list
- org details :
    - Navbar
    - Orgs desc
    - Add orgs to preference list
    - Link to orgs page on GSOC site
    - Projects under orgs(Specified year only)
    - Options to see past participations
    - Add projects to preference list
    - footer
- project details :
    - Navbar
    - Project Desc
    - Add project to preference list
    - Link to projects
    - footer
