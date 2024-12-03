### @selxyzz/play 
---

# Instalisasi
- Anda Dapat Menginstall Module Ini Dengan Cara Berikut:
```bash
npm install @selxyzz/play
```
---

# Penggunaan
- Anda Dapat Menggunakan Module Ini Untuk Melakukan Search & Download Atau Langsung Melakukan Kedua Nya. 
- Berikut Adalah Code Untuk Melakukan Search Saja:
```js
const { searchYT } =require('@selxyzz/play')

(async () => {
const play = await searchYT('selxyzz') 
if (play === 0) {
 console.log('Tidak Ada Result Untuk Pencarian Ini.') 
} else {
console.log(play) 
}
})()
```
- Berikut Adalah Code Untuk Melakukan Download.:
```js
const { ytdlClone } =require('@selxyzz/play')

(async () => {
const play = await ytdlClone('selxyzz') 
if (play === 0) {
 console.log('Tidak Ada Result') 
} else {
console.log(play) 
}
})()
```
- Berikut Adalah Contoh Code Untuk Melakukan Kedua Nya.:
```js
const { play } =require('@selxyzz/play')

(async () => {
const play = await play('selxyzz') 
if (play === 0) {
 console.log('Tidak Ada Result') 
} else {
console.log(play) 
}
})()
```
---


# Contributors 
- Programmer Yang Membantu Project Module Ini Adalah
- [`Selxyzz`](https://wa.me/6282181938329) 
---

Thanks For Using My Module. 
> Selxyz