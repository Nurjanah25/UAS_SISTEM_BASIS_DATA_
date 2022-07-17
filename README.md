### UJIAN AKHIR SEMESTER

Nama : Nurjanah

NIM : 312010035

Kelas : TI.20.D.1

Matkul : Sistem Basis Data

Dosen : Muhammad Najamuddin Dwi Miharja, S.Kom, M.kom

# Membuat Sistem Informasi Klinik.

* tampilan login
![image](https://user-images.githubusercontent.com/101665497/179379200-c4c62799-42b7-4362-9aac-92b6334f73fa.png)

* tampilan daa pasien
![image](https://user-images.githubusercontent.com/101665497/179379220-59b63144-2bd0-4827-b3b7-f4dc12b5ecc6.png)

* tapilan data dokter
![image](https://user-images.githubusercontent.com/101665497/179379252-9349f13a-8be1-44c9-871f-e13b405e8789.png)

* tampilan data obat
![image](https://user-images.githubusercontent.com/101665497/179379295-4928cd9b-5eb0-4b1b-bf34-d6522251e391.png)

* tampilan data user
![image](https://user-images.githubusercontent.com/101665497/179379318-63adf456-6110-4d87-ac1d-8113ffc977d9.png)

* Implementasi Fungsi.
Mengimplementasikan Fungsi untuk menampilkan total data :

CREATE FUNCTION fn_totalUsers() RETURNS INT(11) UNSIGNED NOT DETERMINISTIC NO SQL SQL SECURITY DEFINER RETURN (SELECT COUNT(id_pasien) FROM pasien)
![image](https://user-images.githubusercontent.com/101665497/179379393-3bb92689-b632-471e-8377-d263e2878621.png)

