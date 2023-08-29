LECTURE -4
<>==>Angle brackets
()==>Parenthesis
{}== > Curly Braces, body, block of code
[]== > scare brackets 
void main(){
int number =123;
int roolnumber=1;
String name="ALI";
String fname="akram";
double smaic= 3434.2;
  bool ischeck = true;
  print(name);
  print(fname);
  print(smaic);
  print(ischeck);
  print (name.toLowerCase());
}	

void main(){  
 singal line comments 
   //this app stuctre 
    double line comments 
  /* this 
    is
    my
    app
   * / 
doucment comments     for file explanation 
   //this app structure   
}
Variables
Data types
1234		int number  = 123;   > integer
Akram		string  name=“Akram” ;    >string
4.555 		double gpi =34.2344;      >double
True false	bool is check =true;            > Boolean 

	
Late int b;
And
Late int b; 
Agr hum b ko use ni krty to memory use hoti
late lagany sy memory use ni ho gi	Late use for global – un nulable or initialized
(ager b red under line ha to late lgaain gy)
Int b=12; likh sakty hn
Global- void main(){ }body ky uper ya  nechy likha hova)

Local veriable- void main(){ }ky uner likha hova)
Late int b; ye late ky bager ni likh sakty
Initialized- void main(){ }ky uper likha hova)

LECTURE  =5
Int
String
Double
Bool
Dynamic	Statistic 
Variable names
Var	Integrated 
void main() {
  int number = 123;
  int roolnumber = 1;
  String name = "ALI";
  String fname = "akram";
  double smaic = 3434.2;
  bool ischeck = true;
  print(number);
  print(name);
  print(fname);
  print(smaic);
  print(ischeck);
  print(name.toLowerCase());
}	123
ALI
akram
3434.2
true
ali

void main (){
  
  int id, rolno, cnic;
  String name, fname, address;
  double per, domi;
  bool yes, nos;
  id= 1;
  rolno=23;
  cnic=35501;
  name='kh';
  fname='th';
  address='chak 91';
  per=32.2;
  domi=23.22;
  yes=true;
  print(id);	Multi line verable 
void main(){
  int id=1, rollno=12,cnic=23323;
  String name='khadim',fname='talib';
  double domi=23.2, ab=12.333;
  bool yes=true, no=false;
  print(domi); 
   
}	Single line verable 
String =abc or abc1 or _abc or $abc	Every verable start with alpha, _ or $
	Verable no use space or special character 
Cant not use keyword (void like or String)
Statistic verable	Int
String
Doble bool
(Inferred verable)    
var id=1,name='khadim', yes=true, domi=23.22;	Use for writing  multiple variable in one line  
  print(name.toUpperCase()+'     '+fname.toLowerCase());	Lower and uppercase
Verable	userId, userFname (uperCamleCase
Directory name	(Small and use snack case)
file_name, folder_name, directory_name, project_name
LECTURE – 06 
Null	Blank, empty 
Jis me koi data na dena ho
Nullable variable

Null likhny ky ly ? lgana  pry ga	All staticlally type verable are nulable
Int, String, double, bool (is me Null ni likh sakty
Non nullble banany ky ly data type ky bd ? lgaty hn	Int? Id=Null;
String? Name=’khadim’; 
Non-nulable veriable	Var phonNo=Null;     (is me null likh sakty hn
Var	Use for all verable
Dynamic	Use only int, string, bool, and double 
void main (){
  var d;
  d=333;
  d="khadim";
  d=3.333;
  d=true;
  print(d); 
  
}	Is me jo last pr ho ga wo answer ay ga
TRUE
void main(){
int? a;
print(a ?? 34);
}
	Null ko print krny ky ly ?? lga kr value dy skty hn

??	Use for replacement

void main(){
  String? a, b='ali';
  print(a ?? b);
}
	Replacement hum veriable b print krwa skty hn

void main(){
 var a, b=10;
 a= a ?? b;
 print(a);
}
	Result 10
A ko B ki value replace ho jay gay
Right wali cheez replace hoti ha left waly ko
void main(){
 var a;
 a??= 12;
 print(a);
}
	??=
void main(){
 var a, b=12, c=23;
 print(a ??= b+c);
 print(a);
}
	 Result 
35
35

void main(){
 var a, b=12, c=23;
 print(a ?? b+c);
 print(a);
}
	35
Null
void main(){
 var a, b=12, c=23;
 a ??=b+c;
 print(a);
}
	35
a ?? b+c;	Assign result Null
a ??=b+c;	Replacement result b+C
Const url=’all-available.com’;
Is me usi waqat value dani pary gi
	In ki value kbi bi change ni ho gi
Const me usi waqt value daty hn

Final id=334;   is me bad me value dy sakty hn… lekin sir 1 bar
and
void main(){
 var a, b=12, c=23;
 final g =c;
 print(g);
}
	Final me koi or value b assign kr saty hn sirf ak bar
void main(){
String a='Pakistan', b=' zindabad',c=' on ';
int d= 14;
String e=' August';
print(a+b+c+d.toString()+e);
}
void main(){
int a=444;
String b="pakistan";
final c=44;
double d=3.2;
print(a.toString()+b+c.toString()+d.toString()); 
}
	Pakistan zindabad on 14 August
void main(){
int d= 14;
print("Pakistan Zindabad on $d August");
}
	String Literal
Pakistan zindabad on 14 August
void main(){
int d= 14;
String a="Pakistan Zindabad on $d";
print(a);
}
void main(){
int a=444;
String b="pakistan";
final c=44;
double d=3.2;
print("ints $a, Strints $b, finals $c and doubls $d"); 
}	Pakistan zindabad on 14 August
Hum asy b multiple value print kr sakty wo string ya koi or
void main(){
int d= 14, b=34;
double c=343.333;
String a="khadim";
print(" My Name is $a my total marks is ${d+b*c}");
}

	String interpolation   
My Name is khadim my total marks is 11687.322
void main(){
int a=10, b=20, c=30;
print("My math number  is ${a+b} and islamyat number  is ${b-a} english number is ${c*a} and toal is ${c/a}");
}
void main(){
int a=444;
String b="pakistan";
final c=44;
double d=3.2;
print("ints ${a+c+d}, Strints ${a+c-d}, finals ${a*c/d} and doubls $d"); 
}	My math number  is 30 and islamyat number  is 10 english number is 300 and toal is 3.0
Dart collection 3 type
List
Set
Map	Is me multiple vale likh skaty hn



void main(){
  List list =['a','b','c',1,2,3,34.2];
  print(list);
}
and
void main(){
  var list =['a','b','c',1,2,3,34.2];
  print(list);
}
and
void main(){
  List <int> list =[1,2,3];
  print(list);
}
	Is me doublicate value a sakti hn

void main (){
Set set={'pakistan', 'born', 'on' ,14,'august'};
print(set);
}
and
void main (){
  var set={'pakistan', 'born', 'on' ,14,'august'};
  print(set);
}
and
void main (){
  Set <String> set={'pakistan', 'born', 'on' ,'august'};
  print(set);
}


	Is me duplicate value ni a sakti

void main (){
Map map={"user_name":"Khadim", "user_contact_no":03014504591};
print(map);
}
and 
void main (){
var map={"user_name":"Khadim", "user_contact_no":03014504591};
print(map);
}
and
void main (){
  Map <String, String> map={"user_name":"Khadim", "user_contact_no":'yes'};
  print(map);
}



	Is me duplicate value ni a sakti
Keye must b in snack_case and small digit

void main (){
  Map <String, dynamic> map={"user_name":"Khadim", "user_contact_no":'0302330930'};
  print(map);
}
	Dynamic me sb velue a jati
 Best type
Map <String> map= 
LECTRE NO. 10	
void main(){
 // List  me dublicate value  a sakti ha
List name=["ali","akram"];          // list creat in one line
List? fName=[];                     // null value
List sonName=["jabbar","murtaza"];
List finalNames=[...name,...fName,...sonName];             // tamam list ki ak final list creat krny ky ly ...
// var name=["ali","akram"];            //var ky through b list creat ho  sakti
 //List <String>name=["ali","akram"];   // String ya int sy spicify data likh sakaty
 //List name=[];                      //list me data bd me add kr sakty
 //name.add("ali");
 //name[0]="aslam";                    // value update kr sakty
// name.removeAt(0);                   // value deltet kr sakty
 //name.clear();                     // sb kcuh delte kr skty
// for in ky throuth spicific vale print kr sakty 
//for ( String student in name){ print(student); }
For +int or string+name+in+value{print+name} 
values ko asy print krwany ky ly
1
2
3 
 //print(name.elementAt(1));          // koi b value 0,1 likh kr print kr sakty
 print(name.length);                // total lenth dekh skaty
 print(finalNames);
}
void main(){
Set<int> values= {10,20,30,40,50};
int sum=0;
  for(int number in values){
    sum= sum+number;}
  print("$values");
  print("$sum"); 
  
  }  
void main(){
List fruitNames=["Apple","Mango","Orange","Banana","Grapes","Strawberry","Pineapple"];
List fruitList=[];
for(var fruits in fruitNames){
fruitList.add(fruits);
}
print(fruitList);}	LIST
 
void main(){
 // Set  me dublicate value nahi a sakti ha
 Set name={"ali","akram"};          // Set creat in one line
 Set? fName={};                     // set -1 - null value
 Set sonName={"jabbar","murtaza"};  //set-2
 Set finalNames={...name,...fName,...sonName}; //set-3           // tamam list ki ak final list creat krny ky ly ...

//var name=["ali","akram"];            //var ky through b list creat ho  sakti
 //Set <String>name={"ali","akram"};   // String ya int sy spicify data likh sakaty
 //Set name={};                      //list me data bd me add kr sakty
 //name.add("ali");
// name[0]="aslam";                // value update ni ho sakty
// name.remove(0);                   // value deltet kr sakty
 //name.clear();                     // sb kcuh delte kr skty
 //for ( String student in name){      // for in ky throuth spicific vale print kr sakty
 //print(student); }
// print(name.elementAt(0));          // koi b value 0,1 likh kr print kr sakty
//print(name.length);                // total lenth dekh skaty
print(finalNames);
}
void main(){
Set<int> values= {10,20,30,40,50};
int sum=0;
  for(int number in values){
    sum= sum+number;}
  print("$values");
  print("$sum"); 
  
  }
void main(){
  Set fruitNames={"Apple","Mango","Orange","Banana","Grapes","Strawberry","Pineapple"};
Set fruitList={};
for(var fruits in fruitNames){
fruitList.add(fruits);
}
print(fruitList);
              }  	Set
void main(){
 // Map  me dublicate value nahi a sakti ha - Keye must b in snack_case and small digit
 Map? nameali":"akram"};      //map-2    
 Map SonName={"zubair":"rana"};         //map-3 
 Map finalName={};        //map-1 - null value  // list creat in one line
 Map fName={"s={...name,...fName,...SonName}; //map-4          // is me sb map ki value a gai

//var name={"ali":"akram"};            //var ky through b list creat ho  sakti
// Map <String, dynamic>name={"ali":"akram"};   // String ya int sy spicify data likh sakaty
// Map name={};                      //list me data bd me add kr sakty
 //name.addAll({"ali":"akram"});
 //name["ali"]="aslam";                    // value update kr sakty
 //name.remove("ali");                   // value deltet kr sakty
 //name.clear();                     // sb kcuh delte kr skty
//for ( String student in name.values){      // for in ky throuth spicific vale print kr sakty
//  print(student); }
//print(name.length);        // total lenth dekh skaty
 print(finalNames);
}
void main(){
Map<int, int> values= {10:20,30:40};
int sum=0;
  for(int number in values.values){
    sum= sum+number;}
  print("$values");
  print("$sum");
void main(){
  
  
  Map <String, String> fruitNames={"fruit":"Apple"};
Map fruitList={};
for(String  fruits in fruitNames.values){
fruitList.addAll(fruits);
}
print(fruitList);
              }
  
  }
	Map
void main(){
  List teacher_name=[];
  teacher_name.add("Aslam");
  teacher_name.add("Akram"); 
  print("my total teacher is ${teacher_name.length}");

}
	my total teacher is 5
void main (){
  Set color={};
  color.add("green");
  color.add("white");
  color.add("black");
  print("my feverot color are ${color.length}");
}
	my feverot color are 3
void main (){
  Map color_code={};
  color_code.addAll({"green":54545,"white":45454,"black":45454});
  print("my feverot color code are ${color_code.length}");
}
	my feverot color code are 3
NAME      CALLS
GREEN>     KEYS
54545>    VALUES
GREEN:54545> ENTRIES
void main (){
  List color=[];
  color.add("green"); 
  color.add("white");
  color.add("black");
for (var item in color){
  print(color);}

}
	for in

{green, white, black}
{green, white, black}
{green, white, black}
void main (){
  Set color={};
  color.add("green");
  color.add("white");
  color.add("black");
for (var item in color){
  print(color);}
  
}
	{green, white, black}
{green, white, black}
{green, white, black}
void main (){
  Map color_code={};
  color_code.addAll({"green":54545,"white":45454,"black":45454});
  for (var color in  color_code.entries) {
  print(color.value);
  print(color.key);}
  
}
	
void main (){
  List color=[];
  color.add("green");
  color.add("white");
  color.add("black");
  color [0] = "yellow";
  color[1] = "red";
  print(color);
}
	For update values
[yellow, red, black]
void main (){
  Map color_code={};
  color_code.addAll({"green":54545,"white":45454,"black":45454});
color_code["green"]=88889;
color_code["white"]=888;
color_code["black"]=898798;
print(color_code);
}
	For update values
{green: 88889, white: 888, black: 898798}
void main (){
  List color=[];
  color.add("green");
  color.add("white");
  color.add("black");
color.removeAt(0);
  print(color);
}
	For remove any value
[white, black]
void main (){
  List color=[];
  color.add("green");
  color.add("white");
  color.add("black");
color.clear();
  print(color);
}
	For remove all values
void main (){
  List color=[];
  color.add("green");
  color.add("white");
  color.add("black");
  print(color.elementAt(1));
}
	Koi ak value print krny ky ly
void main (){
  Set color={};
  color.add("green");
  color.add("white");
  color.add("black");
  color.remove("green");
  print(color);
}
	Set me sy koi value delete krni ho to
{white, black}
map.remove(99889);	Map me sy value remove krna
void main() {
  List item1 = [1, 2, 3, 4];
  List item2 = [5, 6, 7, 8];
  List item3 = [9, 10, 11, 12];
  List item4 = [ ...item1, ...item2, ...item3,13,14];
  print(item4);
}
	4 list ko 1 list me dalna
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]
void main() {
  List? item1 = Null;
  List item2 = [5, 6, 7, 8];
  List item3 = [9, 10, 11, 12];
  List item4 = [ ...?item1, ...item2, ...item3,13,14];
  print(item4);
}
	Nul ko b add krny ky ly
FUNCTION (part of name body, parameters, retrun type, parenthise                   control+p           see all values 
Phly function banana phr call krna
Function kesi b function add ho sakta ha
DEFINITION=> A function is a set of statements to perform a specific task. Functions organize the program into logical blocks of code.
Once defined, functions may be called to access code. This makes the code reusable. In simple words we can say that functions are used for
code-re-usability and code-organization.
=> Every function contains a specific name, parenthesis, and a body
=> we can also use parameters in functions but these are optional
=> we can also return value to a function but it is also optional
=> a function is defined in start and then called after block of code for execution

CODE REUSBILITY
Return
// use of "return" keyword in functions
// return keyword is used in the body of any function to return its value to the function
// we can only return one value in a function
// once we use return statement, the lines of code will not be executed anymore
// we can only return value once in a function
// it is a good practice to mention/define data type of a function
// if data type of a function is defined then its return type will be in same data type 
// we cannot use one data type in a function call and other in code body
// if we use void keyword before using function then its value cannot be returned

Return me  hum function sy phly int, String etc lga skty hn jis ka matlb ye int or string typy ka data return kry ga

 

void main() {
  print(myInfo());}
  
  
  myInfo(){
  List myInfo=["Huma Nazir", "Nazir Ahmed", 23, 3.9, "Pass"];
  return myInfo;
}

void main(){
  print(addNumbers());
}
addNumbers(){
  int number1= 10;
  int number2= 20;
  int totall= number1 + number2;
  return totall;
}	30
// FUNCTION PARAMETERS
//Parameters are the values of the function written inside the parenthesis that are used in function
//Parameters can be of any data type
// value of a parameters will be assigned in a same data type as it is defined in function definition
// Parameters can only be accessed inside the body , we cannot access them outside the body
/* Defining a parameter is not compulsory, it is optional, but if we have defined a parameter in function then we will have to asign
the value of that parameter while calling a function*/
//we can consider parameters as variables
//there are two types of parameters 1=> Required Parameters 2=>Optional parameters
(I have called function before it's definition in these notes to maintain the sequence but in real coding function will be defined before it is being called)
Parameter koi b value lay sakta ha like int, string etc or smiple a b ly skta
 
	Required (int a,int b) parmeter ki bja khud required parmeter banan chay 
({required int a, require int b})
Is  me value zayada clear han
Ku k is me  pata ha a ki value kia ha b ki value kia ha
Khud required bana behtar ha

void main(){
  addNumbers(10,20);
}
void addNumbers(int number1,int number2){
  number1= 10;
  number2= 20;
  print( number1 + number2);
}	Required parameter
Required bht km hoty han optional parmeter zayda hoty hn ku ky in qalarty zayda hoti ha
C:334;

void main(){
  addNumbers(10,20);
}
void addNumbers(int a,int b,{int c, String d, bool e}){
  a= 10;
  b= 20;
  print( a + b);
}
 	Optional name  parameter
Start with {} in ki  tarteeb zarori ni
{} ki value do ya na do
Optional name parmeter must be initialized or nullable 
Nullable krna bht resky km ha initliazed krna asan ha jeder zarot ha uder nullable banay

void main(){
  addNumbers(10,20);
}
void addNumbers(int a,int b,{int? c, String? d, bool? e}){
  a= 10;
  b= 20;
  print( a + b);
}
	Nullable bnany ky ly
void addNumbers(int a,int b,{int c=0, String d=0, bool e=0}){
	initliazed kry ky ly
void addNumbers(int a,int b,{ required  int c, required  String d, required bool e}){
	Parameter ko required banay ky ly
void main(){
  
  
  studentData("khadim Hussain", 233, cnicNo:36502, email:"abc@gmail.com", dob:"34/2/1987", gpa:3.21);
  
}
void studentData(String name,int rollNo,{int cnicNo=0, String email="", var dob="", double gpa=0.0,}){

print(name );
}	Khadim hussain
import 'dart:html';

import 'package:flutter/material.dart';
void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Functions"),
        ),
        body: Material(
          child: Center(
            child: ElevatedButton(
              child: Text("Click Me!"),
              onPressed: () {
               studenInfo("Khadim Hussain", 22,dob:"10-11-1987",emailAddress: "abc@gmail.com");
              },
            ),
          ),
        ),
      ),
    ),
  );
}

