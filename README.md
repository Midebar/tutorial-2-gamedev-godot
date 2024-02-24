
1. Apa saja pesan log yang dicetak pada panel Output?
Reached objective

2. Coba gerakkan landasan ke batas area bawah, lalu gerakkan kembali ke atas hingga hampir menyentuh batas atas. Apa saja pesan log yang dicetak pada panel Output?
Reached objective

3. Buka scene MainLevel dengan tampilan workspace 2D. Apakah lokasi scene ObjectiveArea memiliki kaitan dengan pesan log yang dicetak pada panel Output pada percobaan sebelumnya?
Node objectivearea pada scene pada MainLevel memiliki hubungan dengan log yang dicetak pada output, yaitu jika objek pesawat mencapai area objektif, maka akan dicetak "Reached Objective" pada output.

4. Scene BlueShip dan StonePlatform sama-sama memiliki sebuah child node bertipe Sprite. Apa fungsi dari node bertipe Sprite?
Sprite berfungsi untuk memperlihatkan icon/image dari objek yang dipilih

5. Root node dari scene BlueShip dan StonePlatform menggunakan tipe yang berbeda. BlueShip menggunakan tipe RigidBody2D, sedangkan StonePlatform menggunakan tipe StaticBody2D. Apa perbedaan dari masing-masing tipe node?
Staticbody2d merupakan tipe objek yang tidak terkena efek physics 2d, tetapi bisa dicollide, sedangkan rigidbody2d terkena efek physics 2d, tetapi tidak deform seperti softbody2d.

6. Ubah nilai atribut Mass dan Weight pada tipe RigidBody2D secara bebas di scene BlueShip, lalu coba jalankan scene MainLevel. Apa yang terjadi?
F = m * a, maka gaya newton yang diapplied lebih besar, sedangkan percepatan tetap sama, yaitu percepatan gravitasi bumi, jika disimulasikan pada bumi.

7. Ubah nilai atribut Disabled pada tipe CollisionShape2D di scene StonePlatform, lalu coba jalankan scene MainLevel. Apa yang terjadi?
Tidak ada collision yang terjadi, sehingga pesawat jatuh melewati platform.

8. Pada scene MainLevel, coba manipulasi atribut Position, Rotation, dan Scale milik node BlueShip secara bebas. Apa yang terjadi pada visualisasi BlueShip di Viewport?
Icon Blueship menjadi besar sesuai dengan scale, berubah rotasi sesuai dengan rotation, dan posisi pada viewport dan gamenya berubah sesuai dengan position

9. Pada scene MainLevel, perhatikan nilai atribut Position node PlatformBlue, StonePlatform, dan StonePlatform2. Mengapa nilai Position node StonePlatform dan StonePlatform2 tidak sesuai dengan posisinya di dalam scene (menurut Inspector) namun visualisasinya berada di posisi yang tepat?
Posisi child nodenya mengikuti poisis relatif parent nodenya sehingga, posisi parentnya sudah benar posisi child nodenya dimulai dari x dan y dari parent node tersebut