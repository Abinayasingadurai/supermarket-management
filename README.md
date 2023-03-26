*****************************************************Abinaya.S*****************************************************
***********************************************kcg college of technology*******************************************

//supermarket management system
/*  1. welcome message
    2. list of items (5-10 items display those items using cout)
    3. chosse your item (for every item , create a class . In that class , rate of basic quantity)
    4. last total cost (add all the rate)
*/
#include <iostream>          //header file
using namespace std;        //main function



//Ginger price 
float Ginger(){
    cout<<"Ginger 1kg = rs 25";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*25;
    return quantity*25;
}
//tomato
float tomato(){
    cout<<"potato 1kg = rs 65";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*65;
        return quantity*65;
//ladysfinger        
}
float ladysfinger(){
    cout<<" lady's finge 1kg = rs 45";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*45;
        return quantity*45;
// clusterBeans       
}
float clusterBeans(){
    cout<<"cluster_Beans 1kg = rs 55";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*55;
    return quantity*55;
}
//Radish
float Radish(){
    cout<<" Radish 1kg = rs 20";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*20;
    return quantity*20;
}
//jackfruit
float jackfruit(){
    cout<<"jack_fruit 2kg = rs 95";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*95;
    return quantity*95;
}
//Bringal
float Bringal (){
    cout<<"Bringal 1kg = rs 25";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*25;
    return quantity*25;
}
//mushroom
float mushroom(){
    cout<<"mushroom 1kg = rs 68";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*68;
    return quantity*68;
}
//Beetroot
float Beetroot(){
    cout<<"Beetroot 1kg = rs 41";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*41;
    return quantity*41;
}
// Bittergourd
float Bittergourd(){
    cout<<"Bitter_gourd 1kg = rs75";
    float quantity ;
    cout<<"\n enter the quantity";cin>>quantity;
    cout<<"the total cost is:"<<quantity*75;
    return quantity*75;
}
    
int main()
{
     int option;
    float baseamount, totalamount,a,b,c,d,e,f,g,h,i,j;     //declare the variable
      
    cout<<"\t\tWelcome to Tamilazhi supermarket";
    cout<<"\nThe first three ways to progress\n******1.Productivity\n2.Production quality\n3.Timely delivery\n4.This is our Taraka Mantra*******";
    start:
    cout<<"\n\n 1.Ginger \n2.tomato \n3.ladysfinger\n4.clusterBeans\n5.Radish\n6.jackfruit\n7.Bringal\n8.mushroom\n9.Beetroot\n10.Bittergourd";
     cout<<"\nenter your choice:";cin>>option;
      switch(option){             //using switch case
          case 1:
          a=Ginger();
          break;
          case 2:
          b=tomato();
          break;
           case 3:
          c=ladysfinger();
          break;
          case 4:
          d=clusterBeans();
          break;
          case 5:
          e=Radish();
          break;
          case 6:
          f=jackfruit();
          break;
          case 7:
          g= Bringal();
          break;
          case 8:
          h=mushroom();
          break;
          case 9:
          i=Beetroot();
          break;
          case 10:
          j=Bittergourd();
          break;
          default:
            exit(0);
      }
       totalamount=a+b+c+d+e+f+g+h+i+j;        //get the output
      cout<<"\nthe overall total cost is:"<<totalamount;
      cout<<"\nKnowing that what you ate before has become normal, when you are very hungry, avoid food that is against your body and time, and   eat what you need.";
      goto start;
      
      return 0;
}