void studenInfo (String name, int rollNo, {var dob="", String emailAddress=""}){
   print(rollNo);
  print(dob);
  print(emailAddress);
}
	
Myfunction(){
//dart code
Print(“hellow”);}	
myName(){
 String name="khadim Hussain";
  String fName="Talib Hussain";
  print("my name is $name");
    print("my Father name is $fName");
  
}
void main(){
myName();   
  
}	my name is khadim Hussain
my Father name is Talib Hussain

void main(){
  print(myColorCode());
  
}
myColorCode(){
  Map color={"Yellow":444, "green":4434};
  return (color);  
}
	Return function
	
myMarks(){
 List <String> subjects=["English", "math"];
  List <int> numbers=[12,33];
  List<double> gpa=[2.21, 3.42];
  List total=[...subjects,...numbers,...gpa];
return(total);}
void main(){
  dynamic total=myMarks();
print (total);  
  
}	[English, math, 12, 33, 2.21, 3.42]
totalNumber(){
  int a=2, b=2;
  int c=a+b-12+3;
  return(c);}
  void main(){
    double ac=totalNumber()+34+totalNumber()/4-totalNumber();
    print(ac);
  }
  	double
Flutter Base Code:
import 'package:flutter/material.dart';
void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Functions"),
        ),
        body: Material(
          child: Center(
            child: ElevatedButton(
              child: Text("Click Me!"),
              onPressed: () {
                dynamic total=myMarks();
                print (total);
              },
            ),
          ),
        ),
      ),
    ),
  );
}

