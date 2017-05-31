# ng-lib

## GOAL
STOPGAP: To allow user to take an @angular/cli generated project and run ng-lib over it to generate a publishable library.
Eventually as the angular SDK improves to give more granular control to the build I want this repo to become obsolete.

## Desired syntax

```BASH
ng new my-project && ng-lib my-project/
```

This would generate a new angular project and using the existing format genrate a ready to publish folder under build/
