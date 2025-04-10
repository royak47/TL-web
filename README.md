## TeraDL - Terabox File Downloader & Video Streaming

<div style="text-align:justify; line-height:1.3;"><b>TeraDL</b> adalah platform untuk streaming video atau mengunduh file Terabox secara gratis dan cepat, yang diciptakan agar pengguna tidak perlu menginstall aplikasi Terabox terlebih dahulu, tapi hanya dengan memasukkan url, kemudian file siap diunduh.</div>

<br>

<p align="left" style="max-height: 100%;">
    <a href="https://github.com/Dapunta/TeraDL/stargazers"><img src="https://img.shields.io/github/stars/Dapunta/TeraDL?style=for-the-badge&color=ff0000" alt="Stars" style="max-height: 100%;"></a>
    <a href="https://github.com/Dapunta/TeraDL/network/members"><img src="https://img.shields.io/github/forks/Dapunta/TeraDL?style=for-the-badge&color=9f9f00" alt="Forks" style="max-height: 100%;"></a>
    <a href="https://github.com/Dapunta/TeraDL/commits"><img src="https://img.shields.io/github/commit-activity/t/Dapunta/TeraDL?style=for-the-badge&color=008800" alt="Commits" style="max-height: 100%;"></a>
    <a href="https://github.com/Dapunta/TeraDL"><img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FDapunta%2FTeraDL&label=visitors&countColor=%230055ff" alt="Visitors" style="max-height: 100%;"></a>
</p>

### Informasi

<table style="border-collapse: collapse;">
    <tr>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">Version</td>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">1.5.5</td>
    </tr>
    <tr>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">Website</td>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;"><a href="https://teradl.dapuntaratya.com">TeraDL</a></td>
    </tr>
    <tr>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">API</td>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;"><a href="https://teradl-api.dapuntaratya.com">TeraDL API</a></td>
    </tr>
    <tr>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">API Doc</td>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;"><a href="https://github.com/Dapunta/TeraDL/tree/main/api">Documentation</a></td>
    </tr>
    <tr>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">Author</td>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;"><a href="https://www.facebook.com/Dapunta.Khurayra.X">Dapunta Khurayra X</a></td>
    </tr>
    <tr>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">Status</td>
        <td style="border: 1px solid transparent; line-height:1.3; padding: 0px;">Open Source (Full)</td>
    </tr>
</table>

### Screenshot

<table style="border-collapse: collapse; width: 100%; max-width: 800px; table-layout: fixed;">
    <tr>
        <td style="border: 1px solid transparent; padding: 5px; text-align: center;">
            <img src="assets/screenshot1.png" alt="Image" style="width: 100%; height: auto;">
        </td>
        <td style="border: 1px solid transparent; padding: 5px; text-align: center;">
            <img src="assets/screenshot2.png" alt="Image" style="width: 100%; height: auto;">
        </td>
        <td style="border: 1px solid transparent; padding: 5px; text-align: center;">
            <img src="assets/screenshot3.png" alt="Image" style="width: 100%; height: auto;">
        </td>
    </tr>
</table>

### TechStack

<table style="border-collapse: collapse; width: 100%;">
    <tr>
        <td style="text-align: left; vertical-align: middle; padding: 8px;">
            <strong>Backend</strong>
        </td>
        <td style="vertical-align: middle; padding: 8px;">
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
        </td>
    </tr>
    <tr>
        <td style="text-align: left; vertical-align: middle; padding: 8px;">
            <strong>Frontend</strong>
        </td>
        <td style="vertical-align: middle; padding: 8px;">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
        </td>
    </tr>
</table>

<br>

### Changelog

<br>

- **Apa Yang Baru Di Versi 1.5?**
    - Perbaikan bug tidak bisa download & streaming
    - Menggunakan service dari [`hnn`](https://terabox.hnn.workers.dev/) untuk mendapatkan url download
    - Menggunakan `Terabox Proxy` untuk streaming video
    - Tampilan UI baru

    <br>

- **Apa Yang Baru Di Versi 1.4?**
    - Fitur streaming video secara langsung
    - Support download berbagai format file
        - Video : `.mp4`, `.mov`, `.mkv`, `.m4v`, `.asf`, `.avi`, `.wmv`, `.m2ts`, `.3g2`
        - Gambar : `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.svg`
        - Lainnya : `.pdf`, `.docx`, `.zip`, `.rar`, `.7z`

    <br>

- **Apa Yang Baru Di Versi 1.3?**
    - Penambahan mode baru *(`get link` dengan `cookies` dari sisi server)* sehingga URL download lebih awet, meminimalisir error, dan proses download menjadi lebih cepat
        - **Mode 1** : Menggunakan cookies dynamic yang didapat dari scrap secara real time
        - **Mode 2** : Menggunakan cookies static dari admin (sesi login akun admin)
    - Auto switch mode jika `cookies` dari sisi server invalid

    <br>

- **Apa Yang Baru Di Versi 1.2?**

    - [TeraDL](https://teradl.dapuntaratya.com/) adalah project lanjutan dari [TeraStream](https://terastream.dapuntaratya.com/)
    - Perbaikan `get file` yang sebelumnya error
    - Perubahan logika pemrograman untuk `get file` dan `get link` sehingga proses loading lebih cepat
    - Perubahan tampilan menjadi lebih sederhana dan agar terkesan lebih menarik

<br>

### Catatan

> [!TIP]  
> Jika ingin menjalankan di local, pastikan `flask_app.py` sudah di-run  
> Lalu jalankan *live-server* atau *localhost* pada `index.html`

> [!WARNING]  
> Platform ini hanya berfungsi untuk link yang berkaitan dengan Terabox  
> Contoh : `1024terabox`, `freeterabox`, `nephobox`, dan lainnya

> [!CAUTION]  
> Jangan abuse, gunakan sewajarnya !  
> Segala tindakan adalah tanggung jawab pengguna  