myMarks(){
  List <String> subjects=["English", "math"];
  List <int> numbers=[12,33];
  List<double> gpa=[2.21, 3.42];
  List total=[...subjects,...numbers,...gpa];
  return(total);}
	
familyName("Khadim Hussain","Talib Hussaian",broName:"umar", sisName:"Mumtaz");

void familyName(name, fName,{broName="",sisName=""}){

  print("my family member name are ${name+" "+fName+" "+broName+" "+sisName}");
}
	
 	
marks(mark: [3,2,3,2,1], totalNumber: 1);

void marks({required List mark,required int totalNumber}){
if(mark.contains(totalNumber)){
  print("$totalNumber exist");
}
else{
  print("$totalNumber  not exist");
  }
	
marks(mark: [3,2,3,2,1], totalNumber: 1);

void marks({required List mark,required int totalNumber}){
mark.contains(totalNumber)? print("$totalNumber exist"): print("$totalNumber notexist");
  }
	
void marks({required List mark,required int totalNumber})=> mark.contains(totalNumber)? print("$totalNumber exist"): print("$totalNumber notexist");
	=>, arrow function
Use for only one statement
Int mark(int number)=>30;	Use for return
Phr retrn likhny ki zarort ni
Is me position matter krti h
Phly a b c d
Ab ky bd d c ki value ni dy sakaty
Is me required use ni ho skta	Opionalpositional parmater ko [] me lkihty hn
  void main(){ 
  marks(number:{"English":33, "Urdu":22,});
  }
  void marks({required Map <dynamic, int> number}){
  print(number);      
     }	{English: 33, Urdu: 22} 

Abc (){
Print(“basic function)”
}
Basic function kesi b type ka data return krwa skata ha	Basic function
Void abc (){
Print(“regular function)”
}	Regular function
Int abc(){
Return 23;
}
Printn ky ly asy cl krty
void main(){
  print("${abc()}"); 
  
}
int  abc(){
  
  return 445;}	Retrn function

Function (is me function ka name lazmi dety hn) abc();
banay ka maqsad koi code bana kr rkh lty hn jo bar bar istmal  ho sky	Code reusability

 
Anonymous function (){ ye bd me use hota} 
Is me Function data type use hota 
•	nameless function-
•	asa function jo kesi dosry function ko as a parmeter ly higher order function hota ha
•	Higher order function ko call krty waqat Anonymous function istml krna ha
•	Abc(Function, int)
•	Abc(is me jo function baya likhty hn, 34)
•	ye sirf ak br use hota
•	is ka fada ya ha is me name space bach jati
•	name dayny ki zarort ni hoti
•	Asy function jin ko bs ak br hi cl krny ki zarort ho
•	banay ka maqsad koi code bar bar istmal  na  krna ho to
•	is ko as a parmeter kesi dosry function me pass krain gy
•	Namless function
•	Lambda function var abc= (){print(“hlo”);};
•	One time calling
•	Immeditaly calling (callback function•		  void main(){
  elevatedButtion( onPress:(){},child:"click it");{
    print("onpress");
  }}
elevatedButtion({required Function onPress, required String child}){
  
}
Function abc= 44;  
•	(function b data type jesy int)
•	Function type me function data type hoti jesy int me 33
•	Print(abc);
•	var abc= 44;
•	Print(abc);	Agr koi function type lekhni ho to function or var type istmaly krty hn
Abc(function a, String b){
} asa function jo kesi dosry function ko as a parmeter ly higher order function hota ha
Phly function bna lain 	Higher order fuction
Mark(abc,44);
Void mark(function a, int b){}
Abc int(333);	 Higher order function ko call krty waqat Anonymous function istml krna ha 
void main(){
  abc(a:(){}, b:444);
}

  abc({Function? a, int b=0}){ 
    print("$b");
    
  }	
void main(){
  abc(onPress:(){},child:"Khadim");
}
abc({required Function onPress, required String child}){
  print("$child");
}	
void main(){
  abc((){},"Khadim");
}
abc(Function onPress, String child){
  print("$child");
}	
 
  void main (){
    elevatedButtion(
      onPress:(){
        print("abc");    
        
      },
      child:"click me",    
    );   
      
  }
elevatedButtion({required Function onPress, required String child}) {
  
}	
Device event
All nofication ana, mobile stare hona, close hona, alarm baja	
App event
Button press, long press, tap, app open, app close, alret box	
Call back function (also name after function) –
Ye button pr press krny pr call hota
event pr call ho ga
A function that call upon an event trigger
We don’t manualy call
We always pass a function parmater 
We always pass anonymous function 

Ye Anonymous function ky ult likhty
Is me value nechy dety or parameter void main me

onPressed: () {
outerFunction(({required int a, required String b,}){print("a value is$a and b value is $b");});}
void outerFunction (Function callBack){
  callBack(a:2, b:”ali”);
}
	
outerFunction((){print("hellow");});
void outerFunction (Function callBack){
callBack();}

void main(){
outerFunction((){print("hellow");});}
void outerFunction (Function a){
a();}	
pressButton (one press and result)
longPress (press long and result)
onHover (mouse ko button p rly kr jain gy to wo call ho jay ga press krny ki zarott ni ho gi)

	
onPressed: () {
outerFunction(({required int a, required String b,}){print("a value is$a and b value is $b");});}
void outerFunction (Function callBack){
  callBack(a:2, b:”ali”);
}
	
onPressed: () {
                outerFunction((a,b){print("a value is$a and b value is $b");
  });
void outerFunction (Function callBack){
  callBack(33,22);
}


}
	
outerFunction ((a, b) {print("total marks of a is $a and b is $b ");
});
void outerFunction( Function call){
  call(22,2);}	
outerFunction ((int a, String b) {print("total marks of a is $a and b is $b ");
});
void outerFunction( Function call){
  call(22,"ali");}	
outerFunction (({required int a, required String b}) {print("total marks of a is $a and b is $b ");
});
void outerFunction( Function call){
  call(a:22, b:"ali");
}

	
outerFunction (({required int a, required int b}) {return a+b;});
void outerFunction( Function call){
 print( call(a:22, b:44));
}
	
 
Object oriented programming (OOP)
OPP is not a programming language
OPP is the name of STRUCTURE, APPROCH, PATTREN, DESIGN PATTERN, WAY OF WORKING
Benefit of OPP code reusability and code organization	
OPP TOPIC
•	Classes & objects
•	Constructors
•	Inheritance
•	polymorphism
•	Abstraction
•	Generic classes
•	Enumeration
•	mixin 	
•	Classes & objects 
•	(class bany ka  maqsad hum us ky function ko utlize krain
•	student ki classs me sb kuch student ka data ak hi body me para ho ga- 
•	class me multiple function likh skty
•	her class  ky ly new file bannay thy like student file name click new >dart file then  file name student
•	agr same thing ak file me br br ain to her kisi ki new file bna lty hn
•	Name of group like male female cast, nantality, 
•	Class Student_Name{} class me phla word capital ho ga
•	Students ni ho ga Student hoga (jama ni ho ga single ho ga)
•	Is me object small ho ga
•	Class ki property / object class ky function me use hoti hn
•	Object  ki value update  b kr sakty student.name =”usma”
•	static late int no; (agr me object me phly static lgay gy to is ki value jetni b function ya object hon gy acces ho skati ha
•	Student.no=20;  classname+ static object name= value;
•	Ye pori class ki property hoti•		
void main(){
 //object small me ho  ga
  //multiple object bna  skty
  //class name+object name+=+class name+();
  Student student_Name= Student();
  Student student_RoolNo= Student();
  
}
class Student{
  
}
//property, /attributes/specification (male hight, color, age)
//function / method ( wo hardworker ha, disiner ha koi khobi)
Late lagna ha
Class ki propity use  krty hovy class name use na krain like
Class Student{
Late Int rollno;
Late String name;	
void main(){
  //object creation
  Student info=Student();
  
  //function calling
  info.abc();
  info.xyz();
  info.klm();
 
  
}
//object / property typing
class Student{
 late int id;
  late String name;
  late int rollNo;
  late String section;
  late String address;
  late double gpa;
  late bool result;
  late var email;
  late List names;
  //function typing
  void abc(){
    print("paksitan");}
    void xyz(){
      print ("zindabad");}
      void klm(){
        print ("14 august");}
}	
Var detail=Pakistan();   (var ky throuth b kr  skty)
void main(){
  Pakistan detail=Pakistan();
  detail.pakistaniDetail();
  detail.pakistaniDetail2();
  detail.pakistaniDetail3();
  
}
class Pakistan{
  late int id;
  late String babyqom;
  late String symble;
  late String language;
  late String fruit;
  late String flower;
  late String game;
  void pakistaniDetail(){
print ("My country");
  }
  void pakistaniDetail2(){
    print ("name");
  }
  void pakistaniDetail3(){
    print("is Pakistan Zindbad");
  }
}	
•		
	
 
void main (){
  StudentDetail students1=StudentDetail(); //students1
  students1.student1(4,"khadim");// students1 data
  students1.id=55;               //update values
    StudentDetail students2=StudentDetail(); //students2
  students2.student1(5,"ali");   //students2 data
  
    StudentDetail students3=StudentDetail(); //students3
  students3.student1(6,"akram"); //students3 data
 // print(students1.id); //print one specfic value
 // students1.detail();  //print all values
  //students2.detail();
  //students3.detail();
 
  StudentDetail.no=56;     //static value
  print(StudentDetail.no); //static print

  
}
class StudentDetail{
  static late int no; //static propirty 
  late int id;
  late String name;
  void student1(int idno, String studentName){
   id=idno;
    name=studentName;
  }
  void detail(){
      print(id);
    print(name);
    
  }
}  void detail(){
    print(id);
    print(name);
    
  }
}	
void main(){
  //student-1 data
  StudentDetails student1=StudentDetails();  // class+object+class
  student1.studentValues(11,"khadim",3.27);    //object+functin-1+values
  student1.name="khadim Hussain";             // value update krna
  //student-2 data
  StudentDetails student2=StudentDetails();  // class+object+class
  student2.studentValues(12,"ali",2.27);    //object+functin-1+values //student-1
  //student-3 data
  StudentDetails student3=StudentDetails();  // class+object+class
  student3.studentValues(13,"akram",1.27);    //object+functin-1+values //student-1
  //student-4 data
  StudentDetails student4=StudentDetails();  // class+object+class
  student4.studentValues(14,"saqlain",4.27);    //object+functin-1+values
  //print student data
  print(student1.name);                    //one or spacif value print
  student4.studntprintdata();              //pory student ka data print krna
 //static value
  StudentDetails.id=1;                    //  static value dena (class+object+value)
  print( StudentDetails.id);              // static value print krna
   
}
//class
class StudentDetails{  //(1)class
  static late int id; //  is ki value sb ko assing ho gi- is ko functiton me value ni dani
  late int no;         //Object/propirty
  late String name;
  late double GPA;
  //function-1
  void studentValues(int studentNo, String studentName, double studentGPA ){  //function-1 + value name
    no=studentNo;                //object propirty assign in function
    name=studentName;
    GPA=studentGPA;      
  }
  //functuin-2 print function
  void studntprintdata(){        //Function-2 for printing data (agr pory student ki value print krni ho oper)
    print(no);
    print(name);
    print(GPA);
  }  
  
}	
Constructors 
Function ky under constructor use ni hoty
Class ky under constructor use hoty hn
Constructor ky bd function b bn sakta ha

•	Ak class ky different constructors ho skty han like normal student ka constructor (Student(){})
•	Freelancer student ka (Student.freelancer(){})
•	Developer student ka(Student.devloper(){})
•	1st constorct ky 3 object han to 2nd constructor ky 3 ya zayda ho sakty 2 ni ho skaty
•	Jo class ka name ho ga wohi constructors ka name ho ga
•	This is special function 
•	Use for initialise class-properties 
•	Syntax is same as function 
•	Constructor name same name as class name
•	Call automatically when object creation (jb void main me likhy gy to ye call ho jay ga)
•	No return type (is me voide ni likhty)

Clas me 1 sy zayda constructor ho skty

•	Default constructor           // jb koi constructor ni dety to wo default hota

•	Parmeterized define constroct // ye sirf ak constructor ho skata ha -is me value dety

•	Named-constructor // ye multiple constructor ho sakty hn	
void main(){
  Student student1=Student(1,2,3);  // edr value dety
}
class Student{
  Student(a,b,c){         // calass wala name dty
  }
}	Constructors 

void main(){
  //parmetrized constructor
  Student normal= Student(1, 22, "Khadim Hussain", 3.27);   
  //named-constructor-1
    Student freelancer= Student.freelancer(2, 33, "Saqlaim", 2.27, "khadimitswl");   
    //named-constructor-2
    Student developer= Student.developer(2, 33, "Saqlaim", 2.27, "khadimitswl", "app devlopment");  
}
//class
class Student{
  late int id;
  late int rollNo;
  late String name;
  late double gpa;
  late String profilelink;
  late String course;
  //parmetrized constructor
  Student(int studentId, int StudentrollNo, String studentName, double studentgpa){
    print("normal student name $studentName");
  }
  //named construtor -1
    Student.freelancer (int studentId, int StudentrollNo, String studentName, double studentgpa, String link){
        print("freelancer student name $studentName");
  }
    //named construtor -2
    Student.developer (int studentId, int StudentrollNo, String studentName, double studentgpa, String link, String course){
        print("developer student name $studentName");}
}
  	
	
void main(){
  //parmetrized constructor
  Student normal= Student(1,);   
  //named-constructor-1
    Student freelancer= Student.freelancer(33);   
    //named-constructor-2
    Student developer= Student.developer("Saqlaim");  
}
//class
class Student{
  late int id;
  late int rollNo;
  late String name;
  late double gpa;
  late String profilelink;
  late String course;
  //parmetrized constructor
  Student(int id){
    //iniitlized
    this.id=id;
or short hand  approach
Student(this.id, this.name, this.rollNo) (hum body ki bajay esy b 1 line me code likh sakty)
    
    print("normal student name $id");
  }
  
  //named constructor -1
    Student.freelancer (int rollNo){
      this.rollNo=rollNo;
        print("freelancer student name $rollNo");
  }
    //named construtor -2
    Student.developer (String name){
      this.name=name;
        print("developer student name $name");}
}	Constant constructors
Me apni marzi sy jis ko jetni marzi value day sakty han 
This.name use for same name
Constant constructors means immubalbe objects
•	Constant jis  ki value change na ho object ki  value change na  ho
•	Class propriety final honi chahy
•	Is ki koi body ni honi chahy
•	Use const keywork to creat constant consstructor
•	Is me sb her constructor me sary objects ain gy, agr hum 5 me sy 2 to ko instilize kry is me null ni ay ga agr
•	Used for creation constant objects 
•	vlue na b dain to
•	Jb name same ay ga  to this.name keyword lgain gy	
void main(){
  const Employee data=const Employee(1, "khadim", 33);
  
}
class Employee{
final int id;
final String name;
final int rollNo;
const Employee (this.id, this.name, this.rollNo);
}	
void main (){
  const Teacher data=const teacher(4, "khadim"); 
  
}
class Teacher{
  final int id;
  final String name;
  const Teacher({this.id=33, this.name="khadim"});
 }
	
By using name parameter constructor
({Name:khadim)}

void  main(){
  Human detail =Human(1,2,3);
  var detail2=Human(1,2,3,);
  var detail3=new Human(1,2,3);
}
class Human{
  Human(int a, int b, int c){
    print("$a,$b, $c");
    
  }
}	
 
	
 
void main(){
  const Student value=const Student(id:33,name:"khadim");{
    print ("$Student");
  }
}
class Student{
 final int id;
  final String name;
  const Student({required this.id, required this.name});
}	By using required or using name parmeter
Class Elements
•	Class property
•	Functions
•	Constructor
Inheritance (extends)
•	The main purpose of Inheritance is “code reusability”
•	Inheritance means” relationship between classes”
•	The basic relationship is “parent-child” child class parent class ky function, constructor or property ko use kr sakty hn
•	Parent class: main class: super class
•	Child class: derived class
•	We use “extends” keyword to create parent-child relationship
•	Parent class me genral/common PROPITY OR FUCNCTION rakhy gy
•	Child class me specific cheezy rkhy gy 
•	Child class parent ki property or function ko use kr sakti ha lekin construction use ni kr sakty
•	Dart suppots only multi level inheritance means(Pakistan>Punjab>sahiwal>91/6r 
•	Is me 91/6r ka constructor ka object banty hovy phly Pakistan ka constructor call ho ga phr Punjab ka phr sahiwal phr 91/6r
•	In parent-child relationship first call parent class constructor then child construct
•	Hr child class ka apna constructor hota jo koi or child ismtal ni kr skata

•	We use “super” keyword when we have a constructor having argument / paametr in parent class
•	Agr parent class ky construct me koi parameter hon gy to humy “super ” use krna ho ga
•	Paramet construct sirf 1 ho sakata name constructor jetny marzi bna lain
void  main(){
  Pakistan info =Pakistan(34);
 }
class Pakistan{
  Pakistan(int a);
}
class Punjab extends Pakistan{
  Punjab(): super (34);  
}



void main(){
//object banaya  //constucor call keya
  Women ayesha= Women();
  Male ali=Male();
  
}
class Human{
  Human(int id, double  gpa,{required String name,required  String city, required int age}){
    print("$id, $gpa, $name, $city, $age");
    
  }}
  class Male extends  Human{
    Male() : super (1,3.23,name:"ali",city:"lahore",age:43);
  }
  class Women extends Human{
    Women() : super (2, 2.45, name:"ayesha", city:"karachi",age:54);
     }
1-	PARENT CLASS
2-	CHILD-1 CLASS
Child functions
3-	CHILD-2 CLASS
Child functions


class Pakistan {
  
}
class Punjab extends Pakistan{
  
}
class Sind extends Pakistan{
  
}
class Kpk extends Pakistan{
  
}
class Balochistan extends Pakistan{
  
}


Classes relationship 	
void main(){
//parent class call in parent
Pakistan pakinfo=Pakistan();
//parent function call in parent
pakinfo.national_language();
//parent proprity call in parent
pakinfo.id=33;
 //child-1 class call
Punjab punjabinfo=Punjab();
//parent propirty use in child-1
punjabinfo.id=44;
//parent function use in child-1
punjabinfo.national_language();
//child-1 function use in child-1
punjabinfo.river();
//child-1 propity use in child-1
punjabinfo.punjab_Cloth="shalwar kameez";
//child-2 cass call
Sind info =Sind();
//parent propirty call in child-2
info.id=11;
//parent function call in child-2
info.national_language();
//child-2 propirty call in child-2
info.sind_language="sindi";
//child-2 function call in child-2
info.sea();
}
//parent class
class Pakistan{
  //parent propirty
  late int id;
  late String game;
  late String flower;
  late String bird;
  late String color;
  late String theem;
  late String sweet;
//parent functions

void national_language(){
  print("nationl language");

}
void national_cloth(){
  print ("national cloth");

}}
//child-1 class
class Punjab extends Pakistan{
  //child propirty
  late String punjab_Language;
  late String punjab_Cloth;
  late String punjab_Colur;
  //child function
  void river(){
    print("5 river in punjab");

  }}
//child-2 class
class Sind extends Pakistan{
  //child propirty
  late String sind_language;
  late String sind_cloth;
  late String sind_colur;
  //child function
  void sea(){
    print("1 sea in sind");

  }}
	
 
void main() {
  //name  consrrucror  call

  Women ayesha = Women();
  Male ali = Male();
  //parameter consrucer call
  Boy aslam = Boy("aslam", 44);
  Boy akram = Boy("akram", 54);
}

//parent class
class Human {
  //parametr consructor of parent class
  Human({required String name, required int age}) {
    print("$name, $age");
  }
  //name constructor of parent class
  Human.details(int id, double gpa,
      {required String name, required String city, required int age}) {
    print("$id, $gpa, $name, $city, $age");
  }
}

//child class -1
class Boy extends Human {
  //parmeter consturc objects
  //class+object+super+objec:object
  Boy(name, age) : super(name: name, age: age) {}
}

//child class-2 use super.detail (super keyword +name of construct)
class Male extends Human {
  //name constructor
  Male() : super.details(1, 3.23, name: "ali", city: "lahore", age: 43);
}

//child class-3
class Women extends Human {
  //name consructor
  Women() : super.details(2, 2.45, name: "ayesha", city: "karachi", age: 54);
} //child class-3
  class Women extends Human{
    //name consructor
    Women() : super.details (2, 2.45, name:"ayesha", city:"karachi",age:54);
     }	
Menually call 
void main() {
  Male id_1 = Male(1);
  Male id_2 = Male(2);
  Male id_3 = Male(3);
  Male id_4 = Male(4);
}
class Human {
  Human(int id) {
    print("$id");
  }
}
class Male extends Human {
  Male(id) : super(id);
}	Pass parameter dynamically to parent class constructor
void main(){
  Male akram=Male(23, "ali");
  Male a=Male.name(88,12);
}
//parent class
class Human{
  //parent paramet constroct-1
  Human(int id, String name){
    print("$id and $name");
  } 
  //parent name controct-2
  Human.detail(int rollno, int age){
    print("$rollno and  $age");
  }
}
//child class
class Male extends Human{
  //child constroct-1
  Male(int id, String name):super(id, name){}
  //child constroct-2
  Male.name(int rollno, int age):super.detail(rollno, age){}
}	When we have multiple constructors in botth parent and child clasess  
void main(){
  
  Crow detail=Crow(12.3, "Khadim", 12,1);
}
// parent class
class Animal{
  //propirty
  late int id;
  //propirty incilize  
  Animal(int id, int age){
    this. id=id;}
}
//child class pick Animal parent
class Birds extends Animal {
  //propirty
  late int rollNo;
  //propirt inclize
  Birds(int rollNo, int no):super(23,44){
    this.rollNo=rollNo;
    this.id=id;
  }
}
//child class pick Birds parent
class Pigen extends Birds{
  //proprity
  late String name;
  //propirty inclize
  Pigen(String name, int rollNo, int id):super (12,45){
    this.name=name;
    this.rollNo=rollNo;
   this.id=id; 
  }
}
//child claass pick Birds parent
class Crow extends Birds{
  late double gpa;
  // is me sb ki propirty ay gi
  Crow (double gpa, String name, int rollNo, int id):super (23,12){
  this.gpa=gpa;
    this.rollNo=rollNo;
    this.id=id;
    print("$gpa, $name, $rollNo,$id");  
  }
}	Agr kesi ki property late lga kr di ho to usy inclize krny ky ly last wali child class me sb ki property ay gi

player in dart
Function ky under ak asa nasted function hota ha jo aaccesable ho outside the function	
class Human {

Human ({required String name, required int age}) {
// parameterized constructor
print("I'm $name, and $age years old");
}

Human.details(int id, double gpa,
{required String name, required String city, required int age}) {
print("$name lives in $city and $age years old");
}
}

class Male extends Human {

Male(String name, int age): super(name: name, age: age) {
print("Male class constructor!");
}

}

class Female extends Human {
Female() :super.details(23, 3.34, name: "Fatima", city: "Lahore", age: 23) {
print("Female class constuctor!");
}
}
main.dart
class Human {

Human ({required String name, required int age}) {
// parameterized constructor
print("I'm $name, and $age years old");
}

Human.details(int id, double gpa,
{required String name, required String city, required int age}) {
print("$name lives in $city and $age years old");
}
}

class Male extends Human {

Male(String name, int age): super(name: name, age: age) {
print("Male class constructor!");
}

}

class Female extends Human {
Female() :super.details(23, 3.34, name: "Fatima", city: "Lahore", age: 23) {
print("Female class constuctor!");
}
}
main.dart
import 'package:flutter/material.dart';
import 'package:hello_world/inheritance.dart';





	
void  main(){
  Human detail =Human(a:[4],b:{2},c:{"c":4});
  Human detal1=Human.detail(1,2,3);
}
class Human{  
  Human({required List  a, required Set b, required Map <String, int> c}){
    print("$a,$b, $c");    
  }	
void  main(){
  Human detail =Human(Male(44), Boy(442));
  
}
//parent class
class Human{ 
  //parent constructor
  //parent+child-1+chil-2 constroctr
  Human(Male detail, Boy info  ){
    //print("$a,$b, $c");    
  }
  //parent name costruor
  Human.detail(int a, int b, int c){
    print("$a, $b, $c");
    
  }}
//chil class-1
  class Male{
    //child constrot
    Male(int d){
      print ("$d");
    
  }}
//chil class-2
    class Boy{
      Boy(int c){
        print ("$c");
      
    }
}	
void  main(){
  Human detail =Human (detail:Male(1), details: Boy(2));
 
  
}
//parent class
class Human{ 
  //parent constructor
  //parent+child-1+chil-2 constroctr
  Human({required Male detail,  required Boy details } ){
    //print("$a,$b, $c");    
  }
  //parent name costruor
  Human.detail(int a, int b, int c){
    print("$a, $b, $c");
    
  }}
//chil class-1
  class Male{
    //child constrot
    Male(int d){
      print ("$d");
    
  }}
//chil class-2
    class Boy{
      Boy(int c){
        print ("$c");
      
    }
}	
void  main(){
  Human detail =Human (detail:Male(info:Boy(),infos:Student(a:Developer())));  
}
//parent class
class Human{ 
  //parent constructor
  //parent+child-1
  Human( {required Male detail} ){
     }}
//chil class-1
  class Male{
    //child constuctor me (Boy class+Student class)
    Male({required Boy info, required Student infos}){
       
  }}
//chalid class-2
//Student class me Develper class
class Student{
  Student({required Developer a}){    
  }}
//chil class-3
    class Boy{
      Boy(){
        
    }}
//child class-4
      class Developer{
        Developer(){        
      }}	
 
Abstract class
//abstract class tb banaty hn jb child classes me function common or  or zarori hon gy
// A class created by an “abstract” keyword
//we can not create objects of abstract class
//Abstract class are alwys extends with other classes
//while inheriting child class must have to implement abstract method
//an abstract class can have one or more abstract mehod / function 
Abstract method/function
Is ki body ni hoti like : void abc();
//abstract class / parent class
abstract class Human {
  //absstract function 
  // ye function dosri class me implement hon gy
  void abc();
  void xyz();

//abstract class/parent class
abstract class Animal{
  //abstract function
  void voice();
}
//child class-1
class Dog extends Animal{
  @override
  void voice() {
    // TODO: implement voice
  }
  //abstract class implement
  
}
class Cat extends Animal{
  @override
  void voice() {
    // TODO: implement voice
  }
 

}
class Goat extends Animal{
  @override
  void voice() {
    // TODO: implement voice
  }
 

}

	
Fluter 
Fluter me her cheez widget hoti ha
Run app 
Ak building function ha, jo ak widget ly ga
Esy jo b widget mely ga usy paint / draw kr dy ga
It accepts  a root-widget and draw/paint on the screen
My base code is a root-widget (ye code khu bnaya live tamplet)
Widget (/ component, part of screen/ section)
Widget ak class ka name ha
Her property  ky against ak widget ho ga

Youtube play list for widget
Firebase analystics (package of the week)
MaterialApp
Ak widget ka name ha is me pori applicate creat ho gi
Scaffold 	
Important widget ( her screen me design is sy hi banta ha)
AppBar
Use for app bar, top bar, bottom bar
Material 
Is sy app ka desgine banta ha
Style 
TextStyle 
Use for text style font size, font style
Centre 
Text ko center me  lana
child: Center(child: Text("KHADIM HUSSAIN"),),

Container (ye box hota)
40 sy zayda margin or pedding ni deni
child: Container(
  width: 400,
  height: 400,
  color: Colors.yellow,
margin: EdgeInsets.all(80), (4 tarf sy samae margin)
margin:EdgeInsets.only(left: 2,right: 4,bottom: 8, top:4), (specific margin)
margin:EdgeInsets.fromLTRB(2, 2,3,4),(apni marzi sy LTRB  margin dena)
margin:EdgeInsets.zero, (ZERO MARGIN DENA)
margin:EdgeInsets.symmetric(vertical: 20,horizontal: 30),ver or hor margin dena
padding: EdgeInsets.only(left: 4,right: 4,top: 4,bottom: 5),
(same as margin)
Decoration
In container widget Color property doesnot work outside the decoration
import 'package:flutter/material.dart';
void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Functions"),
        ),
        body: Material(
          child: Center(
            child: Container( //box
              width: 200, //box width
              height: 200,
              margin:EdgeInsets.symmetric(vertical: 20,horizontal: 20), //box margin
              padding: EdgeInsets.only(left: 4,right: 4,top: 4,bottom: 5), //box paddin
              decoration: BoxDecoration( // container ki decoration
                  color: Colors.yellow, //color dena
                  shape: BoxShape.rectangle, // box ki shap
                  gradient:LinearGradient( // gradien line mem dena
                    begin: Alignment.center, // gradien start point
                    end: Alignment.bottomLeft, // end point
                    stops: [0.50,0,1], // stop me % color fully green ya red ho ga
                    colors: [Colors.green, Colors.red, Colors.grey],// color range
                  ),
                  //border: Border.all(width:13, color: Colors.black, style: BorderStyle.solid), // 4 trf ak hi tara ka  border  lagana
                  //border: Border.symmetric(vertical: BorderSide(width: 12,color: Colors.brown), horizontal: BorderSide(width: 11, color: Colors.black)),// apn marzi sy border banana
                  //borderRadius: BorderRadius.all(Radius.elliptical(10, 10)) // box ko round krna apni marzi sy
                  borderRadius: BorderRadius.only(topRight: Radius.elliptical(10, 20), topLeft: Radius.elliptical(10, 20))

              ),



            ),
          ),
        ),
      ),
    ),
  );

}






	 
Button sy ply jo icon hota ha esy leding icon khth hn
Bad me jo ho ga trailing icon 	
import 'package:flutter/material.dart';

void main() {
  runApp(
    MyStatelessWidget(),
  );
}

class MyStatelessWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Container Widget"),
        ),
        body: Material(
          child: Container(
            width: 400,
            height: 400,
            child: Text(
              "Hello World",
              style: TextStyle(fontSize: 30),
            ),

            margin: EdgeInsets.only(left: 50, top: 50),
            padding: EdgeInsets.all(30),

            decoration: BoxDecoration(
              color: Colors.orange,
              shape: BoxShape.rectangle,
              gradient: LinearGradient(
                begin: Alignment.topRight,
                end: Alignment.bottomLeft,
                stops: [0.2, 0.5, 0.8, 0.9],
                colors: [
                  Colors.brown,
                  Colors.white,
                  Colors.green,
                  Colors.yellow
                ],
              ),
              borderRadius: BorderRadius.only(
                bottomRight: Radius.elliptical(50, 50),
                bottomLeft: Radius.elliptical(50, 50),
                topRight: Radius.elliptical(50, 50),
                topLeft: Radius.elliptical(50, 50),
              ),
              border: Border.all(width: 10, color: Colors.pink),
            ),
          ),
        ),
      ),
    );
  }
}
	
 	
import 'dart:ui';

