# FAC Python
> Ensino de Python para comunicadores

### to run locally
1. install [`node.js`](https://nodejs.org/en/)
2. `npm i`
3. `npm run dev`

### to deploy

just push to this repo's `master` branch


## Editing Content

edit `.jade` files

* for *modules*: `/public/course/0x-moduleName/index.jade`
* for *articles*: `/public/course/0x-moduleName/0x-articleName/index.jade`
	
	inside them, the begining of the file file is mandatory metadata
	
	if you're edditing articles, i recommend using markdown by using `markdown:` and indenting the content
	
	to create a new article/module duplicate one existing folder and modify it's content

> [tip] folders' name are slug


## Contributing Guidelines

| Action                 | Commit/PR Name                      |
|:-----------------------|:------------------------------------|
| new article            | [new article] article-slug          |
| modify article         | [fix article] article-slug          |
| new module             | [new module] module-slug            |
| modify module          | [fix module] module-slug            |
| feature                | :sparkles: [feature] feature-name   |
| bugfix                 | :bug: [bugfix] bug-fixname          |



### tech

| Package                                                     | Use                            |
|:------------------------------------------------------------|:-------------------------------|
| [harp](http://harpjs.com)                                   | pre-processor and local server |
| [harp-scripts](http://github.com/leonardodino/harp-scripts) | harp extension w/ browser-sync |
| [netlify](https://www.netlify.com/)                         | CI for CDN Deployment          |


### Dependencies
| Dependency | Minimum Version |
| --- | --- |
| `node` | `v6` |
| `bash` | `v3`* |

`*` Built-in on MacOS & Modern Linux.
