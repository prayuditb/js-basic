#Prayudi

##array.js
###arrMembers = ['one','two',,'three',];
it's define new array variable called arrMembers
###console.log(arrMembers[0]);
it's show the value of arrMembers with index number 0 and the value is 'one'
###console.log(arrMembers[2]);
it'show the "undefined" because the value of arrMembers with index number2 is undefined
###console.log(arrMembers[3]);
it's show the value of arrMembers with index number 3 and the value is 'three'
###console.log(arrMembers[4]);
it'show the "undefined" because the value of arrMembers with index number 4 is undefined
###console.log(arrMembers.length);
it's show the total index of arrMembers
###multiArray
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
<code>
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
</code>
when 'continue' executed, the loop will continue to next iteration <br>
and when the 'break' executed, the loop will be stopped.<br>

##breakWithLabel.js
<code>
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
</code>
The break statement will stop the iteration of first 'for' loop labeled with topLabel

##const.js
<code>
const MENU = "Home";

console.log("Posisi menu = " + MENU);

// mencoba mengisi MENU. berhasil?

MENU = "About";

console.log("Posisi menu = " + MENU);

// Posisi menu = Home
// Posisi menu = Home
</code>
the const can not be change after its defined, changing the value of const can make an error
