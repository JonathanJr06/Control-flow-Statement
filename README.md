# Control-flow-Statement
Tugas PBO (3)


#Data Diri

from encodings import utf_8_sig


nama = input("Nama Mahasiswa : ")
nim = input("Masukkan NIM : ")
jenis_kelamin = input("Masukkan jenis kelamin anda : ")
nama_matakuliah = input("Masukkan Nama Matakuliah yang anda tuju : ")
tanggal_input_nilai = input("Masukkan Tanggal : ")
absensi = input("Masukkan absensi anda : ")

nilai_tugas = int(input("Masukkan Nilai Tugas anda : "))
if nilai_tugas == 80-100:
    print ("A" "LULUS")
elif nilai_tugas == 77-78:
    print ("A+" "LULUS")
elif nilai_tugas == 74-77:
    print ("A-" "LULUS")
elif nilai_tugas == 71-74:
    print ("B+" "LULUS")
elif nilai_tugas == 68-71:
   print ("B-" "LULUS")
elif nilai_tugas == 64-68:
    print ("C+" "LULUS")
elif nilai_tugas == 60-64:
   print ("C-" "TIDAK LULUS")
elif nilai_tugas == 50-59:
    print ("D" "TIDAK LULUS")
elif nilai_tugas == 0-49:
   print ("E" "TIDAK LULUS")
else :
    print ("KETERANGAN : LULUS")

nilai_uts = input("Mauskkan nilai UTS anda : ")
if nilai_uts == 80-100:
    print ("A" "LULUS")
elif nilai_uts == 77-78:
    print ("A+" "LULUS")
elif nilai_uts == 74-77:
    print ("A-" "LULUS")
elif nilai_uts == 71-74:
    print ("B+" "LULUS")
elif nilai_uts == 68-71:
   print ("B-" "LULUS")
elif nilai_uts == 64-68:
    print ("C+" "LULUS")
elif nilai_uts == 60-64:
   print ("C-" "TIDAK LULUS")
elif nilai_uts == 50-59:
    print ("D" "TIDAK LULUS")
elif nilai_uts == 0-49:
   print ("E" "TIDAK LULUS")
else :
    print ("KETERANGAN : LULUS")


nilai_uas = input("Masukkan nilai UAS anda : ")
if nilai_uas == 80-100:
    print ("A" "LULUS")
elif nilai_uas == 77-78:
    print ("A+" "LULUS")
elif nilai_uas == 74-77:
    print ("A-" "LULUS")
elif nilai_uas == 71-74:
    print ("B+" "LULUS")
elif nilai_uas == 68-71:
   print ("B-" "LULUS")
elif nilai_uas == 64-68:
    print ("C+" "LULUS")
elif nilai_uas == 60-64:
   print ("C-" "TIDAK LULUS")
elif nilai_uas == 50-59:
    print ("D" "TIDAK LULUS")
elif nilai_uas == 0-49:
   print ("E" "TIDAK LULUS")
else :
    print ("KETERANGAN : LULUS")


nilai_akhir = input("Masukkan nilai Akhir anda : ")
if nilai_akhir == 80-100:
    print ("A" "LULUS")
elif nilai_akhir == 77-78:
    print ("A+" "LULUS")
elif nilai_akhir == 74-77:
    print ("A-" "LULUS")
elif nilai_akhir == 71-74:
    print ("B+" "LULUS")
elif nilai_akhir == 68-71:
   print ("B-" "LULUS")
elif nilai_akhir == 64-68:
    print ("C+" "LULUS")
elif nilai_akhir == 60-64:
   print ("C-" "TIDAK LULUS")
elif nilai_akhir == 50-59:
    print ("D" "TIDAK LULUS")
elif nilai_akhir == 0-49:
   print ("E" "TIDAK LULUS")
else :
    print ("KETERANGAN : LULUS")


print ("Terimakasiih atas waktunya",nama,nim,"Pada Tanggal",tanggal_input_nilai,"Pada Matakuliah",nama_matakuliah)
