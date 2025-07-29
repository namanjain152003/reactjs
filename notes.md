react is a library of javascript used to make our work simple.

we can install react by :-

1. npx create-react-app 01basicreact (this method take lot of time)
2. npm create vite@latest (this method is fast)

in these , package.json is there where the scripts are present which are used to run the project
==> npm run dev is used to run the vite project.


  jsx has ability to return only one element so we can make <> </> to return multiple elements.

  functions name must me start with capital letter
  files name must be capital as well
  
  to use javascriptvariable inside the return in react use {variable name}.

  HOOKS:
  these are used to update and change state...

  we have to import hooks like
  import {useState} from 'react'

  after that in function :-
  
  const/let [counter,setCounter]=useState(15)
  

  props are used to increase the code reusability in the react...