# Tugas-algoritma-Kelompok-12  
 **Agesti Rahmi Gusmita   1251170016 (sebagai Project Manager)**  
 **Widya Cahyaning Ababil 1251170067 (sebagai Developer)**  
 **Salsa Amanatussaadah   1251170018 (sebagai system analysis)**  

 BEGIN  
 INPUT n = 300 (jumlah dompet)  
 INPUT t = 3 detik (waktu cek per dompet)  
 INPUT k = 150  

 COMPUTE t_bestcase = 3 
 COMPUTE t_worstcase = 900
 COMPUTE langkah_avg = 150
 COMPUTE t_average = 451,5

 OUTPUT "======================================"  
 OUTPUT judul "ANALISIS PERCEPATAN PENCARIAN KTM (LINEAR SEARCH)"  
 OUTPUT "======================================="
 OUTPUT parameter studi kasus:  
    - Jumlah Dompet dalam tumpukan = 300  
    - Waktu pengecekan per dompet = 3 detik  
    - Posisi KTM yang dicari = dompet ke-150 
OUTPUT"========================================="

OUTPUT header tabel:  
      Urutan (k) | Waktu t (k) | Selisih best | Speedup vs Worst | speed vs avg  
OUTPUT "========================================"  

FOR i = 1 TO 300 DO  
  COMPUTE t_k = i * 3  
  COMPUTE t_selisihbestwaktu = (i - 1) * 3
  COMPUTE t_vsworstcase = 300 / i   
  COMPUTE t_vsaverage = 301 / (2 * i)  

  IF i == 150 THEN  
      SET keterangan = 150 (ktm) 
  ELSE  
      SET keterangan =  
  ENDIF  
  
  OUTPUT baris tabel dengan nilai i, t_k, t_selisihbestwaktu, t_vsworstcase, t_vsaverage, dan keterangan  
END FOR  

OUTPUT "================================" 
OUTPUT " RINGKASAN ANALISIS KASUS "  
OUTPUT "==============================="
OUTPUT hasil ringkasan :  
    - Best Case = t_bestcase 3 detik (langkah 1)  
    - Worst Case = t_worstcase 900 detik (langkah 300)  
    - Average Case = t_average 226,5 detik (langkah 150)  
    - Selisih Waktu = 897 
    - Percepatan Best Worst = 300x 
    - Percepatan Best Avg = 150x
OUTPUT"=============================="  

END 
