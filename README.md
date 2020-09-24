# DFS-BFS

## :triangular_flag_on_post: Tentang repo
Repo ini berisi kode program dalam bahasa python yang menerapkan penggunaan algoritma DFS (Depth First Search) dan BFS (Breadth First Search) dalam permasalahan mencari jalur dari titik A ke titik B dalam labirin. Ada dua kode program yang identik yaitu **maze.py** dan **mymaze.py**. **maze.py** adalah kode program yang menjadi referensi saya (sumber: course introduction to AI with python lecture: Search). Di **mymaze.py** saya menambahkan komentar dalam bahasa Indonesia yang merupakan catatan saya ketika memahami program.

## :grey_question: Algoritma DFS dan BFS
Jika kamu belum mengerti tentang algoritma DFS dan BFS kamu bisa melihat video ini. **Perlu dicatat! video dibawah akan menerangkan menggunakan Graph, bagaimanapun algoritma ini bisa digunakan di Tree**

[![DFS](http://i3.ytimg.com/vi/Y40bRyPQQr0/hqdefault.jpg)](https://www.youtube.com/watch?v=Y40bRyPQQr0)
[![BFS](http://i3.ytimg.com/vi/0u78hx-66Xk/hqdefault.jpg)](https://www.youtube.com/watch?v=0u78hx-66Xk&t=65s)

## :sparkles: Hal yang keren di program ini
Jika kamu menjalankan program ini kamu akan mendapatkan gambar yang menunjukkan solusi dari masalah.

Kamu bisa mengganti nama gambar yang akan dihasilkan dengan mengubah parameternya.
```python
m.output_image("ganti_nama_file.png")
```

Defaultnya gambar yang dihasilkan hanya menampilkan state solusi saja, seperti ini :arrow_down:
![gambar default](https://github.com/nardiyansah/DFS-BFS/blob/master/maze.png)

Tapi kamu bisa melihat state yang telah dieksplor dengan menambahkan parameter :arrow_down:
```python
m.output_image("ganti_nama_file.png", show_explored=True)
```
![gambar explore](https://github.com/nardiyansah/DFS-BFS/blob/master/maze_explore.png)
