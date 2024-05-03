<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata</title>
    <style>

        .kotak {
            background-color: #75e577;
            border-radius: 8px; /* Memperkecil radius border */
            box-shadow: 0 0 8px rgba(0, 0, 0, 0.1); /* Memperkecil ukuran bayangan */
            margin: 20px auto;
            padding: 16px; /* Memperkecil padding */
            width: 75%; /* Mengurangi lebar kotak */
            max-width: 600px; /* Memperkecil lebar maksimum kotak */
            overflow: hidden;
        }

        .judul {
            text-align: center;
            margin-bottom: 16px; /* Memperkecil jarak antara judul dan konten */
        }

        .foto-informasi {
            display: flex;
            align-items: center;
        }

        .foto-profil {
            border-radius: 50%;
            box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
            margin-right: 12px; /* Memperkecil jarak antara foto profil dan informasi */
            flex-shrink: 0;
        }

        .informasi {
            flex-grow: 1;
            font-size: 14px; /* Menyesuaikan ukuran huruf */
        }

        .informasi table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 12px; /* Memperkecil jarak antara tabel dan konten */
        }

        .informasi table td {
            padding: 8px; /* Memperkecil padding */
            border-bottom: 1px solid #581313;
        }

        .pendidikan,
        .pengalaman,
        .keahlian {
            margin-top: 16px; /* Memperkecil jarak antara bagian-bagian */
        }

        .pendidikan ul,
        .pengalaman ul,
        .keahlian ul {
            list-style-type: none;
            padding: 0;
        }

        .pendidikan ul li::before,
        .pengalaman ul li::before,
        .keahlian ul li::before {
            content: "\2022";
            color: #000000;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
    </style>
</head>
<body>
    <div class="kotak">
        <div class="judul">
            <h1>Biodata DIRI</h1>
        </div>

        <div class="foto-informasi">
            <img class="foto-profil" src="download (3).jpeg" alt="Foto Profil">
            <div class="informasi">
                <table>
                    <tr>
                        <td>Nama :</td>
                        <td>Erlin</td>
                    </tr>
                    <tr>
                        <td>Tempat :</td>
                        <td>Flores</td>
                    </tr>
                    <tr>
                        <td>Tgl.Lahir :</td>
                        <td>05 januari 2005</td>
                    </tr>
                    <tr>
                        <td>Agama :</td>
                        <td>Katolik</td>
                    </tr>
                    <tr>
                        <td>Alamat :</td>
                        <td>Manggarai </td>
                    </tr>
                    <tr>
                        <td>Email :</td>
                        <td><a href="mailto:erlinsinarti@gmail.com">erlinsinarti@gmail.com</a></td>
                    </tr>
                    <tr>
                        <td>No.HP :</td>
                        <td>081241011009</td>
                    </tr>
                    <tr>
                        <td>Website :</td>
                        <td><a href="https://arcomteknologi.id">arcomteknologi.id</a></td>
                    </tr>
                </table>
            </div>
        </div>

        <div class="pendidikan">
            <h2>Pendidikan</h2>
            <ul>
                <li>2011 - 2017 SDI Lenda</li>
                <li>2017 - 2020 SMP NEGERI SATAP Wae Ratun</li>
                <li>2020 - 2023 SMAK Negeri 1 Borong</li>
                <li>2023 - selesai Institut Bisnis dan Teknologi Indonesia</li>
            </ul>
        </div>

        <div class="pengalaman">
            <h2>Pengalaman Kerja</h2>
            <ul>
                <li>2017 - 2019 - Back-End Developer - di PT. Teknologi Indonesia</li>
                <li>2020 - Now - Full Stack Developer - di PT. BOX Tech AI Indonesia</li>
            </ul>
        </div>

        <div class="keahlian">
            <h2>Keahlian</h2>
            <ul>
                <li>Memasak</li>
                <li>Mebaca novel</li>
                <li>Maraton Drakor dan Dracin</li>
            </ul>
        </div>
    </div>
</body>
</html>
