---
patternId: notice-animated-footer
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Animated Footer Demo</title>
    <style>
        body {
            overscroll-behavior-y: none;
            font-family: system-ui;
            padding: 2em;
        }
        .banner {
            animation: slideIn 1000ms ease-in-out;
            position: fixed;
            left: 0;
            bottom: 0;
            right: 0;
            padding: 1rem;
            background-color: yellow;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
        }
        @keyframes slideIn {
            from {
                transform: translateY(100vh)
            }

            to {
                transform: translateY(0vh)
            }
        }
        .close-button {
            background: transparent;
            border: none;
            padding: 1em;
            font-size: 1em;
            position: absolute;
            right: 0;
            top: 0;
            cursor: pointer;
        }
    </style>
</head>

<body>
    <div id="banner" class="banner">
        <button id="close-button" class="close-button" aria-label="close" tabindex="0">✕</button>
        <div>
            <h1>Notice</h1>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent.
        </div>
    </div>
    <script>
        document.getElementById("close-button").onclick = () => {
            document.getElementById("banner").style = "display: none";
        }
    </script>
    <div class="filler">
        <h1>Animated Footer</h1>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
            incididunt ut labore et dolore magna aliqua. Maecenas volutpat blandit aliquam etiam 
            erat velit. Integer eget aliquet nibh praesent. Sit amet mattis vulputate enim nulla. 
            Faucibus nisl tincidunt eget nullam non. Sem fringilla ut morbi tincidunt augue. 
            Sed id semper risus in hendrerit gravida rutrum quisque non. Blandit aliquam etiam 
            erat velit scelerisque in dictum non consectetur. Et ultrices neque ornare aenean 
            euismod. Dignissim sodales ut eu sem integer vitae justo. Justo eget magna fermentum 
            iaculis eu non diam phasellus.
        </p>
    </div>
</body>