import 'package:flutter/material.dart';

void main() {
  runApp(
    MyStatelessWidget(),
  );
}

class MyStatelessWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Container Widget"),
        ),
        body: Material(
          child: Container(
            width: 200,
            height: 150,
            //color: Colors.yellow,
            alignment: Alignment.topRight,
            
            child: Text("KHADIM",
              //textDirection: TextDecoration.rtl,
              textAlign: TextAlign.justify,
                            overflow: TextOverflow.ellipsis, // zayda text honi ki sarorat  me ..... lga dy ga
              softWrap: false, // ak line jo jeta text a sky bs  wohi dekhay
              maxLines: 2, // jetni line ka text dekhan ho
              //child: Text("#",
           // semanticsLabel: "my code", //user ky ly text me # nazar ay ga lekin is me hum apni yadast ky ly jo marzi likh lain
STYLE PROPORITY
 style: TextStyle ( fontFamily: "TiltPrism", color: Colors.white,
              //textScaleFactor:5, // text ka size zayda krna
              fontStyle: FontStyle.italic,
                fontWeight: FontWeight.bold,
                fontSize: 30,
                letterSpacing: 13,
                wordSpacing: 12,
                height: 1

                                 //backgroundColor: Colors.grey,
              ),
              ),



            margin: EdgeInsets.only(left: 100, right: 50, bottom: 40, top: 200),
            //padding: EdgeInsets.only(left: 10, right: 20, bottom: 30, top: 40),
            decoration: BoxDecoration(
              color: Colors.blue,
              shape: BoxShape.rectangle,
              border: Border.all(width: 3, color: Colors.black),
             borderRadius: BorderRadius.only( // APNI MARZI CORNER BANANA
               topLeft: Radius.elliptical(420, 420),
               topRight: Radius.elliptical(420, 420),
               bottomLeft: Radius.elliptical(420, 420),
               bottomRight: Radius.elliptical(420, 420),
             ),
             // borderRadius: BorderRadius.circular(335),
              //borderRadius: BorderRadius.only(
               // bottomRight: Radius.elliptical(50, 50),
                //bottomLeft: Radius.elliptical(50, 50),
                //topRight: Radius.elliptical(50, 50),
                //topLeft: Radius.elliptical(50, 50),
              //),
              gradient: LinearGradient(
                begin: Alignment.centerLeft,
                end: Alignment.topLeft,
                colors: [Colors.orange, Colors.red,Colors.yellow],
              ),
              ),
            ),
          ),
          /*child: Container(
            width: 300,
            height: 250,
            child: Text(
              "Hello World",
              style: TextStyle(fontSize: 25),
            ),

            margin: EdgeInsets.only(left: 50, top: 50),
            padding: EdgeInsets.all(30),

            decoration: BoxDecoration(
              color: Colors.orange,
              shape: BoxShape.rectangle,
              gradient: LinearGradient(
                begin: Alignment.topRight,
                end: Alignment.bottomLeft,
                stops: [0.2, 0.5, 0.8, 0.9],
                colors: [
                  Colors.brown,
                  Colors.white,
                  Colors.green,
                  Colors.yellow
                ],
              ),
              borderRadius: BorderRadius.only(
                bottomRight: Radius.elliptical(50, 50),
                bottomLeft: Radius.elliptical(50, 50),
                topRight: Radius.elliptical(50, 50),
                topLeft: Radius.elliptical(50, 50),
              ),
              border: Border.all(width: 10, color: Colors.pink),
            ),
          ),*/
        ),

    );
  }
}
	
 	 
import 'dart:ui';

