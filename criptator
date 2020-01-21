#include "stdafx.h"
#include <iostream>
#include <string>
#include <iomanip>
#include <cmath>
#include <algorithm>
#include <cctype>
#include <windows.h>
using namespace std;


string message;
string pezzetto;
string messagiofinale;
string mode;
string secondround;

int _tmain(int argc, _TCHAR* argv[])
{            
	cout<<"You want to code or decode?"<<endl;
	cin>>mode;
	if(mode=="code"){
						int code,codicenumerico,cou,numlettere,n,a;
                      
						n=0;
						a=0;
						cout<<"How many letters the message have: ";
						cin>>numlettere;
						cout<<"Give me the key: ";
						cin>>code;				
						cout<<"Give me the message acsepted caracters a-z and for space use / (press enter after all letters): "<<endl;
						do{
							do{ 
								cin>>message;
								if(message=="/"){
								codicenumerico=0;
								cou=codicenumerico+code;}
								else if(message=="a"){
								codicenumerico=1;
								cou=codicenumerico+code;}
								else if(message=="b"){
								codicenumerico=2;
								cou=codicenumerico+code;}
								else if(message=="c"){
								codicenumerico=3;
								cou=codicenumerico+code;}
								else if(message=="d"){
								codicenumerico=4;
								cou=codicenumerico+code;}
								else if(message=="e"){
								codicenumerico=5;
								cou=codicenumerico+code;}
								else if(message=="f"){
								codicenumerico=6;
								cou=codicenumerico+code;}
								else if(message=="g"){
								codicenumerico=7;
								cou=codicenumerico+code;}
								else if(message=="h"){
								codicenumerico=8;
								cou=codicenumerico+code;}
								else if(message=="i"){
								codicenumerico=9;
								cou=codicenumerico+code;}
								else if(message=="j"){
								codicenumerico=10;
								cou=codicenumerico+code;}
								else if(message=="k"){
								codicenumerico=11;
								cou=codicenumerico+code;}
								else if(message=="l"){
								codicenumerico=12;
								cou=codicenumerico+code;}
								else if(message=="m"){
								codicenumerico=13;
								cou=codicenumerico+code;}
								else if(message=="n"){
								codicenumerico=14;
								cou=codicenumerico+code;}
								else if(message=="o"){
								codicenumerico=15;
								cou=codicenumerico+code;}
								else if(message=="p"){
								codicenumerico=16;
								cou=codicenumerico+code;}
								else if(message=="q"){
								codicenumerico=17;
                                cou=codicenumerico+code;}
								else if(message=="r"){
								codicenumerico=18;
								cou=codicenumerico+code;}
								else if(message=="s"){
								codicenumerico=19;
								cou=codicenumerico+code;}
								else if(message=="t"){
								codicenumerico=20;
								cou=codicenumerico+code;}
								else if(message=="u"){
								codicenumerico=21;
								cou=codicenumerico+code;}
								else if(message=="v"){
								codicenumerico=22;
								cou=codicenumerico+code;}
								else if(message=="w"){
								codicenumerico=23;
								cou=codicenumerico+code;}
								else if(message=="x"){
								codicenumerico=24;
								cou=codicenumerico+code;}
								else if(message=="y"){
								codicenumerico=25;
								cou=codicenumerico+code;}
								else if(message=="z"){
								codicenumerico=26;
								cou=codicenumerico+code;}
								else {cout<<"coming soon"<<endl;}

								if (cou==0){pezzetto="/";}
								else if (cou==1){pezzetto="a";}
								else if (cou==2){pezzetto="b";}
								else if (cou==3){pezzetto="c";}
								else if (cou==4){pezzetto="d";}
								else if (cou==5){pezzetto="e";}
								else if (cou==6){pezzetto="f";}
								else if (cou==7){pezzetto="g";}
								else if (cou==8){pezzetto="h";}
								else if (cou==9){pezzetto="i";}
								else if (cou==10){pezzetto="j";}
								else if (cou==11){pezzetto="k";}
								else if (cou==12){pezzetto="l";}
								else if (cou==13){pezzetto="m";}
								else if (cou==14){pezzetto="n";}
								else if (cou==15){pezzetto="o";}
								else if (cou==16){pezzetto="p";}
								else if (cou==17){pezzetto="q";}
								else if (cou==18){pezzetto="r";}
								else if (cou==19){pezzetto="s";}
								else if (cou==20){pezzetto="t";}
								else if (cou==21){pezzetto="u";}
								else if (cou==22){pezzetto="v";}
								else if (cou==23){pezzetto="w";}
								else if (cou==24){pezzetto="x";}
								else if (cou==25){pezzetto="y";}
								else if (cou==26){pezzetto="z";}
								else{cout<<"Something went wrong, probably the criptation number is too high.";}
								n++;
								a++;
								messagiofinale.append(pezzetto);}

							 while(n<numlettere);
					
      						 a++;
						  }
						while(a<numlettere);

						cout<<"Your coded message is: "<<messagiofinale<<endl;
					}
	else if(mode=="decode"){
		
								int code,codicenumerico,cou,numlettere,n,a;
		                      
								n=0;
								a=0;
								cout<<"How many letters the message have: ";
								cin>>numlettere;
								cout<<"Give me the key: ";
								cin>>code;					
								cout<<"Give me the message (press enter after all coded letters): "<<endl;
								do{
									do{ 
										cin>>message;
										if(message=="/"){
										codicenumerico=0;
										cou=codicenumerico-code;}
										else if(message=="a"){
										codicenumerico=1;
										cou=codicenumerico-code;}
										else if(message=="b"){
										codicenumerico=2;
										cou=codicenumerico-code;}
										else if(message=="c"){
										codicenumerico=3;
										cou=codicenumerico-code;}
										else if(message=="d"){
										codicenumerico=4;
										cou=codicenumerico-code;}
										else if(message=="e"){
										codicenumerico=5;
										cou=codicenumerico-code;}
										else if(message=="f"){
										codicenumerico=6;
										cou=codicenumerico+code;}
										else if(message=="g"){
										codicenumerico=7;
										cou=codicenumerico-code;}
										else if(message=="h"){
										codicenumerico=8;
										cou=codicenumerico-code;}
										else if(message=="i"){
										codicenumerico=9;
										cou=codicenumerico+code;}
										else if(message=="j"){
										codicenumerico=10;
										cou=codicenumerico-code;}
										else if(message=="k"){
										codicenumerico=11;
										cou=codicenumerico+code;}
										else if(message=="l"){
										codicenumerico=12;
										cou=codicenumerico-code;}
										else if(message=="m"){
										codicenumerico=13;
										cou=codicenumerico-code;}
										else if(message=="n"){
										codicenumerico=14;
										cou=codicenumerico-code;}
										else if(message=="o"){
										codicenumerico=15;
										cou=codicenumerico-code;}
										else if(message=="p"){
										codicenumerico=16;
										cou=codicenumerico-code;}
										else if(message=="q"){
										codicenumerico=17;
										cou=codicenumerico-code;}
										else if(message=="r"){
										codicenumerico=18;
										cou=codicenumerico-code;}
										else if(message=="s"){
										codicenumerico=19;
										cou=codicenumerico-code;}
										else if(message=="t"){
										codicenumerico=20;
										cou=codicenumerico-code;}
										else if(message=="u"){
										codicenumerico=21;
										cou=codicenumerico-code;}
										else if(message=="v"){
										codicenumerico=22;
										cou=codicenumerico-code;}
										else if(message=="w"){
										codicenumerico=23;
										cou=codicenumerico-code;}
										else if(message=="x"){
										codicenumerico=24;
										cou=codicenumerico-code;}
										else if(message=="y"){
										codicenumerico=25;
										cou=codicenumerico-code;}
										else if(message=="z"){
										codicenumerico=26;
										cou=codicenumerico-code;}
										else {cout<<"coming soon"<<endl;}

                                        if (cou==0){pezzetto="/";}
										else if (cou==1){pezzetto="a";}
										else if (cou==2){pezzetto="b";}
										else if (cou==3){pezzetto="c";}
										else if (cou==4){pezzetto="d";}
										else if (cou==5){pezzetto="e";}
										else if (cou==6){pezzetto="f";}
										else if (cou==7){pezzetto="g";}
										else if (cou==8){pezzetto="h";}
										else if (cou==9){pezzetto="i";}
										else if (cou==10){pezzetto="j";}
										else if (cou==11){pezzetto="k";}
										else if (cou==12){pezzetto="l";}
										else if (cou==13){pezzetto="m";}
										else if (cou==14){pezzetto="n";}
										else if (cou==15){pezzetto="o";}
										else if (cou==16){pezzetto="p";}
										else if (cou==17){pezzetto="q";}
										else if (cou==18){pezzetto="r";}
										else if (cou==19){pezzetto="s";}
										else if (cou==20){pezzetto="t";}
										else if (cou==21){pezzetto="u";}
										else if (cou==22){pezzetto="v";}
										else if (cou==23){pezzetto="w";}
										else if (cou==24){pezzetto="x";}
										else if (cou==25){pezzetto="y";}
										else if (cou==26){pezzetto="z";}
										else{cout<<"Something went wrong, probably the criptation number is too high.";}
										n++;
										a++;
										messagiofinale.append(pezzetto);}

									 while(n<numlettere);
							
      								 a++;
								  }
								while(a<numlettere);

								cout<<"Your coded message is: "<<messagiofinale<<endl;
							}
	else{cout<<"There is no other options."<<endl;}

						

return 0;
}
