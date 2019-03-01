##Yahor Harbatovich

*__e-mail: 270@tut.by__
*__tel:+375-29-7783569__

I think there's no prospects at my preset job so I decided to change profession.
Choosed IT as most promising sphere and keep making first steps into it.
Think I have a potential in programming so it's only a matter of time for me to enter the profession.
For now almost all my spare-time I spend on exploring an IT technologies and I find it very exciting.

#####About skills:
*HTML/CSS basics
*JS basics
*GIT basics
*Java SE basics
*SQL basics

Recently done some tasks and there's some code out of it:
'''javascript
    function makeExchange(currency) {
    var ret={}
    if (currency>10000){
       ret.error="You are rich, my friend! We don't have so much coins for exchange"
       console.log(ret)
    return ret   
    }
    if (currency<=0) return ret
    x=Math.trunc(currency/50)
    if (x>0){
        ret['H']=x 
        currency-=50*x
    }
    x=Math.trunc(currency/25)
    if (x>0) {
        ret['Q']=x
        currency-=25*x
    }  
    x=Math.trunc(currency/10)
    if (x>0) {
        ret['D']=x
        currency-=10*x
    } 
    x=Math.trunc(currency/5)
    if (x>0) {
        ret['N']=x
        currency-=5*x
    }  
    if (currency>0) {
        ret['P']=currency      
    }  
    return ret
'''

'''javascript
function getZerosCount(number, base) {  
 var  arr=[];
 if (number<2) return 0;
for (let k=2;k<=base;k++){  
  while (base%k==0 && base>1){
    arr.push(k);
    base/=k;    
  }   
}
for (i=0; i<arr.length; i++){
  st=1;
  sum=0;
  do{
    del=Math.pow(arr[i],st);
    sum+=Math.trunc(number/del);
    st++;
    }
  while(Math.trunc(number/del)>0);
  arr[i]=sum; 
}
for (i=0; i<arr.length; i++){
  pow=1;
  for (j=i+1; j<arr.length; j++){
    if(arr[i]==arr[j]) pow++;
  }
  arr[i]=Math.trunc(arr[i]/pow);
}  
var min=arr[0];
for (i=1; i<arr.length; i++ ){
  if (arr[i]<min) min=arr[i];
} 
return min;
}
'''

#####Education:
*BSUIR, Multichannel telecommunications
*Belsoft, courses "Windows 2003 Server administration"
*Belhard, courses "Java SE & SQL basics"

#####English level: 
_Intermediate_

