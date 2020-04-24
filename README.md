#### Gatsby-Blog


---

**Install Instructions**

**1.** Clone the repository

```bash
git clone https://github.com/mheerspink75/Gatsby-Blog.git
```

**2.** Install the NPM packages

```bash
cd Gatsby-Blog && npm install
```

**3.** Run the DEV server
```bash
gatsby develop
```

*You can now view gatsby-blog in the browser.*  

[http://localhost:8000/](http://localhost:8000/)


*View GraphiQL, an in-browser IDE, to explore your site's data and schema*  

[http://localhost:8000/___graphql](http://localhost:8000/___graphql)


**4.** Create the production build

```bash
gatsby build
```

**5.** Serve the production build

```bash
gatsby serve
```

info gatsby serve running at: http://localhost:9000/

---

**Deploy to [Surge](https://surge.sh/)**

```bash
surge login

gatsby build

ls public

surge public/
```

Success! - Published to [amuck-meat.surge.sh](http://amuck-meat.surge.sh/)

***or***

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#snapshot/93aa9331-93e4-442f-8272-0617593cd63f)

[![Edit gatsby-blog](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/beautiful-hodgkin-njik6?fontsize=14&hidenavigation=1&theme=dark)
