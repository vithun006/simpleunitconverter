#include <stdio.h>
int main() {
char category;
int tempChoice;
int currencyChoice;
int massChoice;
int userinputF;
int userinputC;
int userinputUSDtoEuro;
int userinputUSDtoJPY;
int userinputUSDtoRMB;
int userinputUSDtoRupee;
int userinputkg;
int userinputmg;
int fahrenheitToCelcius;
int celciusToFahrenheit;
float USDtoEURO ;
float USDtoJPY;
float USDtoRMB;
float ounceToPounds;
float gramsToPounds;
printf("Welcome to Unit Converter! \n");
printf("Here is a list of conversation to choose from: \n");
printf("Temperature(T)\nCurrency(C)\nMass(M) \n");
printf("Please enter the letter you want to convert.\n");
scanf("%c",&category);
if(category == 'T'){
printf("Welcome to Temperature Converter! \n");
printf("Here is a list of conversations to choose from: \n");
printf("Enter 1 for Fahrenheit to Celsius. \n");
printf("Enter 2 for Celsius to Fahrenheit. \n");
scanf("%d",&tempChoice);
if(tempChoice == 1){
printf("Please enter the Fahrenheit degree: \n");
scanf("%d",&userinputF);
fahrenheitToCelcius = ((userinputF-32) * (5.0/9.0));
printf("Celcius: %d",fahrenheitToCelcius);
}
else if(tempChoice == 2){
printf("Please enter the Celcius degree: \n");
scanf("%d",&userinputC);
celciusToFahrenheit = ((9.0/5.0)*userinputC + 32);
printf("Fahrenheit: %d",celciusToFahrenheit);
}
else
printf("Please enter the correct choice. \n");
}
else if(category == 'C') {
printf("Welcome to Currency Converter! \n");
printf("Here is a list of conversations to choose from: \n");
printf("Enter 1 for USD to Euro. \n");
printf("Enter 2 for USD to JPY. \n");
printf("Enter 3 for USD to RMB. \n");
printf("Enter 4 for USD to Rupee. \n");
scanf("%d",&currencyChoice);
if(currencyChoice == 1){
printf("Please enter the USD amount: \n");
scanf("%d",&userinputUSDtoEuro);
USDtoEURO = userinputUSDtoEuro * 0.87;
printf("Euro: %.2f",USDtoEURO); // %.2f = rounds the float to only 2 decimal places;
}
else if(currencyChoice == 2){
printf("Please enter the USD amount: \n");
scanf("%d",&userinputUSDtoJPY);
USDtoJPY = userinputUSDtoJPY * 111.09;
printf("JPY: %.2f",USDtoJPY);
}
else if(currencyChoice == 3) {
printf("Please enter the USD amount: \n");
scanf("%d",&userinputUSDtoRMB);
USDtoRMB = userinputUSDtoRMB * 6.82;
printf("RMB: %.2f",USDtoRMB);
}
else if(currencyChoice == 4){
printf("please enter the USD amount: \n");
scanf("%d",&userinputUSDtoRupee);;
float USDtoRupee = userinputUSDtoRupee * 78.30;
printf("Rupee: %.2f",USDtoRupee);
}
else
printf("Please enter correct choice. \n");
}
else if(category == 'M'){
printf("Welcome to Mass Converter! \n");
printf("Here is a list of conversations to choose from: \n");
printf("Enter 1 for Kilogram to Gram. \n");
printf("Enter 2 for Milligram to Gram. \n");
scanf("%d",&massChoice);
if(massChoice == 1){
printf("Please enter the Kilogram amount: \n");
scanf("%d",&userinputkg);
float kgtog = userinputkg * 1000;
printf("Gram: %.2f",kgtog);
}
else if(massChoice == 2){
printf("Please enter the Milligram amount: \n");
scanf("%d",&userinputmg);
float mgtog = userinputmg * 0.001;
printf("Gram: %.2f",mgtog);
}
}
else
printf("Please enter the correct choice. \n");
return 0;
}
