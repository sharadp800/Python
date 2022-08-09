basic of the python learning with the help of the java 
 
// following program is for the rev num

int number =4565,reverse=0;
while(number!=0){
int reminder = number%10;
reverse =reverse*10+reminder;
number=number/10;
}System.out.println(reverse);

}