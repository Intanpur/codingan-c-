Function dalam bahasa pemrograman C++ adalah sebuah blok kode program yang ditulis
untuk melakukan suatu tindakan tertentu atau mengembalikan nilai tertentu ketika
dipanggil dari program utama atau dari fungsi lainnya. Function juga dapat menerima
parameter sebagai input, sehingga memungkinkan kita untuk memasukkan nilai atau
data ke dalam function untuk diolah atau diproses.
//codingan mengenai gabungan fungsi pointer cstring dan class


#include <iostream>
#include <cstring>

using namespace std;

// Class Mahasiswa
class Mahasiswa {
    private:
        char* nama;
        int umur;
    public:
        Mahasiswa(char* n, int u) {
            nama = new char[strlen(n) + 1];
            strcpy(nama, n);
            umur = u;
        }
        ~Mahasiswa() {
            delete[] nama;
        }
        void display() {
            cout << "Nama: " << nama << endl;
            cout << "Umur: " << umur << endl;
        }
};

// Fungsi utama
int main() {
    // Membuat pointer ke objek Mahasiswa
    Mahasiswa* mhs;

    // Mengalokasikan memori untuk objek Mahasiswa
    mhs = new Mahasiswa("Ahmad", 20);

    // Memanggil metode display
    mhs->display();

    // Menghapus objek Mahasiswa
    delete mhs;

    return 0;
}
//Program di atas menggunakan class Mahasiswa yang memiliki dua atribut yaitu nama dan umur. Atribut nama menggunakan tipe data char* dan diinisialisasi menggunakan //fungsi new untuk mengalokasikan memori. Fungsi strcpy digunakan untuk menyalin nilai dari string yang diinput ke dalam atribut nama. Fungsi new dan delete digunakan //untuk mengalokasikan dan menghapus memori yang digunakan untuk objek Mahasiswa.

//Program ini menggunakan pointer untuk mengakses objek Mahasiswa. Pointer mhs diinisialisasi dengan new dan diisi dengan alamat memori objek Mahasiswa yang baru //dibuat. Pointer digunakan untuk memanggil metode display pada objek Mahasiswa. Setelah selesai digunakan, objek Mahasiswa dihapus menggunakan delete.
