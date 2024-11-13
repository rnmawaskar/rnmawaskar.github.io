<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Voting Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .header {
            font-size: 1.2em;
            margin-top: 20px;
            color: #333;
        }
        .notice {
            background-color: red;
            color: white;
            padding: 10px;
            margin: 10px 0;
            font-weight: bold;
        }
        .share-buttons img {
            width: 30px;
            margin: 0 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 10px;
        }
        th {
            background-color: #f4f4f4;
        }
        .candidate-row {
            background-color: #ffd966;
        }
        .candidate-img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
        }
        .party-symbol {
            width: 40px;
        }
        .vote-button {
            background-color: #4b4bf8;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="header">103 - भोकर्दन-जाफ्राबाद विधान सभा सार्वत्रिक निवडणूक 2024<br>डमी मतदान यंत्र</div>
    <div class="notice">मतदानाच्या दिवशी सुचिता कमी चिन्हा समोरील बटण दाबावे</div>

    <div class="share-buttons">
        <button class="share-button" style="background-color: #25d366; color: white; padding: 10px;">Share</button>
        <img src="facebook_icon.png" alt="Facebook">
        <img src="instagram_icon.png" alt="Instagram">
    </div>

    <table>
        <thead>
            <tr>
                <th>अ.क्र</th>
                <th>उमेदवाराचे नाव</th>
                <th>चित्र</th>
                <th>बल्ब</th>
                <th>बटण</th>
            </tr>
        </thead>
        <tbody>
            <tr class="candidate-row">
                <td>2</td>
                <td>दानवे संतोष रावसाहेब</td>
                <td><img src="candidate_image.jpg" alt="Candidate" class="candidate-img"></td>
                <td><img src="party_symbol.jpg" alt="Party Symbol" class="party-symbol"></td>
                <td><button class="vote-button">बटण दाबा</button></td>
            </tr>
            <!-- Add more rows as needed -->
        </tbody>
    </table>
</body>
</html>
