# jquery-animated-bg
A simple jQuery plugin to create a gradient animated background with floating particles

![GIF of sample](https://github.com/konalexiou/jquery-animated-bg/blob/master/example.gif)

## Usage
To use this plugin you need to have jQuery.

```
<script
      src="http://code.jquery.com/jquery-1.12.4.min.js"
      integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ="
      crossorigin="anonymous"></script>

<script src="jquery.animated-bg.js"></script>
```

After that you just call the plugin

```
<script>
  $(document).ready(function(){
    $('.animated-bg').animatedbg();
  });
</script>
```


## Options
Below are some of the options you can use

```
<script>
  $(document).ready(function(){

    $('.animated-bg').animatedbg({
      colors : ["#7dcbd4", "#fdc014", "#acd573", "#fff"],
      numParticles: 150
    });

  });
</script>
```
