題目1:
int x =250;(設定最大值)

int y =25;(遞增數值)

void setup() {

  // put your setup code here, to run once:



  pinMode (3,OUTPUT);(設定輸出腳)

}



void loop() {

  // put your main code here, to run repeatedly:

   analogWrite(3,x);

   x = x-y;

   if(x ==0 || x ==250)

   y = -y;

   delay(80);(延遲)

   }
   

  



題目遺失
