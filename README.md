題目1:
int x =250;(設定最大值)<br>

int y =25;(遞增數值)<br>

void setup() {<br>

  // put your setup code here, to run once:<br>



  pinMode (3,OUTPUT);(設定輸出腳)<br>

}<br>



void loop() {<br>

  // put your main code here, to run repeatedly:<br>

   analogWrite(3,x);<br>

   x = x-y;<br>

   if(x ==0 || x ==250)<br>

   y = -y;<br>

   delay(80);(延遲)<br>

   }<br>
   

  



題目遺失<br>
