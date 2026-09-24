<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
</head>

<body>

<form action="" method="post" name="registration">

    <p>
        Username:
        <input type="text" name="Username"
               value="Enter your name here"
               maxlength="30" />
    </p>

    <p>
        Password:
        <input type="password" name="password"
               value="enter your password here"
               maxlength="10" />
    </p>

    <p>
        How would you like your Friday's to look like?
        <textarea name="comments" cols="10" rows="5"></textarea>
    </p>

    <p>
        Please select your favourite genre:
        <br />

        <input type="radio" name="genre" value="rock" checked="checked">
        Rock

        <input type="radio" name="genre" value="pop">
        Pop

        <input type="radio" name="genre" value="jazz">
        Jazz
    </p>

    <p>
        Please select your favorite music service(s):
        <br />

        <input type="checkbox" name="service" value="itunes" checked="checked">
        iTunes

        <input type="checkbox" name="service" value="lastfm">
        Last.fm

        <input type="checkbox" name="service" value="spotify">
        Spotify
    </p>

</form>

</body>
</html>
