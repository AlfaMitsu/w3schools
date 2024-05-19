Add another @font-face rule for bold characters of the "sansation" font. Use the URL "sansation_bold.woff".

    @font-face {
      font-family: sansation;
      src: url('sansation_light.woff');
    }
    
    @font-face {
      font-family: sansation;
      src: url('sansation_bold.woff');
      font-weight: bold;
    }
    
    body {
      font-family: sansation;
    }
