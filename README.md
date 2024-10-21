<!DOCTYPE html>
<html>
<head>
    <title>FREE NUMBER OTP BOT</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        @import url("https://fonts.googleapis.com/css?family=Montserrat:400,400i,700");

        :root {
            --font-color: #404040;
            --dp-size: 8rem;
            --padding-size: 2rem;
            --opener-size: 2.5rem;
            --dot-size: 0.4rem;
        }

        body {
            font-size: 16px;
            color: var(--font-color);
            font-family: Montserrat, sans-serif;
            background-image: linear-gradient(to bottom right, #1e1e1e 0%, #1e1e1e 65%, #333 95%, #333 100%);

            background-position: center;
            background-attachment: fixed;
            margin: 0;
            padding: var(--padding-size) 0;
            display: grid;
            place-items: center;
            box-sizing: border-box;
        }

        .card {
            background-color: white;
            max-width: 360px;
            display: flex;
            flex-direction: column;
            overflow: hidden;
            border-radius: 2rem;
            box-shadow: 0px 1rem 1.5rem rgba(black, 0.5);
        }

        .card .banner {
            
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            height: 11rem;
            display: flex;
            align-items: flex-end;
            justify-content: center;
            box-sizing: border-box;
        }

        .card .banner svg {
            background-color: white;
            width: var(--dp-size);
            height: var(--dp-size);
            box-shadow: 0 0.5rem 1rem rgba(black, 0.3);
            border-radius: 50%;
            transform: translateY(50%);
            transition: transform 200ms cubic-bezier(0.18, 0.89, 0.32, 1.28);
        }

        .card .banner svg:hover {
            transform: translateY(50%) scale(1.3);
        }

        .card .menu {
            width: 100%;
            height: 5.5rem;
            padding: 1rem;
            display: flex;
            align-items: flex-start;
            justify-content: flex-end;
            position: relative;
            box-sizing: border-box;
        }

        .card .menu .opener {
            width: var(--opener-size);
            height: var(--opener-size);
            position: relative;
            border-radius: 50%;
            transition: background-color 100ms ease-in-out;
        }

        .card .menu .opener:hover {
            background-color: #f2f2f2;
        }

        .card .menu .opener span {
            background-color: var(--font-color);
            width: var(--dot-size);
            height: var(--dot-size);
            position: absolute;
            top: 0;
            left: calc(50% - var(--dot-size) / 2);
            border-radius: 50%;
        }

        .card .menu .opener span:nth-child(1) {
            top: 0.45rem;
        }

        .card .menu .opener span:nth-child(2) {
            top: 1.05rem;
        }

        .card .menu .opener span:nth-child(3) {
            top: 1.65rem;
        }

        .card h2.name {
            text-align: center;
            padding: 0 var(--padding-size) 0.5rem;
            margin: 0;
        }

        .card .title {
            color: lighten(var(--font-color), 50%);
            font-size: 0.85rem;
            text-align: center;
            padding: 0 var(--padding-size) 1.2rem;
        }

        .card .actions {
            padding: 0 var(--padding-size) 1.2rem;
            display: flex;
            flex-direction: column;
            order: 99;
        }

        .card .actions .follow-info {
            padding: 0 0 1rem;
            display: flex;
        }

        .card .actions .follow-info h2 {
            text-align: center;
            width: 50%;
            margin: 0;
            box-sizing: border-box;
        }

        .card .actions .follow-info h2 a {
            text-decoration: none;
            padding: 0.8rem;
            display: flex;
            flex-direction: column;
            border-radius: 0.8rem;
            transition: background-color 100ms ease-in-out;
        }

        .card .actions .follow-info h2 a span {
            color: #1c9eff;
            font-weight: bold;
            transform-origin: bottom;
            transform: scaleY(1.3);
            transition: color 100ms ease-in-out;
        }

        .card .actions .follow-info h2 a small {
            color: #afafaf;
            font-size: 0.85rem;
            font-weight: normal;
        }

        .card .actions .follow-info h2 a:hover {
            background-color: #f2f2f2;
            span {
                color: #007ad6;
            }
        }

        .card .actions .follow-btn button {
            color: inherit;
            font: inherit;
            font-weight: bold;
            background-color: #ffd01a;
            width: 100%;
            border: none;
            padding: 1rem;
            outline: none;
            box-sizing: border-box;
            border-radius: 1.5rem / 50%;
            transition: background-color 100ms ease-in-out, transform 200ms cubic-bezier(0.18, 0.89, 0.32, 1.28);
        }

        .card .actions .follow-btn button:hover {
            background-color: #efb10a;
            transform: scale(1.1);
                }
        .card .actions .follow-btn button:active {
            background-color: #e8a200;
            transform: scale(1);
        }
        .card .desc {
            text-align: justify;
            padding: 0 var(--padding-size) 2.5rem;
            order: 100;
        }
    </style>
</head>
<body>
    <br><br><br><br><br><br><br><br>
    <div class="card">
     <div class="banner">
            <!-- SVG for the profile picture -->
           <img src="https://i.ibb.co/LQ94p4V/IMG-7434.jpg" alt="Play Code Telegram" height="214">
        </div>
        <br>
       <center> <h3 class="name">FREE OTP BOT</h3>
        
        <div class="actions">
            
            <div class="follow-btn">
                <button onclick="location.href='https://t.me/otpnationalBOT?start=6885146196'">Start Bot</button>
 </div>
        </div></div>
        
</body>
</html>
