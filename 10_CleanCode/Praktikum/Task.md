Problem 1

Pada baris code berikut

![var](https://user-images.githubusercontent.com/96731433/157476863-2ea7a377-e4da-41fd-8791-ea680175ce2c.PNG)

dapat membuat multi string menjadi satu line saja, antara lain sebagai berikut :

**class user {
	var id, username, password;
}**

Dapat menggunakan CamelCase pada nama class

![camel](https://user-images.githubusercontent.com/96731433/157477496-2f5f92f1-6d68-40fb-8cad-a2e703588d10.PNG)

menjadi seperti berikut :

**class userService {
	user[] users = [];

	user[] getallUsers() {
		return users;
	}

	user getuserbyId(userid) {
		return users.filter(userid);
	}
}**

Problem 2
Code pada task berikut masi terdapat beberapa kesalahan

![prob2](https://user-images.githubusercontent.com/96731433/157478002-89413c55-a664-4265-a9ed-a886bebc2586.PNG)

Beberapa hal yang menurut saya harus diperbaiki :
Dapat menggunakan construstor supaya menyimpan variabel global nya dalam constructor
Dapat menggunakan "This" untuk mengakses variabel globalnya
Lebih baik menggunakan bahasa inggris, karena merupakan bahasa yang universal
Menggunakan Camel Case pada setiap penamaan class
Dapat menggunakan komentar untuk beberapa blok saja

Berikut code yang telah saya perbaiki :

**class Vehicle {
                constructor() {
                    this.wheels = 0
                    this.rpm = 0
                }
            }

            class Car extends Vehicle {
            	run() {
            		this.addspeed(10);
            	}
            	addspeed(newspeed) {
            		this.rpm = this.rpm + newspeed;
            	}
            }
            //deklarasi function 
            function main() {
            	let fastcar = new Car();
            	fastcar.run();
            	fastcar.run();
            	fastcar.run();

            	let slowcar = new Car();
            	slowcar.run();
            }

            main();**
