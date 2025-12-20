File bisa ditambahkan ke github dengan cara pertama perubahan file yg dibuat di dorong ke ruang tunggu dulu pakai kode git add. (enter) yg di source control akan berubah jd staged changes artinya masuk ruang tunggu, kemudian pakai kode git commit -m "Isi message" (enter), yang dimana perubahan akan ke up ke akun masing masing, -m artinya message, lalu klik publish branch yg nanti bisa pilih private atau public (enter) lalu selesai ke up. Jika isi file yg telah di up ingin ditambah, file di vscode bisa ditambah dulu, lalu langkah langkah diulang dari git add . yang bisa pakai shortcut tanda + di atas file name source control, lalu gir commit -m "" bisa pakai shortcut tombol commit serta isi message dulu, dan untuk git push nya bisa pakai shortcut tombol sync changes. 

Jika di file yg telah di up ada diedit oleh orang, untuk mengambil perubahan yang ada editan org tersebut bisa pakai kode git fetch (enter) git pull (enter) atau jika ingin mudah, bisa klik logo siknron di sebelah tulisan server main di bawah

untuk melihat perubahan apa saja yang telah terjadi di sistem kita bisa pakai kode git log

jika ingin meng cloning repository orang lain ke laptop kita, pertama buat folder baru, kemudian ambil kode dari repository yg ingin di clone di tombol <>code lalu local dan https dan salin link, lalu balik ke vscode dengan kode git clone *link yang disalin*(enter)

Jika ingin memberi tahukan sesuatu ke pemilik repository, bisa sampaikan lewat issue

jika sebuah repositori ingin di edit banyak orang, kita bisa menggunakan branch agar file nya ketika di push tidak bentrok, caranya dari issue yg dibuat, scroll ke bawah create a new branch dan salin perintah dari github untuk pindah server dari main pakai kode git fetch origin (enter) git checkout nama server baru

jika kita sudah menambah file baru di server baru dengan cara yang sama diatas, kita bisa gabungkan ke branch utama dengan compare and pull request di github lalu create pull request lalu merge pull request setelah di confirm github, lalu perubahan tsb sudah ada di main branch dan kita bisa hapus branch kita

lalu di github juga ada projects yang fungsinya untuk mengorganisir issue yang jumlahnya banyak agar bisa terkontrol