# DA-PARALLAX

A parallax directive for Angular 7+!
This project is used to add parallax on Angular 7+ project
This is created by an Idea of Gaurav Foujdar

See an example here: http://davideagosti.me

## Installation

Download da-paralax.directive.ts file and copy into your project. 
Add this directive by import in app.module.ts

## Importing to your application

Reference the directive in the main module:

```typescript
import { DaParallaxDirective } from 'da-parallax.directive';
```

Then in your base module:
```typescript
declarations: [
    DaParallaxDirective,
]
```

# Parallax Directive for Angular 8

Put the directive on any component you have styled for it:

```html
<div daParallax imgSrc="image path" imgHeight="100vh" bgAttachment="fixed" bgSize="cover" [speed]="-0.4"></div>
```


## Customisation
Below all Options in your html component wher do you like see the parallax effect.

The config gives the following options:

Value           | Use
--------------- | ---------------
imgSrc          | path to your image
imgHeight       | backgound height. default is 70vh 
bgAttachment    | Background Attachment default is Fixed
bgPosition      | Initial offset to use for the scroll, defaults to 50% 0
bgSize          | backgound size. default is cover
[speed]         | speed to scroll at; can be negative to change direction, default is -0.4

## License
MIT