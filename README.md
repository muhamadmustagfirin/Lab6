# Lab6
Modul praktikum 6 ini berisikan latihan menggunakan dictionary pada python, dan juga praktikum membuat Program Daftar Nilai Mahasiswa menggunakan dictionary dan juga menampilkan pilihan menu antara lain: Ubah, Tambah, Hapus, Cari, Lihat!

# Latihan 


### Latihan yang pertama adalah membuat daftar keluar masuk mahasiswa dengan menggunakan dictionary pada python
- berikut source code nya:
```python
datakeluarmasukmahasiswa = {"nama":"nim"}
nim = {'Jono':'312110989', 'Arum':'312118986'}

print("      Daftar Mahasiswa    ")
print("="*30)
print("   nama     |       nim   ")
print("="*30)
print("   Jono     |   ",nim['Jono'])
print("   Arum     |   ",nim['Arum'])
print("="*30)

print("Menampilkan Data Arum")
print("="*21)
print("  Arum  | ",nim['Arum'])
print("="*21)

print("Menambah Data Rahmat dan Nim 312110189")
nim['Rahmat']='312110189'
print("="*38)
print("     Rahmat      |      ",nim['Rahmat'])
print("="*38)

print("Mengubah Nim Jono dengan nim baru 312189098")
nim['Jono']='312189098'
print("="*43)
print("        Jono        |       ",nim['Jono'])
print("="*43)

print("Menampilkan semua nama mahasiswa yang masuk")
print("="*44)
print(nim.keys())
print("="*44)

print("     Menampilkan semua nim mahasiswa yang masuk    ")
print("="*52)
print(nim.values())
print("="*52)

print("                       Menampilkan daftar nama dan nim                      ")
print("="*83)
print(nim.items())
print("="*83)

print("        Hapus data mahasaiswa keluar      ")
nim.pop('Arum')
print("="*60)
print(nim.items())
print("="*60)
```

Dengan penjelasan source code sebagai berikut:
- Dibawah ini adalah untuk menampung data dari dictionary

```python
datakeluarmasukmahasiswa = {"nama":"nim"}
nim = {'Jono':'312110989', 'Arum':'312118986'}
```

- Sedangkan code dibawah adalah untuk mengakses atau menampilkan nim yang telah ditampung dalam data dictionary tersebut

```python
print("      Daftar Mahasiswa    ")
print("="*30)
print("   nama     |       nim   ")
print("="*30)
print("   Jono     |   ",nim['Jono'])
print("   Arum     |   ",nim['Arum'])
print("="*30)
```
- berikut hasil programnya:

![gambar1](ssanlatihan/ssan1.png)

