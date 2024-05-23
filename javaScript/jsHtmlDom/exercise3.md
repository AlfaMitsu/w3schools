Change the text of the first element that has the class name "test".

    <p class="test"></p>
    <p class="test"></p>
    
    <script>
    document.getElementsByClassName("test")[0].innerHTML = "Hello";
    </script>
