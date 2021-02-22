# **Installation** #

        npm install @pala/design --save 

# **grid** 
Your project your-file.html

        class="main-g-c-1"

@pala/design

    main.scss

        .main-g-c-1 {
            display:grid;
            grid-template-columns:repeat(1,1fr);
        }

You can use main-g-c-1 until the main-g-c-20 the only thing that changes is the value inside the gri-template-columns property


To center elemets

class="main-center" 
 
       main.scss
       
        .main-center {
                text-align:center;
        }

using grid center center in the middle class="main-g-center"

        main.scss
        
        .main-g-center {
                justify-self:center;
                align-self:center;
        }
        

using grid center top in the middle class="main-g-center-top"
        
        .main-g-center-top {
                justify-self:center;
                align-self:start;
        }
        
class main-xx
        
     main-mt-xx (marign)
     main-mb-xx (margin)
     main-mr-xx (margin)
     main-ml-xx ( margin-left:xx )
     main-w-xxp ( width:xxp )
     main-w-xx ( width: xx% )
     main-h-xxp ( height: xxp )
     main-h-xx ( heigth: xx% )
     main-b-xx ( border:xx% )
     main-center ( text-align:center )
     main-fs-xx ( font-size:xx% )
     
claas media-xx for phone (max-width:812px)

     media-fs-xx ( font-size:xx% )
  
