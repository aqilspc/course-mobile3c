Rangkuman pertemuan 4 (Naily Ikmalul Insiyah - 16)
- Pembahasan tentang Recycler View
- Setiap tampilan ada data yang divisualisasikan 
- RecyclerView memudahkan untuk menampilkan kumpulan data dalam jumlah besar secara efisien
- Demo aplikasi hutang
- Langkah2: membuat layout (menambahkan 2 text view), membuat package (modul dan adapter), membuat class (Hutang), membuat adapter, membuat layout recycle view, dan menerapkan Adapter dan ViewHolder
- Recycler view -> dataset yang digunakan untuk menyimpan kumpulan model
- import -> alt+enter
- mengetahui jumlah item item.size()
- Menggunakan size karena berupa data list
- view holder digunakan untuk merepresentasikan class adapter ke layout (Kita hubungkan text view melalui id)
- Saat menentukan adaptor, Anda perlu mengganti tiga metode utama: onCreateViewHolder, onBindViewHolder, dan getItemCount
- OnBind -> memastikan data apa saja yang ada (items.get(position))
- Library RecyclerView menyediakan tiga pengelola tata letak, yaitu: LinearLayoutManager, GridLayoutManager, dan StaggeredGridLayoutManager
- membuat nama -> control+space
- Recycle view membutuhkan adapter
- Untuk membuat data dami di Main activity, kita menggunakan arraylist
- Layout Inflater untuk membaca data layout xml
- Harus memahami proses pemodelan dan penampilan data
- Yang mengatur tampilan (misal horizontal, vertikal) adalah layout manager
- Pada list view pemakaian view holder boleh tidak digunakan
