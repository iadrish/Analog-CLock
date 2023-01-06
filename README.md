# ANALOG CLOCK 

A Responsive project using HTML-CSS -Vanilla JS to implement A simple Analog Clock

![Screenshot 2023-01-06 185808](https://user-images.githubusercontent.com/88700100/211021819-c9532499-940a-4ef4-aaa4-81fdce7a0906.png)

## Acknowledgements

 - [HTML Resources](https://www.w3schools.com/html/)
 - [CSS Resources](https://developer.mozilla.org/en-US/docs/Learn/CSS)
 - [JavaScript Resources](https://www.w3schools.com/js/default.asp)
 - [Deployment on Netlify](https://www.freecodecamp.org/news/publish-your-website-netlify-github/)


## Authors

- [@iadrish](https://github.com/iadrish)


## Deployment

To deploy this project run

```bash
  npm run deploy
```

Deployment is Live on: https://63b81578dfe0bf36df70dbe4--legendary-paletas-e109cb.netlify.app/
## Documentation

FUNCTIONS used :

d= new Date();

htime=d.getHours();

mtime=d.getMinutes();

stime=d.getSeconds();

To calculate Degree of Rotation For Individual Hour Hand, Minute Hand & Second Hand

hrotation=30*htime+(mtime/2);

mrotation=6*mtime;

srotation=6*stime;
