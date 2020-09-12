# Welcome to deepzoomup 
> Easily share your high resolution photos as deep zoom images with the world. 


Creating large interactive deep zoom images on the web used to be a technically demanding job. Until now. This Python package *deepzoomup* has been made to easily convert your high resolution images and publish them on line as interactive deep zoom images for anyone to admire or study. 

# What you need to do 

(I assume you know have Python installed and know how to run Jupyter notebooks.) 

1) Install this package with 

    $ pip install 

2) Get an account for cloud storage at Backblaze B2. 

3) Create a public B2 bucket with credentials (id and key) for reading and writing. 

4) Run the following code in your Jupyter notebook: 

    <Code here>



Here is an example of a deepzoom image that was created with *deepzoomup*: 

<script src="https://cdnjs.cloudflare.com/ajax/libs/openseadragon/2.4.2/openseadragon.min.js" 
        integrity="sha512-qvQYH6mPuE46uFcWLI8BdGaJpB5taX4lltbSIw5GF4iODh2xIgyz5ii1WpuzPFUknHCps0mi4mFGR44bjdZlZg==" 
        crossorigin="anonymous">
</script>

<div id="xyx" style="width: 800px; height: 400px; background-color: snow"></div>
<script src="https://dore-data.s3.us-west-002.backblazeb2.com/viewers/xxx.js?callback=OpenSeadragon"></script>
