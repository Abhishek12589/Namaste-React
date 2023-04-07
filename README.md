# Namaste-React
## Inception

## Here i will list all the question which have been asked during the course

### 1. What is Emmet

Emmet is a plugin for greatly Editor which improves the HTML & CSS Work flow

### 2. Difference between library and framework

A framework is a pre-written code that provide a structure 
to build a full fledge software Application on the other hand library is pre-written code is used to execute the specific function.

### 3. What is CDN?

CDN stands for content delivery network.
Content delivery network is a system of distributed servers that deliver web pages and other content to user.

### 4. Why is React Known as React?

“And it's called React because it reacts. It was developed by Facebook in 2013 (a site that CONSTANTLY updates their data) to improve the user interface development and more effectively change (REACT to) what the user sees when they're doing things like mouse clicking, submitting and typing.”

### 5. What is cross origin in script tag?

The crossorigin attribute is used in script tag to specify weather the browser should allow loading of script resouces from different domain or not.It is used to CORS (Cross Origin Resource Sharing) for Javascript files.

### 6. What is the difference between React and React-dom?

React is a framework tool which provide interactive tools to build the UI component while react-dom provide tools that is used to render the react component they are both essential part of the react framework and used together to build the interactive ui.

### 7.  What is difference between react.development.js and react.production.js files via CDN?

React provides two version of its javascript library react.development.js and react.production.js
In react.development.js it is a unminified version which is used for the development purpose and provide error handlind and runtime environment.

on the otherhand react.production.js is an minified of which code is smaller than react.development.js so it will execute more rapidly it used in production time.

### 8.  What is async and defer? -

These are the attributes used in script tag 
let 's understand the scenario one by one in noraml script file
In normal file execute file is done until it will encountered the script tag if if it encountered the script is fetched and executed then the reamining html file executer

In async execution of html file is done while it will spontaneously fetched the script file and after fetching it execute the script file and after that continue the execution of remainig html file.

in defer execution of html file is done while it will spontaneously fetched the script file and execute the html file, it will execute the script file only after the execution of html file.

in most of the cases we use defer but in the scenario of fetching api we use async.

# Igniting Our App 3

### 1. What is npm?
npm is a node package manager, it is largest software registry in the world, we can use install or publish command to install new package or publish package. we can run packages without downloading using npx.

### 2. What is Parcel?Why do we need it.
It will minified our code, It will optimize our code. Parcel is a bundler that analyzes our code and bundle the code in single or multiple files, this will reduce the number of requests which are sent to the server, which will improve the loading speed of the web page.

### 3. What is parcel cache?
Everything related to parcel stored in parcel cache, when the parcle build the files it creates the dependency graph which will analyze the file in dependency tree, parcel cache will store the file so the next time it will check does these files are similar to previous file, if it is then it will don't reload the file again, this will decrease startup time.

### 4. What is npx?
npx allow us to use the command without having it to install, for ex npx create-react-app, it will install the create-react-app package and then deletes it after running the command.

### 5. what is the difference between dependencies and dev  ncies?
dependencies are the packages that are required to run the project like react, while dev-dependcies are the packages which are used for development like babel. An application can be run without dev-depencies.

### 6. What is tree shaking?
it is used to remove the dead code. it is automacically with modern javascript tool like parcel. This is important to prepare code which is production ready.

### 7. What is Hot Module Replacement?
Hot module Replacement improves the development Experience by up updating module in the browser at the run time, This will maintain the state of web page.

### 8. List down 5 important feature of parcel and explain three of them?
1. Zero Configuration, 2. Code Splitting 3. Fast Development Server 4. Plugin System 5. Support Multiple file types

Zero configuration :- With parcel we don't have to write complex configuration file, as it will bundle the necessary dependency automatically.

Code Splitting : Parcel can split our code in small chunks that can be loaded independently.

Fast Development Server : Parcel is having a fast development server, Developer can see their changes in the code in real time.

