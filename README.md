# Pemodelan-GJB-menggunakan-Excel
Pada praktikum ini akan dibuat percobaan untuk membuat pemodelan gerak jatuh bebas menggunakan VBA excel. Jadi dengan VBA excel pada praktikum ini, dapat dibuat sebuah tombol yang otomatis untuk menggerakkan benda jatuh bebas dan grafik. 
Link youtube : https://youtu.be/aowqd1rYKVY
Codingan :
Private Sub Start_Click()
Range("B12").Value = 0 '0
delta_t = Range("B8").Value '0.1
While Range("B12").Value < 9
Range("B12").Value = Range("B12").Value + delta_t
DoEvents
Wend
End Sub

