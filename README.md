# c++_note
--------------
質數表
可以把質數的倍數都去掉
int p[1045]={0}
    for(int i=2;i<p[1045];i++){
        if(p[i]==0){
            for(int j=i+i;j<1045;j+=i)//將i的倍數設定成不是質數
            { 
                p[j]=1;
            }
        }
    }
--------------
