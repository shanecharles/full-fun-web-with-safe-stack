- title : Full Fun Web with SAFE Stack
- description : Introduction to the SAFE web stack.
- author : Shane Charles
- theme : night
- transition : default

***

### Full Fun Web with SAFE Stack

***

<!-- .slide: class="two-floating-elements" -->
### About me

<div class="two-floating-elements">
<img src="images/mvp_logo_vertical.png" alt="mvp" style="height:145px;border:0;margin: auto;"/>
    <ul>
     <li>Shane Charles</li>
<li>White Light Computing, Inc.</li>
<li>Functional programming enthusiast</li>
<li>Board member for Winnipeg .Net UG</li>
</ul>
</div>




    type ContactType = | Twitter | Blog | GitHub

    let getContactInfo = function
      | Twitter -> "@dead_stroke"
      | Blog    -> "https://geekeh.com"
      | GitHub  -> "shanecharles"

***

### You will see

- What is SAFE Stack
- Setup
- Fable + Elmish
- Saturn
- Azure
- Summary

***

### You will not see

- Aesthetics
- UX
- Security

***

### SAFE

- Server
- Azure
- Fable
- Elmish

---

### Server?

- Suave
- Azure
- Fable
- Elmish

---

### + Giraffe

- `choose [suave; giraffe]`
- Azure
- Fable
- Elmish

---
### + Saturn

- `choose [suave; giraffe; saturn]`
- Azure
- Fable
- Elmish

---

### No Longer Suave

- `choose [giraffe; saturn]`
- Azure
- Fable
- Elmish

---

### SAFE Default

- Saturn
- Azure
- Fable
- Elmish

***
### Setup Requirements

- dotnet core (2.+)
- `yarn` or `node`
- `fake` command line tool

---
### Installing Fake

> dotnet tool install fake-cli -g

- Linux/OSx: `~/.dotnet/tools`
- Windows: `%USERPROFILE%\.dotnet\tools`

---

### Installing and Running SAFE 

- Command Line
 - dotnet new -i SAFE.Template
 - dotnet new SAFE
 - fake build --target run

--- 
### Patience for first run

![bored](images/bored.gif)

***

### Fable + Elmish 

> Fable is a F# to javascript compiler.
> Elmish is a frontend paradigm based on the Elm Architecture.

---
### Elm Architecture

- Model
- View
- Update

---
### Flow


---
### Demos
***
### Saturn

- Standalone Server
- Abstraction on Giraffe
- Inspired by Phoenix (Elixir)
- MVC pattern

---
### Opinionated 

- Convention over configuration
 - Dapper
 - Simple.Migrations
- Scaffolding scripts
 - `dotnet saturn` command line tool

---
### Computation Expressions

- pipeline
- controller
- router
 - formerly `scope`

---
### Router functions

- pipe_through
- get, getf
- post
- forward

***

### Extra Resources

- F# for Fun and Profit 
 - https://fsharpforfunandprofit.com/posts/property-based-testing/

***

### Thank You


    type ContactType = | Twitter | Blog | GitHub

    let getContactInfo = function
      | Twitter -> "@dead_stroke"
      | Blog    -> "https://geekeh.com"
      | GitHub  -> "shanecharles"

***
