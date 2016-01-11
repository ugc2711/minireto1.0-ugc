# minireto1.0-ugc

import UIKit

var str = "Hello, playground"


for n in 0...100{
   
    
    
    if (n >= 30 && n <= 40){
    
    if(n%2==0){
        
        if (n % 5==0) {
            print(n , "PAR", "BINGO!!!", "VIVASWIFT!!!")
            } else{print(n , "PAR", "VIVASWIFT!!!")}
        
    }else{ if (n % 5 == 0){
        
        print(n , "IMPAR", "BINGO","VIVASWIFT!!!")
    }else{ print(n , "IMPAR", "VIVASWIFT!!!")
        }  }
        
    }
    
    
    
    else if(n%2==0){
        
        if (n%5==0) {
            print(n , "PAR", "BINGO!!!")
        } else{print(n , "PAR")}
        
    }else{if (n%5==0){
        print(n , "IMPAR", "BINGO")}
     else {
        print(n , "IMPAR")}
    }
}
