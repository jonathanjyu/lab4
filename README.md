# lab4
4-1
0000000000400624 T _Z7averagePdRd
0000000000400652 T _Z7averageif

4-2
1 8
4 8
4 8
8 8
第一直排的數字是每個type所占的記憶體空間,char占1byte,int占4bytes,float占4bytes,double占8bytes.
第二直排的數字都是8,因為指標是帶有記憶體的位址,所以每種type的大小都一樣,這樣才能找到所有的位址.
8是因為我的電腦作業系統是 64bit(8bytes),如果是在32bit的作業環境下執行,結果會是4.
