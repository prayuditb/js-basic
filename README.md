#Prayudi

##array.js
<pre>arrMembers = ['one','two',,'three',];</pre>
it's define new array variable called arrMembers
<pre>console.log(arrMembers[0]);</pre>
it's show the value of arrMembers with index number 0 and the value is 'one'
<pre>console.log(arrMembers[2]);</pre>
it'show the "undefined" because the value of arrMembers with index number2 is undefined
<pre>console.log(arrMembers[3]);</pre>
it's show the value of arrMembers with index number 3 and the value is 'three'
<pre>console.log(arrMembers[4]);</pre>
it'show the "undefined" because the value of arrMembers with index number 4 is undefined
<pre>console.log(arrMembers.length);</pre>
it's show the total index of arrMembers
multiArray
<pre>var multiArray = [
	['0-0','0-1','0-2'],
	['1-0','1-1','1-2'],
	['2-0','2-1','2-2']];</pre>
<br> It's define new two dimentional array called multiArray <br>
###console.log(multiArray[0][2]);
It's show the value of multiArray with index number 0 and 2. The value is '0-2'
###console.log(multiArray[1][2]);
It's show the value of multiArray with index number 1 and 2. The value is '1-2'

##boolean.js
###var isActive = true;
it's declare and define the new boolean variable called isActive with value true
###console.log("Current status: " + isActive);
It's show the sentence "Current status : " and the valueof isActive variable

##breakContinue.js
<pre>
var n = 0;
var x = 0;

while (n < 5) {
	n ++;
	x += n;

	if (x%2 == 0) {
		continue;
	};

	if (x>10) {
		break;
	};

	console.log("Nilai n = " + n);
	console.log("Nilai x = " + x);

};
</pre>
when 'continue' executed, the loop will continue to next iteration <br>
and when the 'break' executed, the loop will be stopped.<br>

##breakWithLabel.js
<pre>
topLabel:
	for(var k = 0; k < 10; k++){
		for(var m = 0; m < 20; m++){
			if(m == 5){
				console.log("Nilai k = " + k);
				console.log("Nilai m = " + m);
				break topLabel;
			}
		}
	}
</pre>
The break statement will stop the iteration of first 'for' loop labeled with topLabel

##const.js
<pre>
const MENU = "Home";

console.log("Posisi menu = " + MENU);

// mencoba mengisi MENU. berhasil?

MENU = "About";

console.log("Posisi menu = " + MENU);
</pre>
the const can not be change after its defined, changing the value of const can make an error

##doWhile.js
<pre>
var i = 0;
do {
	i += 2;
	console.log(i);
} while (i < 20);
</pre>
the statement in 'do' section will be executed before check the condition in while section.<br>
it's mean, the minimum iteration when using 'do while' is once.

##dynamic.js
<pre>
var jumlahMahasiswa = 30
console.log('Jumlah mahasiswa dalam satu kelas = ' + jumlahMahasiswa);
</pre>
the type of variable in javascript can be change automatically, such as the number chenged to string when its called by console.log()
##floatingPoint.js
<pre>
var fpPertama = 3.1415926,
    fpKedua = -.123456789,
    fpKetiga = -3.1E+12,
    fpKeempat = .1e-20;

console.log("fpPertama: " + fpPertama);
console.log("fpKedua: " + fpKedua);
console.log("fpKetiga: " + fpKetiga);
console.log("fpKeempat: " + fpKeempat);
</pre>
floating Point is the decimal fraction number and javascript can store it in variable without declare the type of variable. 
