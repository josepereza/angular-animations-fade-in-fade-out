# Angular Animations Demo
# otra posibilidad para angular animations fade in - fade out es:
```
trigger('myInsertRemoveTrigger', [
  transition(':enter', [
    style({ opacity: 0 }),
    animate('100ms', style({ opacity: 1 })),
  ]),
  transition(':leave', [
    animate('100ms', style({ opacity: 0 }))
  ])
]),
```

This is a demo of animation features in Angular.

This application was written using Angular 5.0. The features shown here should be compatible with Angular 4.x apps as
well. If you are using AngularJS v1.x, this is not the demo you are looking for.

## Running the project

You will need Node.js and NPM or Yarn installed.

After cloning the repository, open a terminal and run:

```
npm install
npm start
```

The demo application will be available at http://localhost:4200.

## Further reading

To get more help on Angular animations, consult the [official Angular Animations documentation](https://angular.io/guide/animations).
