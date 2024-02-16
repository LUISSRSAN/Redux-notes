# Redux-notes

CLASSIC REDUX LEGACY 
- CREATE STORE
- InitialState
-USEREDUCER(state = initialState,action){'
switch (action.type){
case 'account/deposit':
 return {type :'account/deposite',payload:500}
default : return state;

}

ACTION CREATORS 

function deposit(amount){
type : "accounts/deposit",payload:amount
}
function withdraw(){}
function requestLoan(){}
function payLoan(){}

COMBINE REDUCERS 

const rooterReducer = CombineReducers ({
account : accountReducer,
customer:customerReducer,
})


FEATURES 
- CREATE A FOLDER NAMED FEATURES AND STORE EVERY NEW FEATURE INSIDE A NEW FOLDER
EXAMPLE
FEATUES/ACCOUNTS
FEATURES/
  ACCOUNTS/
  CUSTOMERS/
