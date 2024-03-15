# p
public static void main(String[] args) {
        double sonuç=0,fiyat,vergi,kdvOran1=0.18, kdvOran2=0.08;
        Scanner al=new Scanner(System.in);
        System.out.println("vergi uygulancak fiyatı yazınız.");
        fiyat=al.nextDouble();
        vergi= (fiyat<1000)? (fiyat*0.18): (fiyat*0.08);
       
        sonuç=fiyat+vergi;
        System.out.println("kdvli tutar="+sonuç);
        System.out.println("kdv miktarı="+vergi);
        
    }
    
