#React Redux Typescript

Small React project to use Redux with Typescript

#Create as a TS project from start:

Migration for a JS react app is painful becase types and tsconfig aren't created automatically. Best to use the TS template.

```
$ yarn create react-app my-app --template typescript
```

##Using Redux with TS (yarn v1):

```
$ yarn -v

> 1.22.18 (ie version 1)

$ npx yarn-deduplicate --packages @types/react

$ yarn add react-redux @reduxjs/toolkit @types/react-redux
```

This would bee easier, install REact / TS and Redux from template:

```
$ npx create-react-app my-app --template redux-typescript
```

SEE: https://react-redux.js.org/tutorials/typescript-quick-start
