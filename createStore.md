# createStore

## apis
- getState: return current state
- subscribe: listener use this function to connect the state, return the function of unsubscribe
- dispatch: outer use this function to change the inner state, when this function invokes, the subscribed listeners will be called.
- replaceReducer: the store use it to caculate the state;
- [$$observable]: resersed function

## usage
1) create reducer 

	const reducer = function(state, action) {
		// handle state according the action
		const nextState = {};
		// ...
		return nextState;
	}
	
2) create store
	
3) store.subscribe(listener)
4)
	



