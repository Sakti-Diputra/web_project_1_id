#Poyek 3
Indonesia Web Proyek 3

Pada bagian header memutar header square 15 derajat berlawanan arah jarum jam, dengan menggunakan transform: rotate(-15deg);.

Untuk membuat animasi berputar secara penuh (360°) dalam 20 detik dan bergerak berulang-ulang dalam
satu pengulangan (loop) pada kotak di blok header dan segitiga di blok kaufman, menggunakan animation: loader 20s infinite; dan
@keyframes loader {
  0% {
    rotate: 0deg;
  }
  100% {
    rotate: 360deg;
  }
}