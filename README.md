# LAP 3 Thursday REDUX


https://user-images.githubusercontent.com/99121268/174737220-4a30adfc-8119-430b-90b3-31a3e02cb25c.mov

<img width="729" alt="Screenshot 2022-06-20 at 14 52 36" src="https://user-images.githubusercontent.com/99121268/174737368-882abda5-a8b3-4a70-9724-128c8960de50.png">

- `mkdir redux-thursday && cd $_ && npx create-react-app .`
- Redux library
- npm install react-router

- make navbar 
- add balance : 0 
- when balance in deposit is + 100 we want to add it to the homepage

## GOAL: Share states between components:

- REDUX state manager (easier to debug)
- npm install redux react-redux
- useSelector to read state(value of state) (redux)
- connect state 
- store is where the state lives 
- action is object that takes type as field

- useDispatch hook (to update the state)


# RECAP: 
- goals: share state between components 
- `useState` limts us to one component 
- add `Provider` (allow pass props info to all children ) (wtihin store we have all to belongs to my states: deposit, withdraw , reducer, home)
- to read state we use `useSelector` hook 
- to interact iwht the state we use `useDispatch` hook (we can send thing (+100) we are trying to do)
- dispatch (reducer) we take 2 values and we turn it into one thing
- with dispatch we dispatch actions (action is simple JS object with a key)


# 2 reducers
- add new loanReducer.js 
- to play with more than 1 reducer we need to install sth combineReducers
- `useDispatch` to update the state 
- `npm install redux-thunk`  import + add applyMiddleware (connects two pieces of application)
- add Loading while add deposit has 2 s delay 
