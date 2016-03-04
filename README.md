# mk-blocker
Angular Loader, Blocker, Unblocker

##### Install with bower	
```
    $ bower install mk-blocker
```

##### Inject dependency into your applicaiton
```javascript
	angular.module('yourModule', ['mkBlock']);
```

##### Inject mkBlocker service to your controller
```javascript
	.controller('yourCtrl', function(mkBlocker){
		mkBlocker.blockUI(); // to block the UI
		mkBlocker.unblockUI(); // to unblock the UI
		mkBlocker.toggleUI(); // to toggle the UI blocking
	});
```
