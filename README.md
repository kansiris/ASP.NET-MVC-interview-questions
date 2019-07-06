# ASP.NET MVC Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated. Follow me [@kansiris87](https://twitter.com/kansiris87) for technical updates.

### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is MVC?](#What is MVC?)|
|2 | [Explain MVC design pattern?](#Explain MVC design pattern?)|
|3 | [What is Domain Driven Design and Development?](#What is Domain Driven Design and Development?)|
|4 | [What is MVP pattern?](#What is MVP pattern?)|
|5 | [What is MVVM pattern?](#What is MVVM pattern?)|
|6 | [What is ASP.NET MVC?](#What is ASP.NET MVC?)|
|7 | [How MVC pattern works in ASP.NET MVC?](#How MVC pattern works in ASP.NET MVC?)|
|8 | [How Model, View and Controller communicate with each other in ASP.NET MVC?](#How Model, View and Controller communicate with each other in ASP.NET MVC?)|
|9 | [What are advantages of ASP.NET MVC?](#What are advantages of ASP.NET MVC?)|
|10| [Explain brief history of ASP.NET MVC?](#Explain brief history of ASP.NET MVC?)|
|1 | [What is difference between 3-layer architecture and MVC architecture?](#What is difference between 3-layer architecture and MVC architecture?)|
|2 | [What is difference between ASP.NET WebForm and ASP.NET MVC?](#What is difference between ASP.NET WebForm and ASP.NET MVC?)|
|3 | [What is ViewModel in ASP.NET MVC?](#What is ViewModel in ASP.NET MVC?)|
|4 | [Explain ASP.NET MVC pipeline?](#Explain ASP.NET MVC pipeline?)|
|5 | [What is Routing in ASP.NET MVC?](#What is Routing in ASP.NET MVC?)|
|6 | [How to define a route in ASP.NET MVC?](#How to define a route in ASP.NET MVC?)|
|7 | [What is Attribute Routing and how to define it?](#What is Attribute Routing and how to define it?)|
|8 | [When to use Attribute Routing?](#When to use Attribute Routing?)|
|9 | [How to enable Attribute Routing in ASP.NET MVC?](#How to enable Attribute Routing in ASP.NET MVC?)|
|10| [How to define Attribute Routing for Area in ASP.NET MVC?](#How to define Attribute Routing for Area in ASP.NET MVC?)|
|1 | [What is difference between Routing and URL Rewriting?](#What is difference between Routing and URL Rewriting?)|
|2 | [What is Route Constraints in ASP.NET MVC?](#What is Route Constraints in ASP.NET MVC?)|
|3 | [How route table is created in ASP.NET MVC?](#How route table is created in ASP.NET MVC?)|
|4 | [What are important namespaces in ASP.NET MVC?](#What are important namespaces in ASP.NET MVC?)|
|5 | [What is View Engine? ](#What is View Engine? )|
|6 | [How View Engine works? ](#How View Engine works?)|
|7 | [What is Razor View Engine? ](#What is Razor View Engine? )|
|8 | [How to make Custom View Engine? ](#How to make Custom View Engine? )|
|9 | [How to register Custom View Engine in ASP.NET MVC?](#How to register Custom View Engine in ASP.NET MVC?)|
|10| [Can you remove default View Engine in ASP.NET MVC?](#Can you remove default View Engine in ASP.NET MVC? )|

|1 | [What is difference between Razor and WebForm engine?](#What is difference between Razor and WebForm engine?)|
|2 | [What are HTML Helpers in ASP.NET MVC? ](#What are HTML Helpers in ASP.NET MVC? )|
|3 | [What are different types of HTML Helpers? ](#What are different types of HTML Helpers? )|
|4 | [What are Url Helpers?](#What are Url Helpers?)|
|5 | [What is Validation Summary?](#What is Validation Summary?)|
|6 | [What are AJAX Helpers? ](#What are AJAX Helpers? )|
|7 | [What is unobtrusive AJAX?](#What is unobtrusive AJAX?)|
|8 | [What are various configuration options for AJAX Helpers? ](#What are various configuration options for AJAX Helpers?)|
|9 | [What is Cross Domain AJAX?](#What is Cross Domain AJAX?)|
|10| [What are Layouts in ASP.NET MVC?](#What are Layouts in ASP.NET MVC?)|
|1 | [What are Sections in ASP.NET MVC?](#What are Sections in ASP.NET MVC?)|
|2 | [What are RenderBody and RenderPage in ASP.NET MVC?](#What are RenderBody and RenderPage in ASP.NET MVC?)|
|3 | [What are Styles.Render and Scripts.Render?](#What are Styles.Render and Scripts.Render?)|
|4 | [How to enable and disable optimizations in ASP.NET MVC?](#How to enable and disable optimizations in ASP.NET MVC?)|
|5 | [What is ViewStart?](#What is ViewStart?)|
|6 | [When to use _ViewStart? ](#When to use _ViewStart? )|
|7 | [What are different ways of rendering layout in ASP.NET MVC?](#What are different ways of rendering layout in ASP.NET MVC?)|
|8 | [What is App_Start folder in ASP.NET MVC?](#What is App_Start folder in ASP.NET MVC?)|
|9 | [What are different ways of returning/rendering a view in ASP.NET MVC?](#What are different ways of returning/rendering a view in ASP.NET MVC?)|
|10| [What are differences among ViewData, ViewBag, TempData and Session?](#What are differences among ViewData, ViewBag, TempData and Session?)|
|1 | [How to persist data in TempData?](#How to persist data in TempData?)|
|2 | [How to control Session behavior in ASP.NET MVC?](#How to control Session behavior in ASP.NET MVC?)|
|3 | [How TempData is related to Session in ASP.NET MVC? ](#How TempData is related to Session in ASP.NET MVC? )|
|4 | [What are Action methods in ASP.NET MVC? ](#What are Action methods in ASP.NET MVC? )|
|5 | [What is ActionResult and how is it different from others? ](#What is ActionResult and how is it different from others?)|
|6 | [How to make a Non-Action method in ASP.NET MVC?](#How to make a Non-Action method in ASP.NET MVC? )|
|7 | [Can you change action method name?](#Can you change action method name?)|
|8 | [How to restrict an action method to be invoked only by HTTP GET, POST, PUT or DELETE?](#How to restrict an action method to be invoked only by HTTP GET, POST, PUT or DELETE?)|
|9 | [How to determine an action method is invoked by HTTP GET or POST?](#How to determine an action method is invoked by HTTP GET or POST?)|
|10| [How to determine an AJAX request?](#How to determine an AJAX request?)|


|1 | [What is Data Annotations in ASP.NET MVC?](#What is Data Annotations in ASP.NET MVC?)|
|2 | [How to apply Server side validation in ASP.NET MVC?](#How to apply Server side validation in ASP.NET MVC?)|
|3 | [How to determine there is no error in Model State?](#How to determine there is no error in Model State?)|
|4 | [How to enable and disable client-side validation in ASP.NET MVC?](#How to enable and disable client-side validation in ASP.NET MVC?)|
|5 | [What is a CDN and advantages of CDN?](#What is a CDN and advantages of CDN?)|
|6 | [What is jquery.validate.unobtrusive.js?](#What is jquery.validate.unobtrusive.js?)|
|7 | [What is Bundling and Minification in ASP.NET MVC? ](#What is Bundling and Minification in ASP.NET MVC? )|
|8 | [Can we use Bundling and Minification in ASP.NET MVC3 or ASP.NET4.0?](#Can we use Bundling and Minification in ASP.NET MVC3 or ASP.NET4.0?)|
|9 | [How Bundling use browser Cache capability?](#How Bundling use browser Cache capability? )|
|10| [What is Partial View in ASP.NET MVC?](#What is Partial View in ASP.NET MVC?)|
|1 | [How do you return a partial view from controller? ](#How do you return a partial view from controller? )|
|2 | [What are different ways of rendering a Partial View in ASP.NET MVC?](#What are different ways of rendering a Partial View in ASP.NET MVC?)|
|3 | [What is Area in ASP.NET MVC? ](#What is Area in ASP.NET MVC? )|
|4 | [How to register Area in ASP.NET MVC?](#How to register Area in ASP.NET MVC?)|
|5 | [What is Child action and how to invoke it? ](#What is Child action and how to invoke it? )|
|6 | [What is Scaffolding? ](#What is Scaffolding? )|
|7 | [How Scaffold templates works in ASP.NET MVC?](#How Scaffold templates works in ASP.NET MVC?)|
|8 | [What are ASP.NET MVC Filters and Attributes? ](#What are ASP.NET MVC Filters and Attributes? )|
|9 | [What are different types of Filters in ASP.NET MVC? ](#What are different types of Filters in ASP.NET MVC?)|
|10| [When Exception filters are executed in ASP.NET MVC? ](#When Exception filters are executed in ASP.NET MVC? )|
|1 | [What is the order of execution of filters in ASP.NET MVC? ](#What is the order of execution of filters in ASP.NET MVC? )|
|2 | [How to configure filters in ASP.NET MVC?](#How to configure filters in ASP.NET MVC? )|
|3 | [How Authentication and Authorization work in ASP.NET MVC?](#How Authentication and Authorization work in ASP.NET MVC?)|
|4 | [How Forms Authentication and Authorization work in ASP.NET MVC? ](#How Forms Authentication and Authorization work in ASP.NET MVC? )|
|5 | [How to implement custom Forms Authentication and Authorization in MVC?](#How to implement custom Forms Authentication and Authorization in MVC?)|
|6 | [How to allow HTML tags in ASP.NET MVC? ](#How to allow HTML tags in ASP.NET MVC? )|
|7 | [What is caching and when to use it? ](#What is caching and when to use it? )|
|8 | [What are advantages of caching?](#What are advantages of caching?)|
|9 | [What is output caching?](#What is output caching?)|
|10| [What is Donut caching and Donut hole caching in ASP.NET MVC?](#What is Donut caching and Donut hole caching in ASP.NET MVC?)|

|1 | [What is loose coupling and how is it possible?](#What is loose coupling and how is it possible?)|
|2 | [What are Dependency Inversion Principle (DIP) and IoC?](#What are Dependency Inversion Principle (DIP) and IoC?)|
|3 | [What is Dependency Injection (DI)?](#What is Dependency Injection (DI)?)|
|4 | [What is Service Locator?](#What is Service Locator?)|
|5 | [What are different ways to implement Dependency Injection (DI)?](#What are different ways to implement Dependency Injection (DI)?)|
|6 | [What are advantages of Dependency Injection (DI)?](#What are advantages of Dependency Injection (DI)?)|
|7 | [What is IoC or DI container? ](#What is IoC or DI container?)|
|8 | [What are popular DI containers?](#What are popular DI containers?)|
|9 | [What is Test Driven Development (TDD)?](#What is Test Driven Development (TDD)?)|
|10| [What are commonly used tool for Unit Testing in ASP.NET MVC?](#What are commonly used tool for Unit Testing in ASP.NET MVC?)|











1. ### What is Angular Framework?

    Angular is a **TypeScript-based open-source** front-end platform that makes it easy to build applications with in web/mobile/desktop. The major features of this framework such as declarative templates, dependency injection, end to end tooling, and many more other features are used to ease the development.

2. ### What is the difference between AngularJS and Angular?
    Angular is a completely revived component-based framework in which an application is a tree of individual components.

    Some of the major difference in tabular form

    | AngularJS | Angular |
    |---- | ---------
    | It is based on MVC architecture  | This is based on Service/Controller |
    | This uses use JavaScript to build the application| Introduced the typescript to write the application |
    | Based on controllers concept| This is a component based UI approach|
    | Not a mobile friendly framework| Developed considering mobile platform|
    | Difficulty in SEO friendly application development| Ease to create SEO friendly applications|

3. ### What is TypeScript?
    TypeScript is a typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await, and many other features, and compiles to plain JavaScript. Angular built entirely in TypeScript and used as a primary language.
    You can install it globally as
    ```
    npm install -g typescript
    ```
    Let's see a simple example of TypeScript usage,
    ```typescript
    function greeter(person: string) {
        return "Hello, " + person;
    }

    let user = "Sudheer";

    document.body.innerHTML = greeter(user);
    ```
    The greeter method allows only string type as argument.