### 9. What is .gitignore? what should we add and not add into it.
It is a file used by git to track which files cann't be tracked by git.
We will add apikeys, and the code which can be regenrated can be added in the .gitignore.
and we should not add source code in .gitignore. Although it is not a good practice we have too use version control in efficient manner.

### 10. What is the difference between package.json and package-lock.json?
package.json it is a file which is created when we initialed it with npm init, it will have carat ^ and tilda ~ it simply means that it will be automatically updated according to the latest package.
package-lock.json it's a file which is used to lock the version and it will be track by git when we clone the project from git it will take reference from package-lock.json.

### 11. Why should not modify package-lock.json?
It is not recommended to manually update the package-lock.json, as it will be created automatically it will take lock-control of all the dependency and if it will configured manually, it will effect the project.

### 12. What is node module? Is it good to push on git?
It is used to store all the external package which is required to run our project successfully, it is not good to push node module on git as it will be regenrated with the help of package lock.json

### 13. what is the dist folder?
In context of parcel dist is a distribution folder and it contain the final output files after it processes your project source code, for it will have milified and optimized code which is ready to be deployed on the production.

### 14. What is browserlist?
Browserlist is a tool that specifying which browser should be supported in your frontend app by specifynig query in a config app. it's used by framework and library such as React, vue etc.


# Laying the Foundation

### 1. What is Jsx?
it is a Javascript XML is a syntax for javascript.It allows you to write HTML like code, it was originally developed by Facebook Developer in a way to write react components.Jsx is not a javascript so we need babel which convert jsx to browser readable form.

### 2. SuperPower of Jsx?
The superPower of jsx are is that it allows you to write reusable, expressive and efficient code. Jsx have a great role in the popularity of react.

### 3. {TitleComponent} vs {<TitleComponent/>} vs {<TitleComponent></TitleComponent>} in JSX?
This 3 are the way of rendering react component 
1. {TitleComponent} it will render simply a react element and does not take any props.
2. <TitleComponent/> This will take props as the default attribute.

# Talk is Cheap Show me the Code.

### 1. Is JSX mandatory for React?
NO JSX is not mandatory for react Application, JSX just made our code more convenient which is efficient for the application.Jsx is just a syntatic sugar for React.CreateElement

### 2. Is ES6 mandatory for React?
No ES6 is not mandatory for react. if we don't use Es6 We have to use reate-react-class.

### 3. How to add Comments in JSX?
To add comments in JSX we use curly braces inside the curly brace there is forward slash followed by the astric symbol and in the closing *and the forward symbol. {/**/}

### 4. What is Virtual Dom?
It is a programming concept in react where the virtual representation of UI is kept in the memory and synced with the "real" dom by a library such as ReactDOM. This process is called as Reconcilliation.

### 5. What is react fibre?
React fibre is an ongoing implementation of react core algorithm. It is the Culmination of over two years of react team. Fibre is the new new Reconcilation Engine in React 16. It enables the (incremental rerendering)- The ability to split rendering work in chunks and spread it out over multiple frames.

### 6. why we need keys in react? when we use key in react?
Keys are used in react to track the elements in sets and lists.It will track all the element and accounts any changes like delete,insert,move which will help us to not re-render full list again.
It will improve perfomance, Efficiency. In summary keys are an important component of react and should be used in rendering of list and its children component. This will maintain state and improve efficiency.

### 7. Why we should not use index as key in react?
It is genereally a bad practice to use index as key in react.Because it will effect the perfomance when dealing with large data it will re-render the entire list this will break the dry principle.
We should only use key when data is static, or unique id is not present. We can also generate unique with the help of library.

### 8. What is props in react?
Conceptually component are just like javascript function, we pass arbitrary input called as props.

### 9. What is a config driven UI?
let us take an example to understand config driven ui better, in regular websites there is an opening form which ends up to  login or logout when we want to do some changes the code becomes polluted so to get rid of this we will be usig config driven ui.
There are various methods to implement this creating the schema of the login form.