---
title: "Landscape"
layout: splash
# classes: wide
header:
  teaser: /images/photos/landscape/AHVJ3861-2.jpg
  overlay_image: /images/photos/landscape/AHVJ3861-2.jpg
excerpt: "Finding beauty"  
gallerylandscape: 
  - url: /images/photos/landscape/DSC_0676.jpg
    image_path: /images/photos/landscape/DSC_0676.jpg
    alt: "Les Houches, 2018"
    title: "Les Houches, 2018"
  - url: /images/photos/landscape/DSC_3325.jpg
    image_path: /images/photos/landscape/DSC_3325.jpg
    alt: "Edinburgh, 2022"
    title: "Edinburgh, 2022"
  - url: /images/photos/landscape/DSC_1579.jpg
    image_path: /images/photos/landscape/DSC_1579.jpg
    alt: "York, 2019"
    title: "York, 2019"  



  - url: /images/photos/landscape/DSC_2541.jpg
    image_path: /images/photos/landscape/DSC_2541.jpg
    alt: "Leicester, 2021"
    title: "Leicester, 2021"
  - url: /images/photos/landscape/DSC_1748.jpg
    image_path: /images/photos/landscape/DSC_1748.jpg
    alt: "Yorkshire, 2019"
    title: "Yorkshire, 2019"
  - url: /images/photos/landscape/DSC_3230.jpg
    image_path: /images/photos/landscape/DSC_3230.jpg
    alt: "Peak District, 2022"
    title: "Peak District, 2022"    
  
  
  - url: /images/photos/landscape/DSC_2035.jpg
    image_path: /images/photos/landscape/DSC_2035.jpg
    alt: "York, 2020"
    title: "York, 2020"       
  - url: /images/photos/landscape/DSC_3007.jpg
    image_path: /images/photos/landscape/DSC_3007.jpg
    alt: "York, 2021"
    title: "York, 2021"  
  
  - url: /images/photos/landscape/DSC_3280.jpg
    image_path: /images/photos/landscape/DSC_3280.jpg
    alt: "Peak District, 2022"
    title: "Peak District, 2022"  
  
  
  
  
  - url: /images/photos/landscape/DSC_3000.jpg
    image_path: /images/photos/landscape/DSC_3000.jpg
    alt: "York, 2021"
    title: "York, 2021"  

  - url: /images/photos/landscape/DSC_0672.jpg
    image_path: /images/photos/landscape/DSC_0672.jpg
    alt: "Les Houches, 2018"
    title: "Les Houches, 2018"  

  - url: /images/photos/landscape/DSC_1233.jpg
    image_path: /images/photos/landscape/DSC_1233.jpg
    alt: "Cliffs of Moher,  2019"
    title: "Cliffs of Moher,  2019"      



  - url: /images/photos/landscape/AHVJ3861.jpg
    image_path: /images/photos/landscape/AHVJ3861.jpg
    alt: "York, 2023"
    title: "York, 2023"  


  - url: /images/photos/landscape/DSC_1446.jpg
    image_path: /images/photos/landscape/DSC_1446.jpg
    alt: "Scarborough, 2019"
    title: "Scarborough, 2019"  

  - url: /images/photos/landscape/DSC_0616.jpg
    image_path: /images/photos/landscape/DSC_0616.jpg
    alt: "Les Houches, 2018"
    title: "Les Houches, 2018"   
---



 

<!-- {% include gallery id="gallerystreet" layout= "third" style="masonry" %} -->

{% include gallery id="gallerylandscape" layout= "third" style="masonry"%}




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
