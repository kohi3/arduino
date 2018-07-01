01.BasicのBrinkの数字変えただけです。

# 比較
## サンプル
![sampl](https://raw.githubusercontent.com/kohi3/arduino/master/setup/ex_1000sec.gif)
``` C
// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```
## ちょっと変えた

![modify](https://raw.githubusercontent.com/kohi3/arduino/master/setup/fix_200.gif)
``` C
// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(200);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(500);                       // wait for a second
}
```
