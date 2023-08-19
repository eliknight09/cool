# cool
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0 shrink-to-fit=no">
    <link rel="icon" type="image/x-icon" href="./Site/images/logo.png">
    <link rel="stylesheet" href="index.css">
    <title>Zaluea | Home</title>
</head>
<body>
    <div class="bar">
        <div class="main_title"><a href="/">andyum</a></div>
        <div class="button games"><a href="games.html">Games</a></div>
        <div class="button ytlink" onclick="quickLink('hvtrs8%2F-wuw%2Cymuvu%60e%2Ccmm-')">YouTube</div>
        <div class="button tabconfig" onclick="settings()">Tab Config</div>
        <div class="button updates_btn" onclick="updates()">Updates</div>
        <div class="settings" id="settings">
            <div class="settingsstuff title_main">Settings</div>
            <center>
                <input class="setTitle" placeholder="Title" onkeyup="titleSet(this.value)">
                <input class="setIco" placeholder="Icon" onkeyup="iconSet(this.value)">
                <div class="resetButton" onclick="reset()">Reset</div>
            </center>
        </div>
        <div class="updates" id="updates">
            <div class="updatetitle title_updates">Updates</div>
            <center>
                <div class="updatespage" id="updatespage"></div>
            </center>
        </div>
    </div>
    <div class="title">Ultraviolet</div>
    <a href="#" target="_blank">Opens the linked document in a new window or tab</a>
    <a href="#" target="_parent">Opens the linked document in the parent frame</a>
    <center>
        <form>
            <input placeholder="Type or search a URL">
            <div class="links">
        </form>
    </center>
    <script src="uv/uv.bundle.js"></script>
    <script src="uv/uv.config.js"></script>
    <script src="index.js"></script>
    <script src="updates.js"></script>
    <script src="site.js"></script>
</body>
</html>
