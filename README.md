<!DOCTYPE html>
<html>
    <head>
        <title>JavaScript and jQuery example to redirect a page or URL </title>
    </head>
    <body>
        <div id="redirect">
            <h2>Redirecting to another page</h2>
        </div>

        <script src="scripts/jquery-1.6.2.min.js"></script>
        <script>
            // JavaScript code to redirect a URL
            window.location.replace("http://stackoverflow.com");
            // window.location.replace('http://code.shouttoday.com');

            // Another way to redirect page using JavaScript

            // window.location.assign('http://code.shouttoday.com');
            // window.location.href = 'http://code.shouttoday.com';
            // document.location.href = '/relativePath';

            //jQuery code to redirect a page or URL
            $(document).ready(function(){
                //var url = "http://code.shouttoday.com";
                //$(location).attr('href',url);
                // $(window).attr('location',url)
                //$(location).prop('href', url)
            });
        </script>
    </body>
</html>
