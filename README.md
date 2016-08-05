# Visual Studio Code snippets
This is a set of Javascript / Typescript [VSCode](https://code.visualstudio.com) snippets I use every day.

It targets AngularJS / NodeJS and Express. The snippets for NodeJS / Express are in javascript. The AngularJS snippets are in TypeScript.

## Typescript Snippets

|shortcut |area    |function
|-------- |----    |--------
|ed       |generic |`export default`
|cl       |generic |Log to the console.
|clvar    |generic |Log a variable to the console.
|cltest   |generic |Log a test string to the console.
|pfvoid   |generic |Public void method with documentation.
|pstr     |generic |Public string.
|pristr   |generic |Private string.
|desc     |Jasmine |describe a test.
|itt      |Jasmine |perform a test.
|actrl    |Angular |Generic AngularJS controller.
|adctrl   |Angular |Generic AngularJS directive / component controller.
|adir     |Angular |Generic AngularJS directive.
|acomp    |Angular |Generic AngularJS component.
|aserv    |Angular |Generic AngularJS service class.
|mdl      |Angular |Generic model.
|vld      |Angular |Generic validator.
|asyncm   |Angular |Generic Async method returning a promise.
|qdep     |Angular |Generic $q dependency.
|resdep   |Angular |Generic resourceService dependency.

## Javascript snippets
|shortcut |area    |function
|-------- |----    |--------
|gtask    |gulp    |Generic Gulp task.
|gwatch   |gulp    |Generic Gulp watch.
|gwatchcb |gulp    |Generic Gulp watch with change handler.
|cl       |generic |Log to console.
|exprr    |Express |Require Express with router.
|exprt    |Express |Require Express with tests.
|rget     |Express |Router get method.
|rpost    |Express |Router post method.
|rdel     |Express |Router delete method.
|rexport  |Express |Exports router.
|desc     |Jasmine |Describe a test.
|mdesc    |Jasmine |Describe a test with an initialized Express app.
|it       |Jasmine |perform a test.
|reqg     |Jasmine |Test a route with HTTP get.
|reqp     |Jasmine |Test a route with HTTP post.

## VSCode
To display all available sippets open the command palette and select 'Insert Snippet.

## Installation
Move to your VSCode snippets path. Usually this is: \Users\%USERNAME%\AppData\Roaming\Code\User\Snippets.

```
git clone https://github.com/klaasjs/codesnippets.git
```

And make it yours:
```
rm -rf .git
```

Enjoy!