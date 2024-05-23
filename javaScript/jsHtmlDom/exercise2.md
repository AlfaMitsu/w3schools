Use the getElementsByTagName method to find the first <p> element, and change its text to "Hello".

    <p id="demo"></p>
    
    <script>
    document.getElementsByTagName("p")[0].innerHTML = "Hello";
    </script>
