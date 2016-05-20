


Resolving Promises in Angular (From some Service)

```
someService.checkToken()
	.then(
		function(data){
			//promise fulfilled
		},
		function(error) {
	    	// promise rejected
			console.log('error', error);
	    }
	)
```
	    
