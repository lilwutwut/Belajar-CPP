# Halo Semuanya

Ini adalah *Repositories* saya untuk menyimpan pembelajaran saya tentang Bahasa pemrograman C++, bisa ini kayak bukti sebenarnya saya belajar C++

Tujuan Saya Belajar C++ adalah untuk mempelajari _[Competitive programming](https://en.wikipedia.org/wiki/Competitive_programming)_ salah satu bahasa yang paling sering digunakan di *Competitive programming* adalah C++

C++ Adalah bahasa yang cepat sering digunakan dibagian low level, kernel bahkan *[Embedded system](https://en.wikipedia.org/wiki/Embedded_system)* karena di Embedded system, Resources yang terbatas di Embedded system itu adalah hal paling krusial 

So ini repo buat nyimpen source code C++ saya, Sesederhana itu

## Hello World
Hello world di C++ bisa ditulis sebagai berikut
```
#include <iostream>

int main() {
    std::cout << "Hello World";
}
```

atau mungkin teman teman lebih mengenal code yang seperti ini
```
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World";
}
```

Keduanya sama sama bisa jalan tak perlu khawatir soal itu :3

ok mari kita jelaskan fungsi masing masing kodenya

- Agar sebuah kode seperti `cout` berfungsi kita perlu memasukan `#include <iostream>`  bisa disebut sebagai library standar C++
  
-  `using namespace std;` berfungsi untuk mengotomatiskan penulisan langsung ke perintah tanpa tanda `std::` lagi, Tetapi jika anda didunia kerja disarankan untuk tidak menggunakan `using namespace std;` karena dikahawatirkan tentang masalah dengan module lainnya
  
-  `int main` bisa disebut sebagai fungsi utama, ini lah yang akan dijalankan pertama kali saat program dijalankan
