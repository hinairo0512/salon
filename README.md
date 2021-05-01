# cherimoのサイト

## bootstrap,html,aos,
```html
<!-- counterup -->
 <body>
    <span class="counter">1,234,567</span>
    <div class="counter">1,567</div>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"> </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/2.0.5/waypoints.min.js"></script>

    <script src="jquery.counterup.min.js"></script>
    <script>
        $(document).ready(function () {
            $('.counter').counterUp({
                delay: 10,
                time: 1000
            });
        });
    </script>
</body>

```