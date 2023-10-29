---
title: "Street Photography"
layout: splash
# classes: wide
header:
  overlay_image: /images/photos/street/AHVJ2815-3.jpg
  teaser: /images/photos/street/AHVJ2815-3.jpg
  # overlay_filter:             #Color/opacity to overlay on top of the header image. Example: 0.5, rgba(255, 0, 0, 0.5) or linear-gradient. 
#   caption: "photo bottom right"     
excerpt: "Pieces of a city" 
tagline:    #Overrides page excerpt. Useful when header text needs to be different from excerpt in archive views.

gallerystreet: 
  - url: /images/photos/street/DSC_5328.jpg
    image_path: /images/photos/street/DSC_5328.jpg
    alt: "Lisboa, 2023"
    title: "Lisboa, 2023"
  - url:  /images/photos/street/E28A1558.jpg
    image_path: /images/photos/street/E28A1558.jpg
    alt: "Leeds, 2023"
    title: "Leeds, 2023"
  - url:  /images/photos/street/AHVJ5757.jpg
    image_path: /images/photos/street/AHVJ5757.jpg
    alt: "Liverpool, 2023"
    title: "Liverpool, 2023"

  - url: /images/photos/street/DSC_5747.jpg
    image_path: /images/photos/street/DSC_5747.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"
  - url: /images/photos/street/AHVJ5420.jpg
    image_path: /images/photos/street/AHVJ5420.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"  
  - url: /images/photos/street/AHVJ4162.jpg
    image_path: /images/photos/street/AHVJ4162.jpg
    alt: "Bolton, 2023"
    title: "Bolton, 2023"

  - url: /images/photos/street/E28A1268.jpg
    image_path: /images/photos/street/E28A1268.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"   
  - url: /images/photos/street/AHVJ5694.jpg
    image_path: /images/photos/street/AHVJ5694.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"    
  - url: /images/photos/street/E28A2030.jpg
    image_path: /images/photos/street/E28A2030.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023" 

  - url: /images/photos/street/AHVJ3769.jpg
    image_path: /images/photos/street/AHVJ3769.jpg
    alt: "Liverpool, 2023"
    title: "Liverpool, 2023"   
  - url: /images/photos/street/E28A1791.jpg
    image_path: /images/photos/street/E28A1791.jpg
    alt: "Leeds, 2023"
    title: "Leeds, 2023"   
  - url: /images/photos/street/AHVJ2801.jpg
    image_path: /images/photos/street/AHVJ2801.jpg
    alt: "Sale, 2023"
    title: "Sale, 2023"   
    
  - url: /images/photos/street/DSC_5819.jpg
    image_path: /images/photos/street/DSC_5819.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"  
  - url: /images/photos/street/AHVJ2815.jpg
    image_path: /images/photos/street/AHVJ2815.jpg
    alt: "Sale, 2023"
    title: "Sale, 2023"   
  - url: /images/photos/street/AHVJ3498.jpg
    image_path: /images/photos/street/AHVJ3498.jpg
    alt: "Blackburn, 2023"
    title: "Blackburn, 2023"    

  - url: /images/photos/street/DSC_3686.jpg
    image_path: /images/photos/street/DSC_3686.jpg
    alt: "Manchester, 2022"
    title: "Manchester, 2022"
  - url: /images/photos/street/AHVJ5337.jpg
    image_path: /images/photos/street/AHVJ5337.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"
  - url: /images/photos/street/DSC_4620.jpg
    image_path: /images/photos/street/DSC_4620.jpg
    alt: "Manchester, 2022"
    title: "Manchester, 2022"

  - url: /images/photos/street/DSC_5344.jpg
    image_path: /images/photos/street/DSC_5344.jpg
    alt: "Lisboa, 2023"
    title: "Lisboa, 2023"   
  - url: /images/photos/street/DSC_6106.jpg
    image_path: /images/photos/street/DSC_6106.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"  
  - url: /images/photos/street/AHVJ5213.jpg
    image_path: /images/photos/street/AHVJ5213.jpg
    alt: "Lancaster, 2023"
    title: "Lancaster, 2023"  

  - url: /images/photos/street/AHVJ5840.jpg
    image_path: /images/photos/street/AHVJ5840.jpg
    alt: "Liverpool, 2023"
    title: "Liverpool, 2023"  
  - url: /images/photos/street/E28A1129.jpg
    image_path: /images/photos/street/E28A1129.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"     
  - url: /images/photos/street/DSC_5751.jpg
    image_path: /images/photos/street/DSC_5751.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"       

  - url: /images/photos/street/DSC_5844.jpg
    image_path: /images/photos/street/DSC_5844.jpg
    alt: "Manchester, 2023"
    title: "Manchester, 2023"   
  - url: /images/photos/street/DSC_0548.jpg
    image_path: /images/photos/street/DSC_0548.jpg
    alt: "Whitby, 2018"
    title: "Whitby, 2018"       
autor_profile: false
---







<!-- {% include gallery id="gallerystreet" layout= "third"%} -->

{% include gallery id="gallerystreet" layout= "third" style="masonry"%}




<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<!-- <script src="https://unpkg.com/masonry-layout@4/dist/masonry.pkgd.min.js"></script> -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/masonry/4.2.2/masonry.pkgd.min.js"></script>
<script src="https://unpkg.com/imagesloaded@4/imagesloaded.pkgd.min.js"></script>




<script>
    // Wait for the images to load
    imagesLoaded(document.querySelector('.masonry'), function() {
        var elem = document.querySelector('.masonry');
        var msnry = new Masonry(elem, {
            itemSelector: '.masonry-item',
            columnWidth: '.masonry-item', // Use masonry-item's width as the column width
            percentPosition: true
            // ,gutter: 10  // This specifies a 10px gutter both vertically and horizontally
        });
    });
</script>


