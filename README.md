<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protocols List</title>
    <style>
        /* Body and page styling */
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #1e1e1e;
            color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        /* Header styling */
        h1 {
            font-size: 3rem;
            color: #00d4ff;
            text-transform: uppercase;
            margin-bottom: 30px;
            text-shadow: 2px 2px 6px rgba(0, 212, 255, 0.4);
        }

        /* Protocol container styling */
        .protocol-container {
            width: 80%;
            max-width: 1000px;
        }

        /* Individual protocol box styling */
        .protocol {
            background-color: #2e2e2e;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 15px;
            border: 1px solid #444;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .protocol:hover {
            transform: translateY(-10px);
            background-color: #1f1f1f;
        }

        /* Protocol title styling */
        .protocol h4 {
            font-size: 1.5rem;
            color: #ff4081;
            margin-bottom: 10px;
            letter-spacing: 1px;
            position: relative;
        }

        .protocol h4::before {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 50px;
            height: 2px;
            background-color: #ff4081;
            transition: width 0.3s ease;
        }

        .protocol:hover h4::before {
            width: 100px;
        }

        /* Protocol description styling */
        .protocol p {
            color: #ccc;
            line-height: 1.6;
        }

        /* Subtle animation on the container */
        .protocol-container {
            animation: fadeIn 1s ease;
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: scale(0.95); }
            100% { opacity: 1; transform: scale(1); }
        }

        /* Media query for responsiveness */
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }

            .protocol h4 {
                font-size: 1.2rem;
            }

            .protocol p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>

    <h1>Protocols</h1>

    <div class="protocol-container">
        <div class="protocol">
            <h4>A.N.</h4>
            <p>The A.N. protocol stands for "Action Needed".</p>
        </div>

        <div class="protocol">
            <h4>L.I.</h4>
            <p>The L.I. protocol stands for "Leaked Information".</p>
        </div>

        <div class="protocol">
            <h4>R</h4>
            <p>The R protocol stands for "Raid". When it happens, the server chats will be closed/locked.</p>
        </div>
    </div>

</body>
</html>
