## particles.js

### A lightweight JavaScript library for creating particles.

Load particles.js and configure the particles:

**index.html**
```html
<div id="particles-js"></div>

<script src="particles.js"></script>
```

**app.js**
```javascript
/* particlesJS('dom-id', params);
/* @dom-id : set the html tag id [string, optional, default value : particles-js]
/* @params: set the params [object, optional, default values : check particles.js] */

/* default dom id (particles-js) */
//particlesJS();

/* config dom id */
//particlesJS('dom-id');

/* config dom id (optional) + config particles params */
particlesJS('particles-js', {
  particles: {
    color: '#fff',
    shape: 'circle', // "circle", "edge" or "triangle"
    opacity: 1,
    size: 4,
    size_random: true,
<<<<<<< HEAD
    nb: 100,
=======
    nb: 150,
>>>>>>> dev
    line_linked: {
      enable_auto: true,
      distance: 100,
      color: '#fff',
      opacity: 1,
      width: 1,
      condensed_mode: {
        enable: false,
        rotateX: 600,
        rotateY: 600
      }
    },
    anim: {
      enable: true,
      speed: 1
    }
  },
  interactivity: {
    enable: true,
    mouse: {
<<<<<<< HEAD
      distance: 250
=======
      distance: 300
>>>>>>> dev
    },
    detect_on: 'canvas', // "canvas" or "window"
    mode: 'grab',
    line_linked: {
      opacity: .5
    },
    events: {
      onclick: {
<<<<<<< HEAD
    	  push_particles: {
    		  enable: true,
    		  nb: 4
    	  }
    	}
=======
        enable: true,
        mode: 'push', // "push" or "remove"
        nb: 4
      }
>>>>>>> dev
    }
  },
  /* Retina Display Support */
  retina_detect: true
});
```

### ***Live Demo***
<a href="http://codepen.io/VincentGarreau/pen/pnlso" target="_blank">CodePen demo</a>

<a href="http://htmlpreview.github.io/?https://github.com/VincentGarreau/particles.js/blob/master/demo/index.html" target="_blank">GitHub demo</a>
