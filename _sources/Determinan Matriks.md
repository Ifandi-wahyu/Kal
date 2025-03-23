# Determinan Matriks

## Determinan Matriks
Determinan suatu matriks adalah nilai skalar yang dihitung dari elemen-elemen matriks tersebut. Determinan digunakan dalam berbagai bidang matematika, termasuk dalam menyelesaikan sistem persamaan linear, menemukan invers matriks, dan banyak lagi.

### Minor Matriks
Minor dari elemen \(a_{ij}\) dalam matriks adalah determinan dari submatriks yang diperoleh dengan menghapus baris ke-\(i\) dan kolom ke-\(j\) dari matriks asal.

### Kofaktor Matriks
Kofaktor dari elemen \(a_{ij}\) adalah minor elemen tersebut dikalikan dengan faktor tanda:
\[
C_{ij} = (-1)^{i+j} M_{ij}
\]
dengan \(M_{ij}\) adalah minor dari elemen \(a_{ij}\).

### Mencari Determinan dengan Konsep Minor dan Kofaktor Matriks
Determinan dapat dihitung dengan ekspansi kofaktor pada baris atau kolom tertentu. 

#### Contoh Matriks 3×3
Misalkan kita memiliki matriks:

$$
A = 
\begin{bmatrix} 
1 & 2 & 3 \\ 
4 & 5 & 6 \\ 
7 & 8 & 9 
\end{bmatrix}
$$

Determinan dihitung sebagai:
$$
det(A) = 1 \cdot \begin{vmatrix} 5 & 6 \\ 8 & 9 \end{vmatrix} - 2 \cdot \begin{vmatrix} 4 & 6 \\ 7 & 9 \end{vmatrix} + 3 \cdot \begin{vmatrix} 4 & 5 \\ 7 & 8 \end{vmatrix}
$$

#### Contoh Matriks 4×4
$$
B = 
\begin{bmatrix} 
1 & 2 & 3 & 4 \\
5 & 6 & 7 & 8 \\
9 & 10 & 11 & 12 \\ 
13 & 14 & 15 & 16 
\end{bmatrix}
$$

Determinan dihitung dengan ekspansi kofaktor pada baris pertama.

#### Contoh Matriks 5×5
Perhitungan determinan untuk matriks 5×5 mengikuti pola yang sama dengan ekspansi kofaktor.

> **Catatan:** Proses perhitungan determinan untuk matriks besar lebih efisien menggunakan metode lain seperti eliminasi Gauss.
