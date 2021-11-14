# Huddle-landing-page
Huddle landing page designed using HTML,CSS,Bootstrap.
This landing page themed as Huddle has also utilized some of the stylish animation effects provided by 
the open-source CSS animation library called, Animate.css (https://animate.style/)
We can start implementing it directly with the use te CDN link provided by Animate.css
```
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
```
And we're good to go.
  1) We can either implement them directly in our HTML files like this

### Syntax:
```
class="animate__animated animate__bounce"
```
Usage:
```
<h1 class="animate__animated animate__bounce animate__delay-2s">Hello</h1>
```
The above code fragment gives a bounce effect to the h1 tag with a delay of 2 seconds
#### OR
  2) We can add it in our CSS using the animation property.
```
  h1{
  animation-name:bounce;
  animation-duration:2s;
  animation-timing-function:ease-in;
  animation-delay:0.4s;
  }
```
We can add as many animation styles as we need in order to improve our site's user experience.

## Design
### Desktop design
![image](https://user-images.githubusercontent.com/78952955/141670816-4626cbed-03c4-4266-a0a8-f5eb5b9cba28.png)

### Mobile design
![image](https://user-images.githubusercontent.com/78952955/141670851-65b81f04-0730-48b4-bef9-e2cadc65e20f.png)

### Live site URL
https://huddle-connection.netlify.app/
