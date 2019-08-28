# scrollify
jquery smooth scrollify

<!DOCTYPE html>
<html lang="">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Title Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        .mainstyle {
            min-width: 100%;
            height: 100vh;
        }
        
        img {
            min-width: 100%;
        }
    </style>

</head>

<body>
    <div class="mainstyle">
        <figure class="imgclass">
            <img src="bg1.png" alt="">
        </figure>
    </div>
    <div class="mainstyle">
        <figure class="imgclass">
            <img src="bg2.png" alt="">
        </figure>
    </div>
   <div class="mainstyle">
        <figure class="imgclass">
            <img src="bg3.png" alt="">
        </figure>
    </div>
    <div class="mainstyle">
        <figure class="imgclass">
            <img src="bg4.png" alt="">
        </figure>
    </div>
    <div class="mainstyle">
        <figure class="imgclass">
            <img src="bg5.png" alt="">
        </figure>
    </div>

    <!-- jQuery -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollify/1.0.19/jquery.scrollify.min.js"></script>
    </script>
</body>
<script>
    $(function() {
        $.scrollify({
            section: ".mainstyle",
        });
    });
</script>

</html>

