
# Slide Repository

This is repository for my talk and lecture slides. 

Each talk and lecture is in a separate folder, which can contain more than one slide. Typing the folder name as sub-url of the page, e.g. `https://www.msaidf.com/slides/folder-name`, will open the `index.html` file in the folder. 

If there is only one slide in the folder, it will most likely be the `index.html` file. If there are more than one slide in the folder, `index.html` could be the first slide or the talk or lecture home page. 

You could embed the html slides into a webpage using iframe:

Code:

```
## CSS styles
<style>
.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

.testiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>


## html iframe to embed the slide.

<div class="resp-container">
    <iframe class="testiframe" src="https://msaidf.com/slides/xaringan_example">
      Fallback text here for unsupporting browsers, of which there are scant few.
    </iframe>
</div>

```

Result:

<style>
.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

.testiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>


## html iframe to embed the slide.

<div class="resp-container">
    <iframe class="testiframe" src="https://msaidf.com/slides/xaringan_example">
      Fallback text here for unsupporting browsers, of which there are scant few.
    </iframe>
</div>