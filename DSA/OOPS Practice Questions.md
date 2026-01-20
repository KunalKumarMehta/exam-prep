Find Output of each of this code:

Q1  
class Meter {  
    protected int x;  
    Meter(int x){ this.x \= x; }

    int read(int y){ return x \+ y; }  
    int read(int y, int m){ return (x \- y) % m; }

    static int clamp(int v, int lo, int hi){  
        if(v \< lo) return lo;  
        if(v \> hi) return hi;  
        return v;  
    }  
}  
class SmartMeter extends Meter {  
    SmartMeter(int x){ super(x); }

    @Override  
    int read(int y){  
        int t \= clamp(y, 3, 9);  
        return read(t, 7);  
    }  
}  
public class Main {  
    public static void main(String\[\] args){  
        Meter m \= new SmartMeter(20);  
        System.out.print(m.read(2));  
    }  
}

Q2  
class Coupon {  
    private int code;  
    Coupon(int code){ this.code \= code; }

    int apply(int price){ return price \- (code % 10); }  
    int apply(int price, int cap){ return (price \- code) \+ cap; }

    static int sumDigits(int n){  
        int s \= 0;  
        while(n \> 0){ s \+= n % 10; n /= 10; }  
        return s;  
    }  
}  
class FestCoupon extends Coupon {  
    FestCoupon(int code){ super(code); }

    @Override  
    int apply(int price){  
        return apply(price, sumDigits(price));  
    }  
}  
public class Main {  
    public static void main(String\[\] args){  
        Coupon c \= new FestCoupon(57);  
        System.out.print(c.apply(49));  
    }  
}

Q3  
class Locker {  
    protected int pin;  
    Locker(int pin){ this.pin \= pin; }

    int open(int key){ return pin ^ key; }  
    int open(int key, int shift){ return (pin \<\< shift) \+ key; }

    static int bits(int n){  
        int c \= 0;  
        while(n \> 0){ c \+= (n & 1); n \>\>= 1; }  
        return c;  
    }  
}  
class BioLocker extends Locker {  
    BioLocker(int pin){ super(pin); }

    @Override  
    int open(int key){  
        return open(key, bits(key));  
    }  
}  
public class Main {  
    public static void main(String\[\] args){  
        Locker L \= new BioLocker(6);  
        System.out.print(L.open(5));  
    }  
}

Q4  
class Account {  
    private int bal;  
    Account(int bal){ this.bal \= bal; }

    int txn(int amt){ return bal \- amt; }  
    int txn(int amt, int fee){ return bal \- amt \- fee; }

    static int fee(int amt){  
        return (amt % 4\) \+ 1;  
    }  
}  
class PremiumAccount extends Account {  
    PremiumAccount(int bal){ super(bal); }

    @Override  
    int txn(int amt){  
        return txn(amt, fee(amt) \- 1);  
    }  
}  
public class Main {  
    public static void main(String\[\] args){  
        Account a \= new PremiumAccount(100);  
        System.out.print(a.txn(17));  
    }  
}

Q5  
class Oven {  
    protected int temp;  
    Oven(int temp){ this.temp \= temp; }

    int bake(int mins){ return temp \* mins; }  
    int bake(int mins, int mode){ return (temp \+ mode) \* (mins \- 1); }

    static int mode(int mins){  
        return (mins % 3\) \* 10;  
    }  
}  
class SmartOven extends Oven {  
    SmartOven(int temp){ super(temp); }

    @Override  
    int bake(int mins){  
        return bake(mins, mode(mins));  
    }  
}  
public class Main {  
    public static void main(String\[\] args){  
        Oven o \= new SmartOven(5);  
        System.out.print(o.bake(8));  
    }  
}

