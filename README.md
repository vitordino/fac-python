# FAC Python
> Ensino de Python para comunicadores

### to run locally
1. install [`node.js`](https://nodejs.org/en/)
2. `npm run dev`

### to deploy
just push to this repo's `master` branch


## Editing Content

edit `.jade` files
* for *articles*: `/public/articles`
* for *modules*: `/public/modules`
	
	inside, the begining of the file file is mandatory metadata
	
	if you're edditing articles, i recommend using markdown by using `markdown:` and indenting the content
	
	to create a new article/module duplicate one existing folder and modify it's content

> [tip] folders' name are slug


## Contributing Guidelines

to create *articles*: name commits `[new article] article-slug`
to create *modules*: name commits `[new article] article-slug`

| Action                 | Commit/PR Name                |
|:-----------------------|:------------------------------|
| new article            | [new article] article-slug    |
| modify article         | [fix article] article-slug    |
| new module             | [new module] module-slug      |
| modify module          | [fix module] module-slug      |
| feature                | [feature] feature-name        |
| bugfix                 | [bugfix] bug-fixname          |



### tech

| Package                                                     | Use
|:------------------------------------------------------------|:-------------------------------|
| [harp](http://harpjs.com)                                   | pre-processor and local server |
| [harp-scripts](http://github.com/leonardodino/harp-scripts) | harp extension w/ browser-sync |
| [netlify](https://www.netlify.com/)                         | CI for CDN Deployment          |
