# UFCpoo3JAVA



package com.mycompany.ultraemotioncombat;


public class UltraEmojiCombat {
    
    public static void main (String [] args ){
        
        Lutador l[] = new Lutador[6];
                
              l [0]  = new Lutador ("Doni","França",31,1.87f,68.9f,11,2,1 );
              l [1]  = new Lutador ("Carlos","EUA", 28,1.77f,77.4f,10,3,1);
              l [2]  = new Lutador ("joão","Argentina", 33,1.70f,72.0f,15,3,6);
              l [3]  = new Lutador ("Jorge","Brasil", 27,1.85f,80.0f,15,9,0);
              l [4]  = new Lutador ("Prieto","italia", 35,1.80f,90.0f,8,4,3);
              l [5]  = new Lutador ("Paser","Ucrania", 26,1.95f,120.0f,15,9,4);        
        
              
             Luta UEC01 = new Luta ();
             UEC01.marcarLuta(l[1], l[2]);
             UEC01.lutar();
             l[1].status();
             l[2].status();
    }
    
}