import 'package:flutter/material.dart';

void main() {
  runApp(
    MyStatelessWidget(),
  );
}

class MyStatelessWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("Container Widget"),
        ),
        body: Column(
          children: [
            DefaultTextStyle(style: TextStyle(fontSize: 44,color: Colors.white,
                fontStyle: FontStyle.italic,
                fontWeight: FontWeight.bold,
                letterSpacing: 13,
                wordSpacing: 12,
                height: 1,



            ),
                child:
            Container(
              width: 550,
              height: 550,

              color: Colors.greenAccent,
              //color: Colors.yellow,
              alignment: Alignment.center,
              margin: EdgeInsets.only(left: 100, right: 50, bottom: 40, top: 200),

            child: Column(
              children: [
                Text("KHADIM"),
                Text("HUSSAIN"),
              ],),
             // gradient: LinearGradient(
               // begin: Alignment.center,
                //end: Alignment.centerLeft,
                //colors: [Colors.greenAccent,
                  //Colors.white,
                  //Colors.black],
              //),
            ),

            ) ,
        ]
        ),

      ),

    );
  }
}
	
TextField widget
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("text widget"),
        ),
        body: Material(
          child: Center(
            child: Container(
              margin: EdgeInsets.all(22),
              child: TextField(
                undoController: UndoHistoryController(),
                maxLength: 39,
                textCapitalization: TextCapitalization.characters,
                textAlign: TextAlign.center,
                keyboardType: TextInputType.emailAddress,
                decoration: InputDecoration(
                  hintText: "Enter Your Name",
                  label: Text("Name"),
                  icon: Icon(Icons.person),
                  prefixIcon: Icon(Icons.access_alarm_outlined),
                  suffixIcon: Icon(Icons.ac_unit),
                  border: OutlineInputBorder(),
                  hintStyle: TextStyle(fontSize: 21, color: Colors.green),
                  labelStyle: TextStyle(color: Colors.red),
                ),
              ),
            ),
          ),
        ),
      ),
    ),
  );
}
	
