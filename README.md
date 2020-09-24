# Greedy Best-First Search

## :triangular_flag_on_post: Tentang repo
Repo ini berisi kode program dalam bahasa python yang menerapkan penggunaan algoritma Greedy Best-First Search dalam permasalahan mencari jalur dari titik A ke titik B dalam labirin.

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
