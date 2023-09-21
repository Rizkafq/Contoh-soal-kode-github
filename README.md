# Contoh-soal-kode-github
import math

# Ketinggian awal (m)
h_awal = 20

# Ketinggian saat ini (m)
h_saat_ini = 15

# Percepatan gravitasi (m/s^2)
g = 10

# Menghitung kecepatan benda pada saat berada 15 m di atas tanah
v = math.sqrt(2 * g * (h_awal - h_saat_ini))

# Menampilkan hasil kecepatan
print(f"Kecepatan benda pada saat berada {h_saat_ini} m di atas tanah adalah {v} m/s")