Row and column me children me kesi b tara ka widget  a skta ha
Container(
  padding: EdgeInsets.all(4),
  color: Colors.grey,
  child: Row(
    children: [
      Expanded(
        child: Container(
          padding: EdgeInsets.all(4),
          color: Colors.green,
          child: Text("khadim"),
        ),
      ),
      Expanded(
        child: Container(
          padding: EdgeInsets.all(4),
          color: Colors.yellow,
          child: Text("Hussain"),
        ),    
Alt+ener	
KHADIM MYBASECODE
void main (){
  
MaterialApp(
home: Scaffold(
appBar: AppBar(
title: Text("my app"),
),
body: Material(
child:Container (
),
),
),
);
}
        
	
Colum & row	
ListView
child: ListView(
  children: [
    Container(
      alignment: Alignment.center,
      padding: EdgeInsets.all(3),
      color:Colors.yellow,
      child: Center(child: Text("pakistan"),),
    ),
leading: Icon(Icons.person),                        list ky front pr
trailing: Icon(Icons.perm_camera_mic),          list ky end  pr
	
# listview
import 'dart:js';

import 'package:flutter/material.dart';

void main() {
  List<String> newsChannel = ["JEO NEWS", "EXPRESS NEWS", "SMMA NEWS", "7 NEWS", "JEO SUPPER NEWS", "PTV LIVE", "PTV NEWS"];
  List<String> job = ["Private Channel", "Private Channel", "Private Channel", "Private Channel", "Private Channel", "Private Channel","Govt Channel"];
  List icon = [Icons.account_balance_wallet,   Icons.account_balance_wallet,  Icons.access_alarm_outlined,    Icons.ac_unit,Icons.account_balance_wallet,    Icons.access_alarm_outlined,    Icons.ac_unit   ];
  List trailingicon = [   Icons.account_balance_wallet,   Icons.account_balance_wallet,  Icons.access_alarm_outlined,    Icons.ac_unit,Icons.account_balance_wallet,    Icons.access_alarm_outlined,    Icons.ac_unit];
  List colors = [Colors.green, Colors.red, Colors.blue, Colors.green, Colors.red, Colors.blue, Colors.orangeAccent];
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Center(
            child: Text("PAKISTAN NEWS CHENELS"),
          ),
        ),
        body: Material(
          child: Card(
            elevation: 44,
            child: Container(
             margin: EdgeInsets.all(10),
              child: ListView.builder(
                itemCount: newsChannel.length,
                itemBuilder: (context, index) {
                  return Container(
                    color: colors[index],
                    margin: EdgeInsets.all(4),
                    child: ListTile(
                        textColor: Colors.white,
                        iconColor: Colors.white,
                        title: Text(newsChannel[index]),
                        titleAlignment: ListTileTitleAlignment.center,
                        subtitle: Text(job[index]),
                        leading: Icon(icon[index]),
                        trailing: Icon(trailingicon[index])),
                  );
                },
              ),
            ),
          ),
        ),
      ),
    ),
  );
}	
 

# dart-lectures
