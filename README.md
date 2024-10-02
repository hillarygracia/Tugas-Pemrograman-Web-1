# Tugas-Pemrograman-Web
Membuat Form Registrasi
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Registrasi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .container {
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table td {
            padding: 10px;
            vertical-align: middle;
        }
        input[type="text"], input[type="password"], input[type="date"], input[type="file"], select {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Form Registrasi</h2>
    <form action="#" method="post" enctype="multipart/form-data">
        <table>
            <tr>
                <td><label for="first_name">Nama Depan:</label></td>
                <td><input type="text" id="first_name" name="first_name" required></td>
            </tr>
            <tr>
                <td><label for="last_name">Nama Belakang:</label></td>
                <td><input type="text" id="last_name" name="last_name" required></td>
            </tr>
            <tr>
                <td><label for="address">Alamat:</label></td>
                <td><input type="text" id="address" name="address" required></td>
            </tr>
            <tr>
                <td><label for="dob">Tanggal Lahir:</label></td>
                <td><input type="date" id="dob" name="dob" required></td>
            </tr>
            <tr>
                <td><label for="gender">Jenis Kelamin:</label></td>
                <td>
                    <select id="gender" name="gender" required>
                        <option value="Laki-laki">Laki-laki</option>
                        <option value="Perempuan">Perempuan</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td><label for="username">Username:</label></td>
                <td><input type="text" id="username" name="username" required></td>
            </tr>
            <tr>
                <td><label for="password">Password:</label></td>
                <td><input type="password" id="password" name="password" required></td>
            </tr>
            <tr>
                <td><label for="photo">Unggah Foto:</label></td>
                <td><input type="file" id="photo" name="photo" accept="image/*" required></td>
            </tr>
            <tr>
                <td colspan="2">
                    <input type="submit" value="Daftar">
                </td>
            </tr>
        </table>
    </form>
</div>

</body>
</html>
